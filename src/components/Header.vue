<script setup>

import ButtonPurchaseNow from './common/ButtonPurchaseNow.vue'

const logo = "src/assets/images/logo.png"
const headerApp = "src/assets/images/header-app.png"
const shape2 = "src/assets/images/header-shape-2.svg"

const HeroTitle = "You're Using Free Lite Version of AppLand "
const HeroDesc = "Please, purchase the full version of template get all pages, features, elements, documentation, commercial license and permission to remove footer credit."


</script>

<template>
  <div class="header-area">
    <div class="navbar-area">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <nav class="navbar navbar-expand-lg">
              <a class="navbar-brand" href="index.html">
                <img :src="logo" alt="Logo">
              </a>
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="toggler-icon"></span>
                <span class="toggler-icon"></span>
                <span class="toggler-icon"></span>
              </button>

              <div class="collapse navbar-collapse sub-menu-bar" id="navbarSupportedContent">
                <ul id="nav" class="navbar-nav ml-auto">
                  <li class="nav-item active">
                    <a class="page-scroll" href="#home">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#why">Why</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#features">Features</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#screenshots">Screenshots</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#pricing">Pricing</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#download">Download</a>
                  </li>
                </ul>
              </div> <!-- navbar collapse -->
            </nav> <!-- navbar -->
          </div>
        </div> <!-- row -->
      </div> <!-- container -->
    </div> <!-- navbar area -->

    <div id="home" class="header-hero bg_cover d-lg-flex align-items-center">

      <div class="shape shape-1"></div>
      <div class="shape shape-2"></div>
      <div class="shape shape-3"></div>
      <div class="shape shape-4"></div>
      <div class="shape shape-5"></div>
      <div class="shape shape-6"></div>

      <div class="container">
        <div class="row align-items-center justify-content-center justify-content-lg-between">
          <div class="col-lg-6 col-md-10">
            <div class="header-hero-content">
              <h3 class="header-title wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.2s">{{ HeroTitle }}</h3>
              <p class="text wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.6s">{{ HeroDesc }}</p>
                <li class="text-center">
                  <ButtonPurchaseNow/>
                </li>
            </div> <!-- header hero content -->
          </div>
          <div class="col-lg-4 col-md-6 col-sm-6 col-10">
            <div class="header-image">
              <img :src="headerApp" alt="app" class="image wow fadeInRightBig" data-wow-duration="1.3s"
                data-wow-delay="0.5s">
              <div class="image-shape wow fadeInRightBig" data-wow-duration="1.3s" data-wow-delay="0.8s">

              </div>
            </div> <!-- header image -->
          </div>
        </div> <!-- row -->
      </div> <!-- container -->
      <div class="header-shape-1"></div> <!-- header shape -->
      <div class="header-shape-2">
        <img :src="shape2" alt="shape">
      </div> <!-- header shape -->
    </div> <!-- header hero -->
 </div>
</template>

<style scoped></style>