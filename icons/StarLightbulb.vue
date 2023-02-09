
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 7.23 12.75 8.8 14.44 9.05 13.22 10.27 13.51 12 12 11.19 10.49 12 10.78 10.27 9.56 9.05 11.25 8.8 12 7.23"/><path class="cls-1" d="M19.64,9.14A7.64,7.64,0,1,0,6.92,14.83a3.81,3.81,0,0,1,1.26,2.83v2.93a1.91,1.91,0,0,0,1.91,1.91h3.82a1.91,1.91,0,0,0,1.91-1.91V17.66a3.76,3.76,0,0,1,1.25-2.82A7.62,7.62,0,0,0,19.64,9.14Z"/><line class="cls-1" x1="8.18" y1="17.73" x2="15.82" y2="17.73"/></svg>
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