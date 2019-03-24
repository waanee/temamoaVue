<template>
    <header uk-sticky>
        <div class="container">
            <nav class="uk-navbar-container" uk-navbar>
                <div class="uk-navbar-left">
                    <!-- LOGO -->
                    <nuxt-link to="/" class="uk-navbar-item uk-logo">THELOGO</nuxt-link>
                </div>

                <div class="uk-navbar-center mobile-hide">
                    <ul class="uk-navbar-nav">
                        <li><nuxt-link to="/">home</nuxt-link></li>
                        <li><nuxt-link to="/about">about</nuxt-link></li>
                    </ul>
                </div>

                <div class="uk-navbar-right">
                    <span class="right-menu" uk-toggle="target: #offcanvas-overlay" uk-icon="icon: menu"></span>
                </div>
            </nav>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style>
.right-menu {
    margin-right:20px; cursor: pointer;
}
</style>