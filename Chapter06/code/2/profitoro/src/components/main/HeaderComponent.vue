<template>
  <div>
    <button @click="logout">Logout</button>
  </div>
</template>
<script>
  import {mapActions} from 'vuex'

  export default {
    methods: {
      ...mapActions(['logout'])
    }
  }
</script>
<style scoped lang="sass">

</style>
