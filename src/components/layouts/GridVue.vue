<template>
    <div :class="'col s' + (tamanho || '12')">
        <slot></slot>
    </div>
</template>

<script>
    export default {
        name: "GridVue",
        props: ['tamanho']
    }
</script>

<style scoped>

</style>