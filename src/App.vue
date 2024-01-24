<template>
  <div>
  <interpolation1/>
  <methodsparams/>
  <events/>
  <twowaybinding/>
  <getinputfieldvalue/>
  <checkboxradio/>
</div>
</template>

<script>
import interpolation1 from './components/interpolation1.vue'
import methodsparams from './components/methodsparams.vue'
import events from './components/events.vue'
import twowaybinding from './components/twowaybinding.vue'
import getinputfieldvalue from './components/getinputfieldvalue.vue'
import Checkboxradio from './components/checkboxradio.vue'

export default {
  name: 'App',
  components: {
   interpolation1,
   methodsparams,
   events,
   twowaybinding,
   getinputfieldvalue,
    Checkboxradio
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
