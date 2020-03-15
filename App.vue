<template>
  <app-navigation></app-navigation>
</template>

<script> 
  import { StackNavigator } from "vue-native-router";
  import Home from "./components/index";
  import ironman from "./components/screens/ironman";
  import steve from "./components/screens/steve";
  import thor from "./components/screens/thor";
  import hulk from "./components/screens/bruce";
  import natasha from "./components/screens/natasha";
  import clint from "./components/screens/clint";
  import panther from "./components/screens/panther";
  import strange from "./components/screens/strange";
  import vision from "./components/screens/vision";
  import witch from "./components/screens/witch";
  import antman from "./components/screens/antman";
  import marvel from "./components/screens/marvel";
  import spider from "./components/screens/spider";
  const AppNavigation = StackNavigator(
    {
      Home: Home,
      ironman: ironman,
      steve: steve,
      thor: thor,
      hulk: hulk,
      natasha: natasha,
      clint: clint,
      panther: panther,
      strange: strange,
      vision: vision,
      witch: witch,
      antman: antman,
      marvel:marvel,
      spider: spider
    },
    {
      initialRouteName: 'Home',
    }
  );
  export default {
    components: { AppNavigation }
  };
</script>
 
<style>
</style>
