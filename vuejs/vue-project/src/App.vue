<script>
import ChildComp from './ChildComp.vue'

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      msg: 'slot1',
      msg1: 'slot2'
    }
  }
}
</script>

<template>
  <ChildComp>{{ msg }}</ChildComp>
</template>