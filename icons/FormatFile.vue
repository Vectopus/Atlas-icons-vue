
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="12.95" width="13.36" height="5.73"/><polyline class="cls-1" points="4.36 18.68 4.36 22.5 21.55 22.5 21.55 6.27 16.77 1.5 4.36 1.5 4.36 12.96"/><polygon class="cls-1" points="21.55 6.27 21.55 7.23 15.82 7.23 15.82 1.5 16.77 1.5 21.55 6.27"/></svg>
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