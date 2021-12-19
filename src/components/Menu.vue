<template>
  <div>
    <div class="menu">
      <div class="menu_header d-flex flex-row align-items-center justify-content-start">
        <div class="menu_logo"><a href="/">Bon voyage</a></div>
        <div class="menu_close_container ml-auto"><div class="menu_close"><div></div><div></div></div></div>
      </div>
      <div class="menu_content">
        <ul>
          <li><a href="/">Главная</a></li>
          <li><a href="/about">О нас</a></li>
          <li><a href="/services">Туры</a></li>
          <li><a href="/news">Новости</a></li>
          <li><a href="/contact">Контакты</a></li>
        </ul>
      </div>
      <div class="menu_social">
        <div class="menu_phone ml-auto">Тел/факс: +37517-245 67 33</div>
        <ul class="d-flex flex-row align-items-start justify-content-start">
          <li><a href="#"><i class="fa fa-pinterest" aria-hidden="true"></i></a></li>
          <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
          <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Menu"
}
</script>

<style scoped>

</style>
