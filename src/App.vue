<template>
    <div>
        <nav-bar></nav-bar>
        <div id="page-wrapper" class="gray-bg" style="min-height: 515px;">
            <bottom-bar msg_boas_vindas="Seja bem vindo ao Sistema"/>
            <router-view></router-view>
            <footer-vue></footer-vue>
        </div>
        <right-bar></right-bar>
    </div>
</template>

<script>

    import NavBar from "./components/layouts/NavBar";
    import BottomBar from "./components/layouts/BottomBar";
    import FooterVue from "./components/layouts/FooterVue";
    import RightBar from "./components/layouts/RightBar";

    export default {
        name: 'App',
        components: {RightBar, FooterVue, NavBar, BottomBar}
    }
</script>

<style>
</style>
