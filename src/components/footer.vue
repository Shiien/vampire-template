<script>
  import { mapState, mapMutations } from 'vuex'
  export default {
    name: 'footers',
    data() {
      return {

      }
    },
    beforeMount() {

    },
    mounted() {

    },
    destroyed() {

    },
    computed: {
      ...mapState({

      })
    },
    methods: {
      ...mapMutations({

      })
    },
  };

</script>
<!-- vue-loader's scoped css won't work with style-loader -->
<style scoped lang="vcss">

</style>

<template>
  <div :id="$options.name" :class="$options.name">
    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>copied</strong> by SaucerHi.
        </p>
      </div>
    </footer>
  </div>
</template>
