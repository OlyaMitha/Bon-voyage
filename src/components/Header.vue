<template>
  <header class="header">
    <div class="container">
      <div class="row">
        <div class="col">
          <div class="header_content d-flex flex-row align-items-center justify-content-start">
            <div class="header_content_inner d-flex flex-row align-items-end justify-content-start">
              <div class="logo"><a href="/">Bon voyage</a></div>
              <nav class="main_nav">
                <ul class="d-flex flex-row align-items-start justify-content-start">
                  <li class="active"><a href="/">Главная</a></li>
                  <li><a href="/about">О нас</a></li>
                  <li><a href="/services">Туры</a></li>
                  <li><a href="/news">Новости</a></li>
                  <li><a href="/contact">Контакты</a></li>
                </ul>
              </nav>
              <div class="header_phone ml-auto">Тел/факс: +37517-245 67 33</div>

              <!-- Hamburger -->

              <div class="hamburger ml-auto">
                <i class="fa fa-bars" aria-hidden="true"></i>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="header_social d-flex flex-row align-items-center justify-content-start">
      <ul class="d-flex flex-row align-items-start justify-content-start">
        <li><a href="#"><i class="fa fa-pinterest" aria-hidden="true"></i></a></li>
        <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
        <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
