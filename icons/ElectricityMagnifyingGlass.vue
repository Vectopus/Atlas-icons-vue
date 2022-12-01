
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="10.09" cy="10.09" r="8.59"/><line class="cls-1" x1="22.5" y1="22.5" x2="16.77" y2="16.77"/><polygon class="cls-1" points="10.09 7.23 8.18 10.09 10.09 10.09 10.09 7.23"/><polygon class="cls-1" points="10.09 12.96 12 10.09 10.09 10.09 10.09 12.96"/></svg>
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