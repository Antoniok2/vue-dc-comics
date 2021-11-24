<template>
  <div class="extra">
      <div class="icons">
          <section>
            <img src="../assets/img/buy-comics-digital-comics.png" alt="extra_icon">
            <span>DIGITAL COMICS</span>
          </section>
          <section>
            <img src="../assets/img/buy-comics-merchandise.png" alt="extra_icon">
            <span>DC MERCHANDISE</span>
          </section>
          <section>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="extra_icon">
            <span>SUBSCRIPTION</span>
          </section>
          <section>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="extra_icon">
            <span>COMIC SHOP LOCATOR</span>
          </section>
          <section>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="extra_icon">
            <span>DC POWER VISA</span>
          </section>
      </div>
      
  </div>
</template>

<script>
export default {
  name: 'Mainextra'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .extra {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #0282f9;
        height: 120px;
        width: 100%;

        .icons {
            display: flex;
            justify-content: center;

            section {
                display: flex;
                align-items: center;

                span {
                    padding-left: 10px;
                }

                img {
                    width: 20%;
                }
            }
        }
    }
</style>