<!-- 首页信息 -->
<template>
  <div>QVEUI 版本：{{ version }}</div>
</template>

<script>
import { version } from 'qveui'
export default {
  // components: {},
  // props: {},
  // data () {
  //   return {
  //   };
  // },

  // computed: {},
  // mounted: {},
  // methods: {},
  // created () { }
  setup (props, context) {

    return { version }
  },
}

</script>
<style lang='less' scoped>
</style>