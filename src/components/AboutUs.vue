<script setup>
import ButtonFullVersion from './common/ButtonFullVersion.vue';


const section = {
  title: "About Our Lite Version",
  desc: "Please, purchase the full version of template get all pages, features, elements, documentation, commercial license and permission to remove footer credit."
}



</script>

<template>
        <section id="about" class="about-area pt-70 pb-120">
          <div class="container">
            <div class="row align-items-center">
              <div class="col-lg-6">
                <div class="about-image mt-50 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                  <div class="about-shape"></div>
                  <img class="app" src="src/assets/images/about-app.png" alt="app">
                </div> <!-- about image -->
              </div>
              <div class="col-lg-6">
                <div class="about-content mt-50 wow fadeInRightBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
                  <div class="section-title">
                    <h3 class="title">You're Using Free Lite Version</h3>
                    <p class="text">Please, purchase the full version of template get all pages, features, elements,
                      documentation, commercial license and permission to remove footer credit.</p>
                  </div> <!-- section title -->
                  <ButtonFullVersion/>
                </div> <!-- about content -->
              </div>
            </div> <!-- row -->
          </div> <!-- container -->
        </section>

</template>

<style scoped></style>
