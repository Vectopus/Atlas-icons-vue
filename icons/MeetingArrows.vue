
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="23" y1="1" x2="13.41" y2="10.59"/><line class="cls-1" x1="10.59" y1="13.41" x2="1" y2="23"/><polyline class="cls-1" points="11 21 11 13 3 13"/><polyline class="cls-1" points="13 3 13 11 21 11"/></svg>
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