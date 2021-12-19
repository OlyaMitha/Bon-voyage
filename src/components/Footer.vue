<template>
  <footer class="footer">
  <div class="parallax_background parallax-window" data-parallax="scroll" data-image-src="images/footer_1.jpg" data-speed="0.8"></div>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="newsletter">
          <div class="newsletter_title_container text-center">
            <div class="newsletter_title">Подпишитель на нашу рассылку, чтобы быть в курсе последних тенденций и новостей</div>
            <div class="newsletter_subtitle">Присоединяйтесь к нам сейчас</div>
          </div>
          <div class="newsletter_form_container">
            <form action="#" class="newsletter_form d-flex flex-md-row flex-column align-items-start justify-content-between" id="newsletter_form">
              <div class="d-flex flex-md-row flex-column align-items-start justify-content-between">
                <div><input type="text" class="newsletter_input newsletter_input_name" id="newsletter_input_name" placeholder="Имя" required="required"><div class="input_border"></div></div>
                <div><input type="email" class="newsletter_input newsletter_input_email" id="newsletter_input_email" placeholder="Ваш e-mail" required="required"><div class="input_border"></div></div>
              </div>
              <div><button class="newsletter_button">Подписаться</button></div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="row footer_contact_row">
      <div class="col-xl-10 offset-xl-1">
        <div class="row">

          <!-- Footer Contact Item -->
          <div class="col-xl-4 footer_contact_col">
            <div class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
              <div class="footer_contact_icon"><img src="images/sign.svg" alt=""></div>
              <div class="footer_contact_title">позвоните нам</div>
              <div class="footer_contact_list">
                <ul>
                  <li>Тел/факс: +37517-245 67 33</li>
                  <li>MTC: +37533 567 89 45</li>
                  <li>A1: +37529 567 89 45</li>
                  <li>Life: +37544 567 89 45</li>
                </ul>
              </div>
            </div>
          </div>

          <!-- Footer Contact Item -->
          <div class="col-xl-4 footer_contact_col">
            <div class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
              <div class="footer_contact_icon"><img src="images/trekking.svg" alt=""></div>
              <div class="footer_contact_title">Заходите к нам</div>
              <div class="footer_contact_list">
                <ul style="max-width:190px">
                  <li>г. Минск, пр-т Победителей, 54 офис 18 </li>
                </ul>
              </div>
            </div>
          </div>

          <!-- Footer Contact Item -->
          <div class="col-xl-4 footer_contact_col">
            <div class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
              <div class="footer_contact_icon"><img src="images/around.svg" alt=""></div>
              <div class="footer_contact_title">Отправьте нам сообщение</div>
              <div class="footer_contact_list">
                <ul>
                  <li>bonvoyage@gmail.com</li>
                  <li>Office@voyagename.com</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </footer>
  </template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

</style>