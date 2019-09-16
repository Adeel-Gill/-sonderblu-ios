<template>
  <v-app>
    <!-- <v-toolbar fixed app :clipped-left="clipped" dark>
      <img class="mr-3" :src="require('../assets/hdr-logo.png')" height="40" />
      <v-toolbar-items v-for="(title,i) in titles" :key="i">
        <v-btn text>{{title}}</v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
    </v-toolbar> -->


    <v-content>
        <nuxt />
    </v-content>

    <!-- <v-footer dark >
      <v-card >
        <v-card-text>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4 white--text">
            <v-icon size="24px" >{{ icon }}</v-icon>
          </v-btn>
        </v-card-text>

        <v-card-text
          class="white--text pt-0"
        >Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</v-card-text>

        <v-divider></v-divider>

        <v-card-text class="white--text">
          {{ new Date().getFullYear() }} —
          <strong>Vuetify</strong>
        </v-card-text>
      </v-card>
    </v-footer> -->
  </v-app>
</template>

<script>

export default {
  data() {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [
        { icon: "apps", title: "Welcome", to: "/" },
        { icon: "bubble_chart", title: "Inspire", to: "/inspire" }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      titles: [
        "HOME",
        "ABOUT",
        "PROJECTS",
        "SERVICES",
        "BLOG",
        "PAGES",
        "CONTACT"
      ],
      icons: [
        "fab fa-facebook",
        "fab fa-twitter",
        "fab fa-google-plus",
        "fab fa-linkedin",
        "fab fa-instagram"
      ]
    };
  }
};
</script>
 

<style>

body {
    background-color: #FAFAFA;
    font-family: "Roboto", sans-serif !important;
}

nav {
    width: 100%;
    background-color: #37474F;
    height: 50px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    padding: 30px;
}

nav img.logo {
    width: 130px;
}

nav span.login {
    color: white;
}

div#carousel-example-2 {
    top: 0px;
}

div#carousel-example-2 ol {
    top: 90%;
}

div#carousel-example-2 ol li {
    width: 10px;
    height: 10px;
    background-color: #546E7A;
    border-radius: 50%;
}

div#carousel-example-2 div.carousel-inner {
    background-color: rgba(255, 255, 255, .8);
    width: 100%;
    box-shadow: 0 0 3px rgba(0, 0, 0, .1);
    border-radius: 10px;
    min-height: 332px;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view {
    padding: 10px 0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.ImgGroup {
    width: 50%;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 120px;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.ImgGroup img.small {
    position: absolute;
    bottom: 0px;
    width: 70px;
    left: 50px;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.ImgGroup div.ImgContainer {
    width: 100px;
    box-shadow: 0 0px 6px rgba(0, 0, 0, 0.2);
    background-color: white;
    height: 100px;
    border-radius: 50%;
    padding: 5px;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.ImgGroup div.ImgContainer img {
    width: 100%;
    height: 100%;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.Captions {
    padding: 30px 0;
    width: 90%;
    align-items: center;
    color: #546E7A;
    justify-content: center;
    flex-direction: column;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.Captions h5 {
    margin: 0;
    font-style: italic;
    font-weight: 600;
}

div#carousel-example-2 div.carousel-inner div.carousel-item div.view div.Captions p {
    margin-top: 20px;
    text-align: center;
}

div#home {
    width: 100%;
    background-image: url("../assets/bg.png");
    background-size: cover;
    background-position: center;
}

div#home div.row {
    min-height: 750px;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

div#home div.row div.slider h1 {
    color: white;
    text-shadow: 0 3px 6px rgba(0, 0, 0, .2);
    margin-bottom: 20px;
}

h1.heading {
    color: white;
    text-shadow: 0 3px 6px rgba(0, 0, 0, .2);
    margin: 20px 0 20px 0;
    padding: 0 20px;
    text-align: center;
}

div#home div.row div.form {
    display: flex;
    align-items: center;
    justify-content: center;
}

div#home div.row div.form form {
    overflow: hidden;
    box-shadow: 0 3px 6px rgba(0, 0, 0, .2);
    width: 80%;
    background-color: rgba(255, 255, 255, .8);
    border-radius: 5px;
    color: #546E7A;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
}

div#home div.row div.form form h5 {
    text-align: center;
    margin: 20px 0 0px 0px;
}

div#home div.row div.form form span {
    font-size: 13px;
    margin: 10px 0;
    padding: 0 20px;
}

div#home div.row div.form form button {
    margin: 10px 0;
    text-transform: uppercase;
    font-size: 14px;
    border: none;
    background-color: white;
    color: #546E7A;
    padding: 7px 10px;
    box-shadow: 0 3px 6px rgba(0, 0, 0, .2);
    border-radius: 3px;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 80%;
    outline: none;
}

div#home div.row div.form form button i {
    font-size: 16px;
    margin: 0 10px 0 0px
}

div#home div.row div.form form input {
    width: 80%;
    margin-top: 20px;
    border: none;
    background-color: transparent;
    font-size: 12px;
    padding: 5px 0;
    border-bottom: 2px solid #546E7A;
}

div#home div.row div.form form input:not(:nth-of-type(1)) {
    margin-top: 30px;
}

