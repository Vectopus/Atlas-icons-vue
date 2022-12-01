
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="17.17 20.03 22.5 21.55 22.5 4.36 15.82 2.46 8.18 4.36 1.5 2.46 1.5 19.64 8.18 21.55 14.43 19.98"/><path class="cls-1" d="M19.64,15.58c0,2.39-3.82,6-3.82,6S12,18,12,15.58A3.7,3.7,0,0,1,15.82,12,3.7,3.7,0,0,1,19.64,15.58Z"/><circle class="cls-2" cx="15.82" cy="15.82" r="0.95"/><line class="cls-1" x1="8.18" y1="4.36" x2="8.18" y2="21.55"/><line class="cls-1" x1="15.82" y1="2.45" x2="15.82" y2="12"/></svg>
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