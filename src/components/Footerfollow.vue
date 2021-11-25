<template>
  <div class="footer_access_follow">
      <section class="sign_up">
          <button>SIGN-UP NOW!</button>
      </section>
      <section class="follow_us">
          <h2>FOLLOW US</h2>
          <div class="social">
              <img src="../assets/img/footer-facebook.png" alt="logo">
              <img src="../assets/img/footer-twitter.png" alt="logo">
              <img src="../assets/img/footer-youtube.png" alt="logo">
              <img src="../assets/img/footer-pinterest.png" alt="logo">
              <img src="../assets/img/footer-periscope.png" alt="logo">
          </div>
      </section>
  </div>
</template>

<script>
export default {
  name: 'Footerfollow'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .footer_access_follow {
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 100%;
        height: 80px;
        background-color: #303030;

        .sign_up> button {
            border: 1px solid #0282f9;
            padding: 10px;
            color: white;
            background-color: #303030;
        }

        .follow_us {
            display: flex;
            align-items: center;

            h2 {
                color: #047ff8;
                font-size: 20px;
                margin: 10px;
            }

            .social> img {
                margin: 0 10px;
            }
        }
    }
</style>
