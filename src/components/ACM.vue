<script>
  import { mapState, mapMutations } from 'vuex'
  //import ManuSample from './manutemplate.vue'
  export default {
    name: 'ACM',
    //components:ManuSample,
    data () {
      return {}
    },
    beforeMount () {

    },
    mounted () {

    },
    destroyed () {

    },
    computed: {
      ...mapState({})
    },
    methods: {
      ...mapMutations({})
    },
  }

</script>
<!-- vue-loader's scoped css won't work with style-loader -->
<style scoped lang="vcss">

</style>

<template>
    <div :id="$options.name" :class="$options.name">
        <div><manu-sample></manu-sample></div>
        <div>

            <nothing></nothing>
        </div>

    </div>
</template>
