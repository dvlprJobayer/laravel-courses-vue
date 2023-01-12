<template>
  <header-component />
  <RouterView />
  <FooterComponent />
</template>

<script>
import FooterComponent from "./components/FooterComponent.vue";
import HeaderComponent from "./components/HeaderComponent.vue";
export default {
  components: { HeaderComponent, FooterComponent },
  name: "App",
};
</script>
