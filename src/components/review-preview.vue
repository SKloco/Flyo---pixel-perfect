<template>
  <section class="review-preview">
      <img :src="'/src/assets/' + review.svg" />
      <span class="title">{{ review.review }} </span>
      <span class="description">{{ review.fullName }} </span>
      <span class="description">{{ review.job }} </span>
  </section>
</template>

<script>
export default {
  props: {
    review: Object,
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
