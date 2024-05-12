<template>
  <div >
    <p>
       Nueva wea
    </p>
    <ProductosApp msg="Welcome to Your Vue.js App"/>

  </div>
</template>

<script>
import ProductosApp from './ProductosApp/ProductosApp.vue'

export default {
  name: 'HomeApp',
  props: {
    msg: String
  },
  components: {
    ProductosApp
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
