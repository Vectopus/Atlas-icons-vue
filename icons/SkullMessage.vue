
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="12 15.82 1.5 15.82 1.5 2.46 20.59 2.46 20.59 10.09"/><polyline class="cls-1" points="1.5 2.46 11.04 11.04 20.59 2.46"/><path class="cls-1" d="M22.5,16.3a4.3,4.3,0,1,0-6.68,3.57v1.68h4.77V19.87A4.32,4.32,0,0,0,22.5,16.3Z"/><circle class="cls-2" cx="16.77" cy="16.77" r="0.95"/><circle class="cls-2" cx="19.64" cy="16.77" r="0.95"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>