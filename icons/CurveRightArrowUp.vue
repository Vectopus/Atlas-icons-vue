
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="13.91 6.32 10.09 2.5 6.27 6.32"/><path class="cls-1" d="M10.09,23.5V21.59A1.92,1.92,0,0,1,12,19.68H13a4.78,4.78,0,0,0,4.78-4.77h0A4.77,4.77,0,0,0,13,10.14H12a1.92,1.92,0,0,1-1.91-1.91V2.5"/></svg>
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