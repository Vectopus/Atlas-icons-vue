
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10.09 6.32 13.91 2.5 17.73 6.32"/><path class="cls-1" d="M13.91,2.5V8.23A1.92,1.92,0,0,1,12,10.14h-.95a4.77,4.77,0,0,0-4.78,4.77h0a4.78,4.78,0,0,0,4.78,4.77H12a1.92,1.92,0,0,1,1.91,1.91V23.5"/></svg>
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