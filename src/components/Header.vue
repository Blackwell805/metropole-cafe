<template>
    <h1 class='title'>THE METROPOLE CAFE</h1>
    <div class='center-images'>
      <img src="src/assets/teacup.png" alt="teacup" class='teacup'/>
      <img src="src/assets/ribbon.png" alt="ribbon" class='ribbon'/>
      <img src='src/assets/metropole.png' alt='logo' class='logo' />
    </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.center-images {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.teacup {
  position: absolute;
  top: 95px;
  width: 450px;
  z-index: 2;
}
.ribbon {
  position: absolute;
  width: 1250px;
  height: 200px;
  top: 300px;
  z-index: 1;
}
.title {
  position: center;
  top: 122px;
  z-index: 2;
  color: white;
  font-family: "Indie Flower", serif;
}
.logo {
  position: relative;
  width: 150px;
  height: 125px;
  z-index: 2;
  top: 134px;
  left: -4px;
}
</style>