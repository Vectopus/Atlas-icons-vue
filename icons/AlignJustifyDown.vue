
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="11.07" y1="3.37" x2="23.5" y2="3.37"/><line class="cls-1" x1="11.07" y1="9.11" x2="23.5" y2="9.11"/><line class="cls-1" x1="11.07" y1="14.85" x2="23.5" y2="14.85"/><line class="cls-1" x1="11.07" y1="20.59" x2="23.5" y2="20.59"/><polyline class="cls-1" points="9.15 16.76 5.33 20.59 1.5 16.76"/><line class="cls-1" x1="5.33" y1="2.41" x2="5.33" y2="20.59"/></svg>
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