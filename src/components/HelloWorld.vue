<template>
  <h1>{{ msg}}</h1>
  
  <p>Bienvenu sur le site d'Annette</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
