
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M1.5,11.81a14,14,0,0,0,6.7,3.58,16.76,16.76,0,0,0,3.8.43,16.47,16.47,0,0,0,3.83-.44,13.94,13.94,0,0,0,6.67-3.57"/><path class="cls-1" d="M3.9,5.32c1.18,5.8,4.19,5.13,4.3,10.07a2.91,2.91,0,0,1,0,.3,4.39,4.39,0,0,1-3.13,4.2"/><path class="cls-1" d="M20.13,5.36c-1.2,5.75-4.19,5.1-4.3,10,0,.09,0,.21,0,.31a4.39,4.39,0,0,0,3.11,4.19"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="22.5"/></svg>
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