div#home div.row div.form form footer {
    margin-top: 40px;
    width: 100%;
    background-color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

div#home div.row div.form form footer span.footer {
    font-size: 10px;
    text-align: center;
}

div#home div.row div.form form footer button.submit {
    background-color: #2196F3;
    color: white;
}

div#Body div.row {
    padding: 15px;
    margin-top: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

div#Body div.row div.content {
    border-radius: 4px;
    box-shadow: 0 3px 6px rgba(0, 0, 0, .4);
    overflow: hidden;
    padding: 0;
}

div#Body div.row div.content div.Cover {
    position: relative;
    width: 100%;
    height: 160px;
}

div#Body div.row div.content div.Cover img {
    width: 100%;
    height: 100%;
}

div#Body div.row div.content div.Cover p {
    position: absolute;
    top: 80%;
    color: white;
    margin: 0;
    padding: 0;
    font-size: 19px;
    font-weight: 600;
    left: 10px;
}

div#Body div.row div.content div.Content {
    background-color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    flex-direction: column;
    width: 100%;
}

div#Body div.row div.content div.Content div.Brand {
    display: flex;
    align-items: center;
    width: 100%;
    justify-content: flex-start;
}

div#Body div.row div.content div.Content span {
    font-size: 14px;
    color: #2196F3;
    text-transform: uppercase;
    font-weight: 500;
    margin-top: 10px;
}
div#Body div.row div.content div.Content div.Brand div.logo {
    width: 90px;
    height: 90px;
    box-shadow: 0 3px 6px rgba(0, 0, 0, .4);
    border-radius: 50%;
    overflow: hidden;
}

div#Body div.row div.content div.Content div.Brand div.logo img {
    width: 100%;
    height: 100%;
}
div#Body div.row div.content div.Content div.Brand div.text{
    display: flex;
    align-items: flex-start;
    justify-content: center;
    flex-direction: column;
}
div#Body div.row div.content div.Content div.Brand div.text p{
    margin: 0 0 0 20px;
    color: #546E7A;
    font-size: 14px;
}
div#Body div.row div.btns {
    padding: 0;
    box-shadow: 0 0px 6px rgba(0, 0, 0, .20);
    border-radius: 5px;
    overflow: hidden;
}

div#Body div.row div.btns button {
    width: 100%;
    padding: 10px 0;
    text-transform: uppercase;
    color: #546E7A;
    border: none;
    background-color: #F5F5F5;
}

div#feature div.row {
    padding-bottom: 20px;
}

div#feature div.row div.col-md-4 div.content {
    padding: 10px 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    box-shadow: 0 0px 6px rgba(0, 0, 0, .20);
    border-radius: 3px;
    background-color: white;
}

div#feature div.row div.col-md-4 div.content span {
    margin-top: 10px;
    font-size: 20px;
    color: #546E7A;
    align-self: flex-start;
}

div#feature div.row div.col-md-4 div.content p {
    margin-top: 10px;
    font-size: 12px;
    color: #546E7A;
    margin-bottom: 0;
    align-self: flex-start;
}

footer.container-fluid {
    background-color: #455A64;
}

footer.container-fluid div.row {
    display: flex;
    align-items: flex-start;
    justify-content: center;
}

footer.container-fluid div.row div.col-md-3 {
    display: flex;
    align-items: flex-start;
    justify-content: center;
    flex-direction: column;
    padding-bottom: 20px;
}

footer.container-fluid div.row div.col-md-3 span {
    color: white;
    font-weight: 500;
    font-size: 14px;
    margin: 20px 0 20px 0;
}

footer.container-fluid div.row div.col-md-3 img {
    width: 30px;
    height: 32px;
}

footer.container-fluid div.row div.col-md-3 p {
    margin: 05px 0;
    font-size: 12px;
    letter-spacing: .5px;
    color: white;
    font-weight: lighter;
}

footer.end {
    width: 100%;
    height: 40px;
    background-color: #37474F;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 20px;
}

footer.end span {
    color: white;
    font-size: 12px;
}

/* here is new style */

@media (max-width:768px) {
    div#home div.row div.form {
        padding: 0 !important;
    }

    div#home div.row div.form form {
        width: 100% !important;
        border-radius: 0 !important;
    }

    div#home div.slider {
        padding: 0;
    }

    div#home div.slider div.carousel-inner {
        background-color: white;
        border-radius: 0;
    }

    div#Body div.row div.content div.Content div.Brand div.text {
        width: 100% !important;
    }

    div#Body div.row div.content div.Content div.Brand div.text p {
        margin: 0 !important;

    }
    div#Body div.row div.content div.Content div.Brand div.text span{
        color: #546E7A;
        margin: 10px 0;
    }
    div#Body div.row div.content div.Content div.Brand {
        flex-direction: column;
    }

    div#Body div.row div.content div.Content div.Brand div.logo {
        height: auto !important;
        width: 100% !important;
        display: flex;
        align-items: center;
        justify-content: center;
        box-shadow: none !important;
        border-radius: 0 !important;
    }

    div#Body div.row div.content div.Content div.Brand div.logo img {
        width: 70% !important;
    }
}
</style>