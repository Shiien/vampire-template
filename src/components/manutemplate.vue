<script>
  import { mapState, mapMutations } from 'vuex'

  export default {
    name: 'manu-sample',
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
    .manu-sample {
        float: left;
        width: 15%;
        height: auto;
    }
</style>

<template>
    <div :id="$options.name" :class="$options.name">

        <!--<div class="tile is-parent">-->
        <article class="tile is-child notification is-success">
            <div class="content">
                <aside class="menu">
                    <p class="menu-title">
                        <strong>导航</strong>
                    </p>
                    <ul class="menu-list">
                        <li>
                            <nav-item to="/" icon="fa-home">主页</nav-item>
                        </li>
                        <li>
                            <nav-item to="/author" icon="fa-wifi">作者</nav-item>
                        </li>
                        <li>
                            <nav-item to="/ACM" icon="fa-heart">ACM训练</nav-item>
                        </li>
                    </ul>
                </aside>
            </div>
        </article>
        <!--</div>-->

    </div>
</template>
