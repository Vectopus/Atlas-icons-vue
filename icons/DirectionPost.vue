
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 8.15 5.29 8.15 2.42 5.75 5.29 3.35 12 3.35 12 8.15"/><polygon class="cls-1" points="12 6.23 18.71 6.23 21.58 8.63 18.71 11.02 12 11.02 12 6.23"/><line class="cls-1" x1="12" y1="22.52" x2="12" y2="0.48"/><line class="cls-1" x1="0.5" y1="22.52" x2="23.5" y2="22.52"/></svg>
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