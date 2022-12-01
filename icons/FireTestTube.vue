
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.25,20.75a2.25,2.25,0,0,1-4.5,0C9.75,19.25,12,17,12,17S14.25,19.25,14.25,20.75Z"/><polyline class="cls-1" points="1 24 1 22 4 15 20 15 23 22 23 24"/><line class="cls-1" x1="7" y1="23" x2="17" y2="23"/><line class="cls-1" x1="8" y1="1" x2="16" y2="1"/><path class="cls-1" d="M14,7V1H10V7L6.49,11.39A2.2,2.2,0,0,0,6,12.78H6A2.21,2.21,0,0,0,8.22,15h7.56A2.21,2.21,0,0,0,18,12.78h0a2.2,2.2,0,0,0-.49-1.39Z"/><line class="cls-1" x1="8" y1="10" x2="13" y2="10"/></svg>
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