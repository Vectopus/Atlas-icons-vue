
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 20.63 17.75 20.63 17.75 14.88"/><polyline class="cls-1" points="0.5 3.38 6.25 3.38 6.25 9.13"/><path class="cls-1" d="M9.23,1.83A10.12,10.12,0,0,1,12,1.46a10.54,10.54,0,0,1,6.06,19.16"/><path class="cls-1" d="M14.77,22.17a10.12,10.12,0,0,1-2.77.37A10.54,10.54,0,0,1,5.94,3.38"/></svg>
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