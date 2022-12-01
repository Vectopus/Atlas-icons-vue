
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.89,6.63h3.9a2,2,0,0,1,2,2V16.4a2,2,0,0,1-2,2H14.93l-1.42-2.12a1.81,1.81,0,0,0-3,0L9.07,18.35H3.21a2,2,0,0,1-2-2V8.58a2,2,0,0,1,2-1.95H8.09"/><line class="cls-1" x1="4.18" y1="10.53" x2="6.14" y2="10.53"/><line class="cls-1" x1="4.18" y1="14.44" x2="6.14" y2="14.44"/><polygon class="cls-1" points="12.98 6.63 11.02 7.6 11.02 5.65 12.98 6.63 12.98 6.63"/></svg>
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