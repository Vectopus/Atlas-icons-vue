
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,22.5H1.5L9.37,3.27A2.85,2.85,0,0,1,12,1.5h0a2.85,2.85,0,0,1,2.63,1.77Z"/><polyline class="cls-1" points="7.17 8.63 10.09 10.09 12 7.23 13.91 8.18 16.09 6.82"/></svg>
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