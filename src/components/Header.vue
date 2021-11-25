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
          <li v-for="link, i in links" :key="i">
            <a :class="link.select ? 'active' : ''" :href="link.url">{{link.text}}</a>
          </li>
        </ul>
      </nav>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      links: [
        {
          text: 'CHARACTERS',
          url: '#',
          select: true
        },
        {
          text: 'COMICS',
          url: '#',
          select: false
        },
        {
          text: 'MOVIES',
          url: '#',
          select: false
        },
        {
          text: 'TV',
          url: '#',
          select: false
        },
        {
          text: 'GAMES',
          url: '#',
          select: false
        },
        {
          text: 'COLLECTIBLES',
          url: '#',
          select: false
        },
        {
          text: 'VIDEOS',
          url: '#',
          select: false
        },
        {
          text: 'FANS',
          url: '#',
          select: false
        },
        {
          text: 'NEWS',
          url: '#',
          select: false
        },
        {
          text: 'SHOP',
          url: '#',
          select: false
        }
      ]
    }
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

          &:hover {
            color: blue;
            border-bottom: 1px solid blue;
          }
        }
      }
  }
</style>
