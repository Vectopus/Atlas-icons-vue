
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 22.22 21.77 17.34 21.77 6.59 12 1.78 2.23 6.59 2.23 17.34 12 22.22"/><polyline class="cls-1" points="2.23 6.59 12 11.39 12 22.22"/><polyline class="cls-1" points="12 22.22 12 11.39 21.77 6.59"/><polyline class="cls-1" points="21.77 6.59 12 11.39 2.23 6.59"/></svg>
</template>
<script>
    export default {
        props: {
            size: {
                type: Number,
                default: 24,
                required: false,
            },
            weight: {
                type: Number,
                default: 2,
                required: false,
            },
        }
    }
</script>
<style scoped>
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>