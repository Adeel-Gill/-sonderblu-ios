<style>
img {
    vertical-align: middle;
    border-style: none;
    
}

*, ::after, ::before {
    box-sizing: border-box;
}

.about_area .about_thumb {
    position: relative;
    z-index: 2;
}

.about_area .about_thumb .exprience {
    position: absolute;
    top: 50%;
    -webkit-transform: translate(-50%,-50%);
    -ms-transform: translate(-50%,-50%);
    transform: translate(-50%,-50%);
    display: inline-block;
    padding: 40px 45px;
    background: #fff;
    text-align: center;
    left: 50%;
}
.align-items-center {
    -webkit-box-align: center!important;
    -ms-flex-align: center!important;
    align-items: center!important;
}

.row {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}
.container {
    max-width: 1140px;
}
::selection {
    background: #444;
    color: #fff;
    text-shadow: none;
}

.col-xl-6 {
    -webkit-box-flex: 0;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
    max-width: 50%;
}
.col-md-6 {
    -webkit-box-flex: 0;
    -ms-flex: 0 0 50%;
    flex: 0 0 50%;
    max-width: 50%;
}
.col, .col-1, .col-10, .col-11, .col-12, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-auto, .col-lg, .col-lg-1, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-auto, .col-md, .col-md-1, .col-md-10, .col-md-11, .col-md-12, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-auto, .col-sm, .col-sm-1, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-auto, .col-xl, .col-xl-1, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-auto {
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}
*, ::after, ::before {
    box-sizing: border-box;
}
user agent stylesheet
div {
    display: block;
}
.container {
    flex: 1 1 100%;
    margin: auto;
    padding: 24px;
    width: 100%;
}
</style>
<template>
 <v-container style="margin-bottom:50px">
      <v-layout row>
        <v-flex md6>
          <v-card dark tile flat color="error">
           <div class="about_thumb">
<img src="https://colorlib.com/preview/theme/ararat/img/about/1.png" alt="">
<div class="exprience">
<h1>25</h1>
<span>Years of Experience</span>
</div>
</div>
          </v-card>
        </v-flex>
        <v-flex md6>
          <v-card dark tile flat color="pink darken-4">
           <div class="col-xl-5 offset-xl-1 col-md-6">
<div class="about_info">
<div class="section_title">
<span class="sub_heading">About Us</span>
<h3>Architechtural plan <br>
design and build</h3>
<div class="seperator"></div>
</div>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo
viverra maecenas accumsan lacus vel facilisis. </p>
<ul class="about_list">
<li>Consectetur adipiscing sed do eiusmod. </li>
<li>Eiusmod tempor incididunt labore. </li>
</ul>
<a href="#" class="boxed-btn">ABOUT US</a>
</div>
</div>
          </v-card>
        </v-flex>
      </v-layout> 
    </v-container>
</templete>