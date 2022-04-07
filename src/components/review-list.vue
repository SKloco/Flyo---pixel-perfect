<template>
  <section class="review-list">
    <reviewPreview v-for="review in reviews" :key="review" :review="review" />
  </section>
</template>

<script>
import reviewPreview from './review-preview.vue'
export default {
  created() {},
  data() {
    return {
      reviews: [
        {
          review: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
          svg: '/src/assets/profile-1.jpg',
          fullName: 'Satish Patel',
          job: 'Founder & CEO, Huddle',
        },
        {
          review: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
          svg: '/src/assets/profile-2.jpg',
          fullName: 'Bruce McKenzie',
          job: 'Founder & CEO, Huddle',
        },
        {
          review: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
          svg: '/src/assets/profile-3.jpg',
          fullName: 'Iva Boyd',
          job: 'Founder & CEO, Huddle',
        },
      ],
    }
  },
  methods: {},
  computed: {},
  components: { reviewPreview },
  unmounted() {},
}
</script>
