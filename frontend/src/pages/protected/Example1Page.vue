<!--=========================TEMPLATE=========================-->
<template>
  <div class="container">
    {{msg('mainText')}}
  </div>
</template>
<!--=======================TEMPLATE END=======================-->

<!--==========================SCRIPT==========================-->
<script>
  import {messageUtils} from '../../mixins/messageUtils'

  export default {
    name: "example1Page",
    mixins: [messageUtils],
  }
</script>
<!--=========================SCRIPT END========================-->

<!--===========================STYLE===========================-->
<style scoped>
</style>
<!--=========================STYLE END=========================-->
