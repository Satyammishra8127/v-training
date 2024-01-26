<template>
  <div>
  <home/>
  <Htmlbinding/>
</div>
</template>

<script>
/*import interpolation1 from './components/interpolation1.vue'
import methodsparams from './components/methodsparams.vue'
import events from './components/events.vue'
import twowaybinding from './components/twowaybinding.vue'
import getinputfieldvalue from './components/getinputfieldvalue.vue'
import Checkboxradio from './components/checkboxradio.vue'
import Else1 from './components/Else1.vue'
import loop1 from './components/loop1.vue'*/
import home from './components/home.vue'
import Htmlbinding from './components/Htmlbinding.vue';

export default {
  name: 'App',
  components: {
   /*interpolation1,
   methodsparams,
   events,
   twowaybinding,
   getinputfieldvalue,
    Checkboxradio,
    Else1,
    loop1,*/
    home,
    Htmlbinding
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
