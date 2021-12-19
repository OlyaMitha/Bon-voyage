<template>
  <div class="home">

    <!-- Home Slider -->
    <div class="home_slider_container">
      <div class="owl-carousel owl-theme home_slider">

        <!-- Slide -->
        <div class="owl-item">
          <div class="background_image" style="background-image:url(images/home_slider.jpg)"></div>
          <div class="home_slider_content_container">
            <div class="container">
              <div class="row">
                <div class="col">
                  <div class="home_slider_content">
                    <div class="home_title"><h2>Будь там где твое сердце</h2></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Slide -->
        <div class="owl-item">
          <div class="background_image" style="background-image:url(images/home_slider.jpg)"></div>
          <div class="home_slider_content_container">
            <div class="container">
              <div class="row">
                <div class="col">
                  <div class="home_slider_content">
                    <div class="home_title"><h2>Ваш отдых начинается с визита к нам</h2></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Slide -->
        <div class="owl-item">
          <div class="background_image" style="background-image:url(images/home_slider.jpg)"></div>
          <div class="home_slider_content_container">
            <div class="container">
              <div class="row">
                <div class="col">
                  <div class="home_slider_content">
                    <div class="home_title"><h2>Мир начинается здесь...</h2></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Search -->

  <div class="home_search">
    <div class="container">
      <div class="row">
        <div class="col">
          <div class="home_search_container">
            <div class="home_search_title">Найдите свою поездку</div>
            <div class="home_search_content">
              <form action="#" class="home_search_form" id="home_search_form">
                <div class="d-flex flex-lg-row flex-column align-items-start justify-content-lg-between justify-content-start">
                  <input type="text" class="search_input search_input_1" placeholder="Город" required="required">
                  <input type="text" class="search_input search_input_2" placeholder="Выезд" required="required">
                  <input type="text" class="search_input search_input_3" placeholder="Прибытие" required="required">
                  <input type="text" class="search_input search_input_4" placeholder="Бюджет" required="required">
                  <button class="home_search_button">Поиск</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>

</style>
