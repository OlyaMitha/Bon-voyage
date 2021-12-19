<template>
  <div class="contact">
    <div class="container">
      <div class="row">

        <!-- Get in touch -->
        <div class="col-lg-6">
          <div class="contact_content">
            <div class="contact_title">Оставьте заявку</div>
            <div class="contact_text">
              <p>и мы свяжемся с вами в ближайщее время</p>
            </div>
            <div class="contact_list">
              <ul>
                <li>
                  <div>адрес:</div>
                  <div>г. Минск, пр-т Победителей, 54 офис 18</div>
                </li>
                <li>
                  <div>телефон</div>
                  <div>+37517-245 67 33</div>
                </li>
                <li>
                  <div>email:</div>
                  <div>bonvoyage@gmail.com</div>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <!-- Contact Form -->
        <div class="col-lg-6">
          <div class="contact_form_container">
            <form action="#" id="contact_form" class="contact_form">
              <div style="margin-bottom: 18px"><input type="text" class="contact_input contact_input_name inpt" placeholder="Ф.И.О." required="required"><div class="input_border"></div></div>
              <div class="row">
                <div class="col-lg-6" style="margin-bottom: 18px">
                  <div><input type="text" class="contact_input contact_input_email inpt" placeholder="E-mail" required="required"><div class="input_border"></div></div>
                </div>
                <div class="col-lg-6" style="margin-bottom: 18px">
                  <div><input type="text" class="contact_input contact_input_subject inpt" placeholder="Предмет" required="required"><div class="input_border"></div></div>
                </div>
              </div>
              <div><textarea class="contact_textarea contact_input inpt" placeholder="Сообщение" required="required"></textarea><div class="input_border" style="bottom:3px"></div></div>
              <button class="contact_button">Отправить</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Map -->

  <div class="contact_map">
    <!-- Google Map -->
    <div class="map">
      <div class="map_container">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2903.9764760692206!2d27.52730677835242!3d53.91937491627182!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46dbc56231f5683d%3A0x3cff0b851f00606!2z0L_RgC3Rgi4g0J_QvtCx0LXQtNC40YLQtdC70LXQuSA1NCwg0JzQuNC90YHQug!5e0!3m2!1sru!2sby!4v1639931835950!5m2!1sru!2sby" width="1000" height="700" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
       </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactCompany"
}
</script>

<style scoped>

</style>
