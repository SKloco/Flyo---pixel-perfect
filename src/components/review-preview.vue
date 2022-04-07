<template>
  <section class="review-preview">
    <span class="review">{{ review.review }} </span>
    <div class="container">
      <img :src="review.svg" />
      <div class="card">
        <span class="name">{{ review.fullName }} </span>
        <span class="job">{{ review.job }} </span>
      </div>
    </div>
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
