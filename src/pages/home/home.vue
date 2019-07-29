<template>
<div>
  <homeheader></homeheader>
  <p v-show="show">Welcome</p>
</div>
</template>

<script>
import homeheader from './components/header'
export default {
  name: 'Home',
  data: function () {
    return {
      show: false
    }
  },
  components: {
    homeheader: homeheader
  }
}
</script>

<style>

</style>
