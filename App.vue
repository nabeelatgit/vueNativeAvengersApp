<template>
  <app-navigation></app-navigation>
</template>

<script> 
  import { StackNavigator } from "vue-native-router";
  import Home from "./components/index";
  import thanos from "./components/screens/thanos";
  import ironman from "./components/screens/ironman";
  const AppNavigation = StackNavigator(
    {
      Home: Home,
      thanos: thanos,
      ironman: ironman
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
