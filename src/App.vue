<script>

import {defineComponent} from "vue";
import Header from "@/components/Header.vue";
import CoffeeList from "@/components/CoffeeList.vue";

export default defineComponent({
  components: {CoffeeList, Header}
})
</script>

<template>
  <div class='App-container'>
    <img src='src/assets/twigBerriesLeft.png' alt='left twig' class='left-twig' />
    <img src='src/assets/twigBerriesRight.png' alt='right twig' class='right-twig' />
    <header>
      <Header/>
    </header>
    <main>
      <body>
        <section>
          <CoffeeList />
        </section>
      </body>
    </main>
    <footer>
      footer
    </footer>
  </div>
</template>

<style scoped>
header {
  align-items: center;
}
.App-container {
  display: block;
}
.left-twig {
  position: absolute;
  top: 0;
  left: 0;
  width: 400px;
  height: 400px;
  order: 1;
}
.right-twig {
  position: absolute;
  top: 0;
  right: 0;
  width: 400px;
  height: 400px;
  order: 2;
}

</style>
