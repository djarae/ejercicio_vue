<template>
  <div >
    <p>
       ProductosApp Component!
    </p>
    <CrearProducto msg="Welcome to Your Vue.js App"/>
    <TablaProducto msg="Welcome to Your Vue.js App"/>

  </div>
</template>

<script>
import CrearProducto from './CrearProducto/CrearProducto.vue'
import TablaProducto from './TablaProducto/TablaProducto.vue'

export default {
  name: 'ProductosApp',
  props: {
    msg: String
  },
  components: {
    CrearProducto,
    TablaProducto
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
