/
<template>
  <section class="main-layout">
    <app-header />
    <app-main />
    <app-footer />
  </section>
</template>

<script>
import appHeader from './components/app-header.vue'
import appMain from './components/app-main.vue'
import appFooter from './components/app-footer.vue'

export default {
  created() {},
  data() {
    return {}
  },
  methods: {},
  computed: {},
  components: {
    appHeader,
    appMain,
    appFooter,
  },
  unmounted() {},
}
</script>
