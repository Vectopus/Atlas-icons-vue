
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="9.14 6.29 5.32 2.48 1.5 6.29"/><path class="cls-1" d="M5.32,2.48V13h0a9.54,9.54,0,0,0,9.54,9.54,7.64,7.64,0,0,0,7.64-7.63,6.11,6.11,0,0,0-6.11-6.11,4.89,4.89,0,0,0-4.89,4.88,3.91,3.91,0,0,0,3.91,3.91,3.13,3.13,0,0,0,3.13-3.12A2.5,2.5,0,0,0,16,11.94"/></svg>
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