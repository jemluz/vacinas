<template lang="pug">
  div#inicio
    p {{ msg }}
</template>

<script>
export default {
  name: 'Inicio',
  props: ['msg']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#inicio {
}
</style>
