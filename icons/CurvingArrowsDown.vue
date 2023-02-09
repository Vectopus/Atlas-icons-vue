
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 10.09 22.5 15.82 16.77 15.82"/><polyline class="cls-1" points="7.23 15.82 1.5 15.82 1.5 10.09"/><path class="cls-1" d="M22.5,15.82l-5.61-5.61a6.92,6.92,0,0,0-4.89-2h0a6.92,6.92,0,0,0-4.89,2L1.5,15.82"/></svg>
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