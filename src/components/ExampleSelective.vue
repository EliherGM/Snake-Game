<template>
  <h1 v-if="age < 18">Eres menor de edad</h1>
  <h1 v-else>Eres mayor de edad</h1>
</template>

<script>
  import { defineComponent } from "vue"
  export default defineComponent({
    name: 'ExampleSelective',
    setup(){
      let age = 20
      return {age}
    }
  })

  // Con setup en la etiqueta script
  // el codigo queda de la sig manera:
  // let age = 10;

</script>

<style scoped>
  
</style>