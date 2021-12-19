<template>
  <div id="player">
    <div id="video">
      <video id="media" width="720" height="400">
        <source src="/video/Bella Italia.mp4"/>
      </video>
      <nav>
        <div id="buttons">
          <input type="button" id="play" value="Play">
          <input type="button" id="mute" value="Mute">
        </div>
        <div id="bar">
          <div id="progress"></div>
        </div>
        <div id="control">
          <input type="range" id="volume" min="0" max="1" step="0.1" value="0.6">
        </div>
        <div class="clear"></div>
      </nav>
    </div>
  </div>
</template>

<script>

export default {
  name: "video",
  setup(){
    var media,bar,play,mute,progress,volume,loop,maxim;
    function initiate(){
      //обьявили обьекты или элементы//
      maxim=400;
      media=document.getElementById('media');
      play=document.getElementById('play');
      mute=document.getElementById('mute');
      bar=document.getElementById('bar');
      progress=document.getElementById('progress');
      volume=document.getElementById('volume');
      //обьяыляем дополнительные прослушиватели для них//
      play.addEventListener('click',push);
      bar.addEventListener("click", muve);
      volume.addEventListener("change", level);
      mute.addEventListener("click", sound);//прослушивает события//
    }
    function push(){
      //должна проверить либо запустить либо остановить видео//
      if(!media.paused && !media.ended) {
        media.pause();
        play.value = 'Play';
        clearInterval(loop);
      }else{//методы//
        media.play();
        play.value = 'Pause';
        loop=setInterval(status,1000);//пользователь клик на воспроизв запускается интервал и наоборот очитка//
      }

    }
    function status(){
      if(!media.ended){
        var size = parseInt(media.currentTime * maxim / media.duration);
        progress.style.width=size+'px';
      }
      else{
        progress.style.width="0px";
        play.innerHTML='Play';
        clearInterval(loop);

      }
    }
    function muve(e){
      if(!media.ended && !media.paused){
        var mouseX = e.pageX - bar.offsetLeft;
        var newtime = mouseX*media.duration/maxim;
        media.currentTime = newtime;
        progress.style.width = mouseX+'px';
      }
    }
    function level(){
      media.volume=volume.value;
    }
    function sound(){
      if (mute.value=='Mute'){
        media.mute=true;
        mute.value='Sound';
      }
      else{
        media.mute=false;
        mute.value='Mute';
      }
    }
    addEventListener("load",initiate);

  },

}
</script>
<style lang="scss">
#player{
  margin-left: 300px;
  width:720px;
  background: #28add4;
  padding: 10px;
  border-radius: 5px;
}
#play, #mute{
  width:65px;
  border-radius:2px;
  background: #8fc712;
  color:white;
}
#buttons{
  float: left;
  padding: 5px;
  padding-top: 2px;
}
#bar{
  float: left;
  width: 400px;
  height:16px;
  padding:2px;
  background: #cecece;
  margin: 2px 5px;
}
#progress{
  height: 16px;
  background: #8fc712;
  width: 0px;
}
.clear{
  clear:both;
}

</style>
