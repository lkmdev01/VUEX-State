<template>
  <div>
    <HelloWorld />
    {{ $store.state.user.first_name }}
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { ref } from 'vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  setup() {
    
  },
  created(){
    
  }
}
</script>
