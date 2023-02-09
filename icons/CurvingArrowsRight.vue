
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10.09 1.5 15.82 1.5 15.82 7.23"/><polyline class="cls-1" points="15.82 16.77 15.82 22.5 10.09 22.5"/><path class="cls-1" d="M15.82,1.5,10.21,7.11a6.92,6.92,0,0,0-2,4.89h0a6.92,6.92,0,0,0,2,4.89l5.61,5.61"/></svg>
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