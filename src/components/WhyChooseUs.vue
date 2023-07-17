<script setup>

const section = {
  title: "Why You Should Choose AppLand",
  desc: "Alii nusquam cu duo, vim eu consulatu percipitur, meis dolor comprehensam at vis. Vel ut percipitur dignissim signiferumque."
}

const feature = [
  {
    title: "Clean Design",
    desc: "Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy."
  },
  {
    title: "Easy to Use",
    desc: "Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy."
  },
  {
    title: "Fast Loading",
    desc: "Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy."
  },
  {
    title: "All Elements",
    desc: "Lorem ipsum dolor sitam etco snsetetur sadipscing elitr sed diam nonumy."
  }
]

</script>

<template>
    <section id="why" class="services-area pt-110 pb-120">
              <div class="container">
                <div class="row justify-content-center">
                  <div class="col-lg-7">
                    <div class="section-title text-center pb-25">
                      <h3 class="title">{{ section.title }}</h3>
                      <p class="text">{{ section.desc }}</p>
                    </div> <!-- section title -->
                  </div>
                </div> <!-- row -->
                <div class="row">
                  <div class="col-lg-3 col-sm-6">

                    <div class="single-services services-color-1 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s"
                      data-wow-delay="0.2s">
                      <div class="services-icon d-flex align-items-center justify-content-center">
                        <i class="lni lni-layers"></i>
                      </div>
                      <div class="services-content">
                        <h4 class="services-title"><a href="#">{{ feature[0].title }}</a></h4>
                        <p class="text">{{ feature[0].desc }}</p>
                      </div>
                    </div> <!-- single services -->

                  </div>

                  <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-2 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s"
                      data-wow-delay="0.4s">
                      <div class="services-icon d-flex align-items-center justify-content-center">
                        <i class="lni lni-layout"></i>
                      </div>
                      <div class="services-content">
                        <h4 class="services-title"><a href="#">{{ feature[1].title }}</a></h4>
                        <p class="text">{{ feature[1].desc }}</p>
                      </div>
                    </div> <!-- single services -->
                  </div>
                  <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-3 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s"
                      data-wow-delay="0.6s">
                      <div class="services-icon d-flex align-items-center justify-content-center">
                        <i class="lni lni-bolt"></i>
                      </div>
                      <div class="services-content">
                        <h4 class="services-title"><a href="#">{{ feature[2].title }}</a></h4>
                        <p class="text">{{ feature[2].desc }}</p>
                      </div>
                    </div> <!-- single services -->
                  </div>
                  <div class="col-lg-3 col-sm-6">
                    <div class="single-services services-color-4 text-center mt-30 wow fadeInUpBig" data-wow-duration="1.3s"
                      data-wow-delay="0.8s">
                      <div class="services-icon d-flex align-items-center justify-content-center">
                        <i class="lni lni-protection"></i>
                      </div>
                      <div class="services-content">
                        <h4 class="services-title"><a href="#">{{ feature[3].title }}</a></h4>
                        <p class="text">{{ feature[3].desc }}</p>
                      </div>
                    </div> <!-- single services -->
                  </div>
                </div> <!-- row -->
              </div> <!-- container -->
            </section>
</template>

<style scoped></style>
