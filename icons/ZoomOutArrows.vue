
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1" y1="1" x2="10.59" y2="10.59"/><line class="cls-1" x1="13.41" y1="13.41" x2="23" y2="23"/><polyline class="cls-1" points="21 13 13 13 13 21"/><polyline class="cls-1" points="3 11 11 11 11 3"/></svg>
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