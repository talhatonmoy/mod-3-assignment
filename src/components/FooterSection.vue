<script setup>
const section = {
  logo: "src/assets/images/logo.png",
  desc: "Lorem ipsum dolor sit amet consetetur sadipscing elitr, sederfs diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam."
}


const socialLinks = {
  facebook: "#",
  twitter: "#",
  instagram: "#",
  linkedin: "#"
}
 
</script>

<template>
        <footer id="footer" class="footer-area">

          <div class="footer-shape shape-1"></div>
          <div class="footer-shape shape-2"></div>
          <div class="footer-shape shape-3"></div>
          <div class="footer-shape shape-4"></div>
          <div class="footer-shape shape-5"></div>
          <div class="footer-shape shape-6"></div>
          <div class="footer-shape shape-7"></div>
          
          <div class="footer-shape shape-8">
            <img class="svg" src="src/assets/images/footer-shape.svg" alt="Shape">
          </div>

          <div class="footer-widget pt-30 pb-80">
            <div class="container">
              <div class="row">
                <div class="col-lg-4 col-md-6">
                  <div class="footer-about mt-50 wow fadeIn" data-wow-duration="1.3s" data-wow-delay="0.2s">
                    <a class="logo" href="#">
                      <img :src="section.logo" alt="Logo">
                    </a>
                    <p class="text">{{ section.desc }}</p>
                    <ul class="social">
                      <li><a :href="socialLinks.facebook"><i class="lni lni-facebook"></i></a></li>
                      <li><a :href="socialLinks.twitter"><i class="lni lni-twitter"></i></a></li>
                      <li><a :href="socialLinks.instagram"><i class="lni lni-instagram"></i></a></li>
                      <li><a :href="socialLinks.linkedin"><i class="lni lni-linkedin"></i></a></li>
                    </ul>
                  </div> <!-- footer about -->
                </div>
                <div class="col-lg-5 col-md-6">
                  <div class="footer-link d-flex flex-wrap">
                    <div class="footer-link-wrapper mt-45 wow fadeIn" data-wow-duration="1.3s" data-wow-delay="0.4s">
                      <div class="footer-title">
                        <h4 class="title">Quick Links</h4>
                      </div>
                      <ul class="link">
                        <li><a class="" href="#">Home</a></li>
                        <li><a class="" href="#">Features</a></li>
                        <li><a class="" href="#">Testimonial</a></li>
                        <li><a class="" href="#">Pricing</a></li>
                        <li><a class="" href="#">Contact</a></li>
                      </ul>
                    </div> <!-- footer link wrapper -->

                    <div class="footer-link-wrapper mt-45 wow fadeIn" data-wow-duration="1.3s" data-wow-delay="0.6s">
                      <div class="footer-title">
                        <h4 class="title">Support</h4>
                      </div>
                      <ul class="link">
                        <li><a class="" href="#">FAQ</a></li>
                        <li><a class="" href="#">Privacy Policy</a></li>
                        <li><a class="" href="#">Terms Of Use</a></li>
                        <li><a class="" href="#">Legal</a></li>
                        <li><a class="" href="#">Site Map</a></li>
                      </ul>
                    </div> <!-- footer link wrapper -->
                  </div> <!-- footer link -->
                </div>
                <div class="col-lg-3 col-md-6">
                  <div class="footer-contact mt-45 wow fadeIn" data-wow-duration="1.3s" data-wow-delay="0.8s">
                    <div class="footer-title">
                      <h4 class="title">Quick Link</h4>
                    </div>
                    <ul class="contact-list">
                      <li>
                        <div class="contact-info d-flex">
                          <div class="info-content media-body">
                            <p class="text"><i class="lni lni-phone"></i> +809272561823</p>
                          </div>
                        </div> <!-- contact info -->
                      </li>
                      <li>
                        <div class="contact-info d-flex">
                          <div class="info-content media-body">
                            <p class="text"><a href="#"><i class="lni lni-envelope"></i> info@appland.com</a></p>
                          </div>
                        </div> <!-- contact info -->
                      </li>
                      <li>
                        <div class="contact-info d-flex">
                          <div class="info-content media-body">
                            <p class="text"><a href="#"><i class="lni lni-world"></i> www.yourweb.com</a></p>
                          </div>
                        </div> <!-- contact info -->
                      </li>
                      <li>
                        <div class="contact-info d-flex">
                          <div class="info-content media-body">
                            <p class="text"><i class="lni lni-map"></i> 123 Stree New York City , United States Of America
                              750.</p>
                          </div>
                        </div> <!-- contact info -->
                      </li>
                    </ul> <!-- contact list -->
                  </div> <!-- footer contact -->
                </div>
              </div> <!-- row -->
            </div> <!-- container -->
          </div> <!-- footer widget -->

          <div class="footer-copyright">
            <div class="container">
              <div class="row">
                <div class="col-lg-12">
                  <div class="copyright d-sm-flex justify-content-between">
                    <div class="copyright-text text-center">
                      <p class="text">Template Crafted by <a rel="nofollow" href="https://uideck.com">UIdeck</a></p>
                    </div> <!-- copyright text -->

                    <div class="copyright-privacy text-center">
                      <a href="#">Report Issues</a>
                    </div> <!-- copyright privacy -->
                  </div> <!-- copyright -->
                </div>
              </div> <!-- row -->
            </div> <!-- container -->
          </div> <!-- footer copyright -->
        </footer>
</template>

<style scoped></style>
