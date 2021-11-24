<template>
  <div class="navigation_bar">
    <!-- logo barra di navigazione -->
    <section class="logo">
      <img src="../assets/img/dc-logo.png" alt="logo">
    </section>
    <!-- menu navigazione -->
    <section class="menu_navigazione">
      <nav>
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a class="active" href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>        
        </ul>
      </nav>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navigation_bar {
    display: flex;
    justify-content: space-around;
    width: 100%;
    height: 80px;

    .logo {
      display: flex;
      align-items: center;

      img {
      width: 70px;
      } 
    }

    .menu_navigazione {
      display: flex;
      align-items: center;
    }

    .menu_navigazione nav ul li {
      display: inline-block;
      margin: 0 10px;

      a {
        text-decoration: none;
        color: black;
        padding-bottom: 20px;

        &.active {
          color: blue;
          border-bottom: 1px solid blue;
          }
        }
      }
  }
</style>
