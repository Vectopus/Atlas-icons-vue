
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="exchange"><circle class="cls-1" cx="18.68" cy="5.32" r="3.82"/><circle class="cls-1" cx="5.32" cy="18.68" r="3.82"/><path class="cls-1" d="M18.68,13.91v.95A5.72,5.72,0,0,1,13,20.59"/><polyline class="cls-1" points="16.35 15.28 18.74 12.9 21.13 15.28"/><path class="cls-1" d="M5.38,10.09v-1A5.73,5.73,0,0,1,11.1,3.35"/><polyline class="cls-1" points="7.71 8.66 5.32 11.04 2.93 8.66"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>