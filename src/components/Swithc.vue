<template>
  <div>
    <div class="on" @click='isOn = true' :class='{active: isOn}'>
    </div>
    <div class="off" @click='isOn = false' :class='{active: !isOn}'>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        isOn: true
      }
    }
  }
</script>

<style>

</style>
