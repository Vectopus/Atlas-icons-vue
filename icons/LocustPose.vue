
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.07,12h9.87a1.6,1.6,0,0,1,1.6,1.61h0a1.71,1.71,0,0,1-.11.59h0a7.16,7.16,0,0,1-6.64,4.5H7.2L2.41,14.89H.5"/><path class="cls-1" d="M17.72,13.93h0a3.47,3.47,0,0,1-3.1,1.92h0A2.64,2.64,0,0,0,12,18.49v.23"/><circle class="cls-1" cx="20.59" cy="8.2" r="1.91"/></svg>
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