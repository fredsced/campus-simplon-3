<template>
  <div class="about page">
    <h1>This is an about page</h1>
    <my-hello></my-hello>
    <counter></counter>
    <ComprendreThis></ComprendreThis>
    <v-for-imbriques :words="['hello', 'world', 'of', 'VueJS']"></v-for-imbriques>
  </div>
</template>
<script>
import myHello from "@/components/myHello.vue";
import Counter from "@/components/Counter.vue";
import ComprendreThis from "@/components/ComprendreThis.vue";
import VForImbriques from "@/components/VForImbriques.vue";
export default {
  components: {
    myHello,
    ComprendreThis,
    Counter,
    VForImbriques
  }
}
</script>

