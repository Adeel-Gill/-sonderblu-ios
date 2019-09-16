<style scoped>
.text-center {
  text-align: center !important;
}
</style>
<template>
  <v-carousel>
    <v-carousel-item v-for="(color, i) in colors" :key="color">
      <v-sheet :color="color" height="100%" tile>
        <v-row class="fill-height" align="center" justify="center">
          <div class="display-3">Slide {{ i + 1 }}</div>
          <div class="container">
            <div class="row">
              <div class="col-xl-12">
                <div class="slider_text text-center">
                  <h3>We Design your space</h3>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit sed do eiusmod tempor</p>
                  <a href="#" class="boxed-btn2">See Our Projects</a>
                </div>
              </div>
            </div>
          </div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>
<script>
export default {
  data() {
    return {
      colors: ["primary", "secondary", "yellow darken-2", "red", "orange"]
    };
  }
};
</script>
