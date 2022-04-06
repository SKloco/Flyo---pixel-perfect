<template>
  <section class="feature-preview">
    <img :src="'/src/assets/' + info.svg" />
    <span class="title">{{ info.title }} </span>
    <span class="description">{{ info.description }} </span>
  </section>
</template>

<script>
export default {
  props: {
    info: Object,
  },
  created() {},
  data() {
    return {}
  },
  methods: {},
  computed: {},
  components: {},
  unmounted() {},
}
</script>
