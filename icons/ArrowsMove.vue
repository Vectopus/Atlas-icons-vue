
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="14 12 21.94 12 22 12"/><polyline class="cls-1" points="10 12 2.06 12 2 12"/><polyline class="cls-1" points="6 8 2 12 6 16"/><polyline class="cls-1" points="18 16 22 12 18 8"/><polyline class="cls-1" points="12 22 12 21.94 12 14"/><polyline class="cls-1" points="12 2 12 2.06 12 10"/><polyline class="cls-1" points="16 6 12 2 8 6"/><polyline class="cls-1" points="8 18 12 22 16 18"/><circle class="cls-1" cx="12" cy="12" r="2"/></svg>
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