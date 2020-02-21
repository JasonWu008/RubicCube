<template>
  <div class="app">
    <div id="rubic">
    </div>
  </div>
</template>

<script>
import { threeStart } from '../utils/Rubic.js'
export default {
  name: 'Rubic',
  mounted () {
    threeStart()
  }
}
</script>

<style scoped>
#rubic {
  cursor: pointer;
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: #fff;
  margin: -15px;
}
</style>
