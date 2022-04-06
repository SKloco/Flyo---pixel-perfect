<template>
  <section class="feature-list">
    <featurePreview v-for="info in featuresInfo" :key="info" :info="info" />
  </section>
</template>

<script>
import featurePreview from './feature-preview.vue'

export default {
  created() {},
  data() {
    return {
      featuresInfo: [
        {
          title: 'Access your files, anywhere',
          svg: 'icon-access-anywhere.svg',
          description: 'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.',
        },
        {
          title: 'Security you can trust',
          svg: 'icon-security.svg',
          description: '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.',
        },
        {
          title: 'Real-time collaboration',
          svg: 'icon-collaboration.svg',
          description: 'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.',
        },
        {
          title: 'Store any type of file',
          svg: 'icon-any-file.svg',
          description: 'Whether you are sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.',
        },
      ],
    }
  },
  methods: {},
  computed: {},
  components: { featurePreview },
  unmounted() {},
}
</script>
