<template>
<div>
    <transition>
        <p v-show="show">Welcome</p>
    </transition>
        <router-link to='/album'> Go</router-link>
</div>
</template>

<script>
import { setTimeout } from 'timers'
export default {
  name: 'Home',
  data: function () {
    return {
      show: false
    }
  },
  mounted: function () {
    setTimeout(() => {
      this.show = true
    }, 2000)
    setTimeout(() => {
      this.show = false
    }, 4000)
  }
}
</script>

<style>
</style>
