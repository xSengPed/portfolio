<template>
  <div>
    <HomePage />
  </div>
</template>

<script>
import HomePage from "./pages/HomePage.vue";
export default {
  name: "App",
  components: {
    HomePage,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Nunito:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,600;1,700;1,800;1,900&display=swap');
* {
  font-family: 'Nunito', sans-serif;
  padding: 0;
  margin: 0;
  letter-spacing: 1.35px;
}
</style>
