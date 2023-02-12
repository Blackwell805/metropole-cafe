<script>

import {defineComponent} from "vue";
import Header from "@/components/Header.vue";
import CoffeeList from "@/components/CoffeeList.vue";

export default defineComponent({
  components: {CoffeeList, Header}
})
</script>

<template>
  <div class='container'>
    <div class="banner">
      <header>
        <Header/>
      </header>
    </div>

    <div class="body">
      <main>
        <CoffeeList />
      </main>
    </div>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}
.container {
  display: flex;
  justify-content: center;
}
.banner {
  display: flex;
  justify-content: center;
  position: fixed;
  top: 50px;
  left: 0;
  width: 100%;
  padding: 10px;
}

</style>
