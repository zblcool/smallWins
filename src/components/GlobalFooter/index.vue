<template>
  <global-footer class="footer custom-render">
    <template v-slot:links>
      <a href="https://www.github.com/vueComponent/pro-layout" target="_blank">Contact</a>
      <a href="https://github.com/zblcool" target="_blank">Github</a>
      <a href="/" target="_blank">@SmallWIns</a>
    </template>
    <template v-slot:copyright>
      <a href="https://github.com/vueComponent" target="_blank">SmallWins</a>
    </template>
  </global-footer>
</template>

<script>
import { GlobalFooter } from '@ant-design-vue/pro-layout'

export default {
  name: 'ProGlobalFooter',
  components: {
    GlobalFooter
  }
}
</script>
