<script setup>

const section = {
  title: "Download and Start Using!",
  desc: "Alii nusquam cu duo, vim eu consulatu percipitur, meis doorcomprehen sam at vis. Vel utdignissim signiferumq Alii nusquam cuduo, vim eusde consulatu percipitur, meis dolor comprehensam at vij.Alii nusquam cu duo, vim eu consulatu percipitur, meis doorcomprehen sam at vis.Vel ut dignissim signiferumq nusquam."
}

const downloadImages = {
  appStore: 'src/assets/images/app-store.png',
  appStoreLink: "#",
  googlePlay: 'src/assets/images/play-store.png',
  googlePlayLink: '#'
}

</script>

<template>
  <section id="download" class="download-area pt-70 pb-40">
    <div class="container">
      <div class="row justify-content-center align-items-center">
        <div class="col-lg-6 col-md-9">
          <div class="download-image mt-50 wow fadeInRightBig" data-wow-duration="1.3s" data-wow-delay="0.2s">
            <img class="image" src="src/assets/images/download-app.png" alt="download">

            <div class="download-shape-1"></div>
            <div class="download-shape-2">
              <img class="svg" src="src/assets/images/download-shape.svg" alt="shape">
            </div>
          </div> <!-- download image -->
        </div>
        <div class="col-lg-6">
          <div class="download-content mt-45 wow fadeInLeftBig" data-wow-duration="1.3s" data-wow-delay="0.5s">
            <h3 class="download-title">{{ section.title }}</h3>
            <p class="text">{{ section.desc }}</p>
            <ul>
              <li><a class="app-store" :href="appStoreLink"><img :src="downloadImages.appStore" alt="store"></a></li>
              <li><a class="play-store" :href="googlePlayLink"><img :src="downloadImages.googlePlay" alt="store"></a></li>
            </ul>
          </div> <!-- download image -->
        </div>
      </div> <!-- row -->
    </div> <!-- container -->
  </section>
</template>

<style scoped></style>
