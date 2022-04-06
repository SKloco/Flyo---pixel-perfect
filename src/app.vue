/<template>
  <section class="main-layout">
    <app-header/>
    <app-main/>
  </section>
</template>

<script>
 import appHeader from './components/app-header.vue'
 import appMain from './components/app-main.vue'
 
 

export default {
  name: 'cmp name',
//  props: {
//    car: Object,
//  },
  created() {},
  data() {
    return {}
  },
  methods: {},
  computed: {},
  components: {
    appHeader,
    appMain
  },
  unmounted() {},
}
</script>