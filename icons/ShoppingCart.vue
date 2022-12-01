
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.21 15.82 22.48 12.96 22.48 4.36 4.15 4.36"/><path class="cls-1" d="M.52,1.5H3.39L7.2,15.82,5.54,18.31a1.48,1.48,0,0,0-.24.82h0a1.46,1.46,0,0,0,1.46,1.46h11.9"/><circle class="cls-1" cx="18.66" cy="21.55" r="0.95"/><circle class="cls-1" cx="9.11" cy="21.55" r="0.95"/></svg>
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