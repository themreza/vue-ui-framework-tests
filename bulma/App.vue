<template>
    <div id="main-wrapper">
        <section class="header">
            <div class="top-bar is-hidden-mobile pl-20 pr-20 pt-4 pb-4">
                <div class="columns is-gapless">
                    <div class="column vcentered justify-left">
                        <font-awesome-icon icon="phone-alt" class="fa"/>
                        <span class="pl-10">01 02 034 56 78</span>
                    </div>
                    <div class="column vcentered justify-center">
                        <font-awesome-icon icon="truck" class="fa"/>
                        <span class="pl-10">Free delivery on orders above $30</span>
                    </div>
                    <div class="column vcentered justify-right">
                        <font-awesome-icon icon="check-square" class="fa"/>
                        <span class="pl-10">30 day return policy</span>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    import Vue from 'vue'
    import Buefy from 'buefy'
    import { library } from '@fortawesome/fontawesome-svg-core'
    import { faPhoneAlt, faTruck, faCheckSquare } from '@fortawesome/free-solid-svg-icons'
    import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

    library.add(faPhoneAlt, faTruck, faCheckSquare)
    Vue.component('font-awesome-icon', FontAwesomeIcon)

    Vue.use(Buefy)

    export default{}
</script>

<style lang="scss">
    @import "./variables.scss";

    .top-bar {
        background-color: $primary-color;
        color: $primary-text-color;
    }
</style>