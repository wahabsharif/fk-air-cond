<template>
  <footer class="footer_section section_padding">
    <div class="container">
      <div>
        <img
          src="assets/logo/fk-aircond-logo.svg"
          alt="Footer Logo"
          width="100"
        />
      </div>
      <div class="row">
        <div class="col-md-3 col-sm-6">
          <div class="footer_box">
            <p>
              FK Aircond Services, based in Malaysia, offers maintenance,
              installation, repair, and chemical services for all your air
              conditioning needs. Trusted expertise.
            </p>
          </div>
          <!--end .footer_box-->
        </div>
        <!--end .col-md-3-->
        <div class="col-md-3 col-sm-6">
          <div class="footer_box service">
            <h3>Services</h3>
            <ul>
              <li><a href="/aircond-repair">Aircond Repair</a></li>
              <li><a href="/aircond-installation">Aircond Installation</a></li>
              <li><a href="/aircond-maintenance">Aircond Maintenance</a></li>
              <li><a href="/aircond-replacement">Aircond Replacement</a></li>
            </ul>
          </div>
          <!--end .footer_box-->
        </div>
        <!--end .col-md-3-->
        <div class="col-md-3 col-sm-6">
          <div class="footer_box">
            <h3>Useful Links</h3>
            <ul>
              <li><a href="/about">About Us</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Terms and Conditions</a></li>
            </ul>
          </div>
          <!--end .footer_box-->
        </div>
        <!--end .col-md-3-->
        <div class="col-md-3 col-sm-6">
          <div class="footer_box">
            <h3>Contact Us</h3>
            <span
              ><i class="fa fa-location-arrow"></i>
              <a href="#"
                >Sunway PGS9 Bandar Sunway<br />Subang Jaya Selangor,
                Malaysia.</a
              >
            </span>
            <span class="support_email"
              ><i class="fa fa-envelope"></i>
              <a href="mailto:info@fkAircondservices.com"
                >info@fkAircondservices.com</a
              >
            </span>
            <span class="support_num"
              ><i class="fa fa-phone-square"></i>
              <a href="tel:+601164418255">+60-11-6441-8255</a></span
            >
          </div>
          <!--end .footer_box-->
        </div>
        <!--end .col-md-3-->
      </div>
      <!--end .row-->
    </div>
    <!--end .container-->

    <!-- copyright section -->
    <div class="copyright_area">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-sm-12">
            <div class="copyright_left">
              <ul class="social_media">
                <li>
                  <a
                    href="https://www.facebook.com/fkaircondservices/"
                    target="_blank"
                    ><i class="fa fa-facebook"></i
                  ></a>
                </li>
                <li>
                  <a
                    href="https://www.instagram.com/fkaircondservices/"
                    target="_blank"
                    ><i class="fa fa-instagram"></i
                  ></a>
                </li>
                <li>
                  <a
                    href="https://www.youtube.com/@FKAircondServices"
                    target="_blank"
                    ><i class="fa fa-youtube-play"></i
                  ></a>
                </li>
              </ul>
              <p>
                &copy; copyright {{ getCurrentYear() }} - FK Aircond Services.
              </p>
            </div>
            <!--end .copyright_left-->
          </div>
          <!--end .col-md-6-->
          <div class="col-md-6 col-sm-12">
            <div class="copyright_right">
              <ul class="menu">
                <li>
                  <p>Design and Developed with Passion by</p>
                  <a href="https://visionnexigen.com/" target="_blank"
                    >Vision Nexigen
                  </a>
                </li>
              </ul>
            </div>
            <!--end .copyright_right-->
          </div>
          <!--end .col-md-6-->
        </div>
        <!--end .row-->
      </div>
      <!--end .container-->
    </div>
    <!--end .copyright_area-->
  </footer>
</template>

<script>
export default {
  name: "Footer",
  methods: {
    getCurrentYear() {
      return new Date().getFullYear();
    },
  },
};
</script>

<style scoped></style>
