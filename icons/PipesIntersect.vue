
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,2.43V8.16H8.18a1,1,0,0,1,1,.95V22.48h5.72V9.11a1,1,0,0,1,1-.95H22.5V2.43Z"/><line class="cls-1" x1="1.5" y1="0.52" x2="1.5" y2="10.07"/><line class="cls-1" x1="22.5" y1="0.52" x2="22.5" y2="10.07"/><line class="cls-1" x1="7.23" y1="22.48" x2="16.77" y2="22.48"/><line class="cls-1" x1="7.23" y1="12.93" x2="16.77" y2="12.93"/></svg>
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