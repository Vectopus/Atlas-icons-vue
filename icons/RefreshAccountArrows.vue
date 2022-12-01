
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="10.09" r="1.91"/><path class="cls-1" d="M9.14,14.86h0A2.86,2.86,0,0,1,12,12h0a2.86,2.86,0,0,1,2.86,2.86h0"/><path class="cls-1" d="M18,3.41A10.5,10.5,0,0,1,12,22.5"/><path class="cls-1" d="M6,20.59A10.5,10.5,0,0,1,12,1.5"/><polyline class="cls-1" points="17.73 8.18 17.73 3.41 22.5 3.41"/><polyline class="cls-1" points="6.27 15.82 6.27 20.59 1.5 20.59"/></svg>
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