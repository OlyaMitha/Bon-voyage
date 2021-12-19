<template>
  <div class="destinations" id="destinations">
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <div class="section_subtitle">просто удивительные места</div>
          <div class="section_title"><h2>Популярные направления</h2></div>
        </div>
      </div>
      <div class="row destinations_row">
        <div class="col">
          <div class="destinations_container item_grid">
            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="images/destination_1.jpg" alt="">
                <div class="spec_offer text-center"><a href="#">Специальное предложение</a></div>
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Бали, Индонезия</a></div>
                <div class="destination_price">От $680</div>
              </div>
            </div>

            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="images/destination_2.jpg" alt="">
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Ява, Индонезия</a></div>
                <div class="destination_price">От $850</div>
              </div>
            </div>

            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="images/destination_3.jpg" alt="">
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Сан Франциско, США</a></div>
                <div class="destination_price">От $740</div>
              </div>
            </div>

            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="/images/destination_4.jpg" alt=""/>
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Париж, Франция</a></div>
                <div class="destination_price">От $327</div>
              </div>
            </div>

            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="images/destination_5.jpg" alt="">
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Остров Пхи-Пхи, Тайланд</a></div>
                <div class="destination_price">От $679</div>
              </div>
            </div>
            <!-- Destination -->
            <div class="destination item">
              <div class="destination_image">
                <img src="images/destination_6.jpg" alt="">
              </div>
              <div class="destination_content">
                <div class="destination_title"><a href="/Services">Миконос, Греция</a></div>
                <div class="destination_price">От $553</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Destinations"
}
</script>

<style scoped>

</style>
