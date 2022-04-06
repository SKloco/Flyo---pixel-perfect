<template>
  <main>
    <intro />
    <featureList />
    <secondryMain />
    <reviewList />
    <getStarted />
  </main>
</template>

<script>
import intro from './intro.vue'
import featureList from './feature-list.vue'
import secondryMain from './secondryMain.vue'
import reviewList from './review-list.vue'
import getStarted from './get-started.vue'
export default {
  created() {},
  data() {
    return {}
  },
  methods: {},
  computed: {},
  components: {
    intro,
    featureList,
    secondryMain,
    reviewList,
    getStarted,
  },
  unmounted() {},
}
</script>
