<template>
  <NavBar />
  <ComputedElem />
  <list-of-elem />
  <ButtonBgColor />
  <FooterComponent />
</template>

<script>
import NavBar from './components/NavBar.vue';
import ComputedElem from './components/ComputedElem.vue';
import FooterComponent from './components/FooterComponent.vue';
import ListOfElem from './components/listOfElem.vue';
import ButtonBgColor from './components/ButtonBgColor.vue';

export default {
  components: {
    NavBar,
    ComputedElem,
    FooterComponent,
    ListOfElem,
    ButtonBgColor,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
