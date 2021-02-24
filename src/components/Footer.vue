<template>
  <div class="footer mt-2">
    <div class="footer-top">
      <div class="container">
        <div class="row d-flex justify-content-around">
          <div class="col-3" style="color:white !important">
            <a href="/contact-us">
              <i style="vertical-align: middle;" class="fas fa-dot-circle"></i>
              Contact
            </a>
          </div>
          <div class="col-3" style="color:white !important">
            <a href="/terms-and-conditions">
              <i style="vertical-align: middle;" class="fas fa-dot-circle"></i>
              Terms & Conditions
            </a>
          </div>
          <div class="col-3" style="color:white !important">
            <a href="/about-us">
              <i style="vertical-align: middle;" class="fas fa-dot-circle"></i>
              About Us
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bot mt-2">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <p class="text-center">
              {{ currentYear }} Most Near All Rights Reserved ©.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    currentYear() {
      const date = new Date()
      return date.getFullYear()
    },
  },
}
</script>

<style scoped>
a {
  text-decoration: none;
  color: white;
}

.footer {
  width: 100%;
  overflow: hidden;
}
.footer-top {
  width: 100%;
  padding: 20px 0;
  overflow: hidden;
  background: #6f5bda;
  color: white;
}
.footer-top h3 {
  padding-bottom: 20px;
  line-height: 20px;
  font-size: 15px;
  text-align: left;
  text-transform: uppercase;
  color: #333333;
}
</style>
