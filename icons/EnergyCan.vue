
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="12.32 8.18 11.04 12 12.96 12 11.68 15.82"/><polygon class="cls-1" points="16.77 22.5 7.23 22.5 5.32 18.68 5.32 5.32 7.23 1.5 16.77 1.5 18.68 5.32 18.68 18.68 16.77 22.5"/><line class="cls-1" x1="5.32" y1="5.32" x2="15.82" y2="5.32"/><line class="cls-1" x1="5.32" y1="18.68" x2="15.82" y2="18.68"/><line class="cls-1" x1="4.36" y1="1.5" x2="19.64" y2="1.5"/></svg>
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