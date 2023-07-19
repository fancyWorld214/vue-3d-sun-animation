<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/sideview">SideView</router-link> |
    <router-link to="/verticalview">VerticalView</router-link>
  </nav> -->
  <NavbarComponent class="navbar-component"/>
  <router-view class="router-view-container"/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  //color: #2c3e50;
}

#app {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  //background-color: #f0f0f0;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}


/* Styling for the NavbarComponent, adjust the styles as needed */
/* You can use a fixed position to make it float on top */
/* e.g., position: fixed; top: 0; left: 0; width: 100%; */
/* Or use any other positioning based on your design */
/* For simplicity, I'll use relative positioning in this example */
.navbar-component {
  position: relative;
  //background-color: #f0f0f0;
  padding: 10px;
}

/* Styling for the router-view container, adjust the styles as needed */
/* You may add padding, margins, or other styles to create spacing */
</style>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import NavbarComponent from '@/components/NavBar.vue';

@Options({
  components: {
    NavbarComponent,
  },
})
export default class App extends Vue {}

</script>