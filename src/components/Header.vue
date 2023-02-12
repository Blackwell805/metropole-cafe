<template>
  <div class='container'>
    <div class='twig-images'>
      <img src='src/assets/twigBerriesLeft.png' alt='left twig' class='left-twig' />
      <img src='src/assets/twigBerriesRight.png' alt='right twig' class='right-twig' />
    </div>
    <div>
      <img src="src/assets/teacup.png" alt="teacup" class='teacup'/>
      <img src="src/assets/ribbon.png" alt="ribbon" class='ribbon'/>
      <img src='src/assets/metropole.png' alt='logo' class='logo' />
    </div>
    <h1 class='title'>THE METROPOLE CAFE</h1>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.images {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.twig-images {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}
.teacup {
  position: absolute;
  z-index: 2;
}
.ribbon {
  position: absolute;
  width: 700px;
  height: 200px;
  top: 75px;
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
  position: center;
  width: 50px;
  height: 50px;
  z-index: 2;
  top: 55px;
  left: -5px;
}
.left-twig {
  position: absolute;
  top: 0;
  right: 0;
  width: 300px;
  height: 300px;
  order: 1;
}
.right-twig {
  position: absolute;
  top: 0;
  left: 0;
  width: 200px;
  height: 200px;
  order: 2;
}
</style>