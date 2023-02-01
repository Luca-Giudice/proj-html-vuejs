<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'Ava & Associates',
  components: { AppHeader, AppMain }
}
</script>

<template>
<app-header></app-header>
<app-main></app-main>

</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  min-height: 100vh;
}

img{
max-width: 100%;
height: auto;

}

a{
  text-decoration: none;
}

.container{
  margin: 0 auto;
  max-width: 1140px;
}
</style>