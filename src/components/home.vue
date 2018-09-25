<script>
  import { mapState, mapMutations } from 'vuex'

  export default {
    name: 'home',
    beforeMount () {

    },
    mounted () {

    },
    destroyed () {

    },
    computed: {
      ...mapState({
        count: state => state.count
      })
    },
    methods: {
      ...mapMutations({
        increment: 'increment'
      })
    },
  }

</script>

<style scoped lang="vcss">


</style>

<template>
    <div :id="$options.name" :class="$options.name">
        <section class="hero is-medium is-primary is-bold">
            <div class="hero-body">
                <div class="container">
                    <h1 class="title">
                        感觉这才像一个主页
                    </h1>
                    <h2 class="subtitle">
                        Hello World
                    </h2>
                </div>
            </div>
        </section>
    </div>
</template>
