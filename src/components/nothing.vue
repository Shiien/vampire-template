<script>
  import { mapState, mapMutations } from 'vuex'
  export default {
    name: 'nothing',
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
  .hero-body {
    flex-grow: 1;
    flex-shrink: 0;
    padding: 3rem 1.5rem;
  }
</style>

<template>
  <div :id="$options.name" :class="$options.name">
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            <strong>这里暂时没有任何东西</strong>
          </h1>
        </div>
      </div>
    </section>
  </div>
</template>
