
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.07,18.78h3.86a2.9,2.9,0,0,1,2.9,2.9v1a0,0,0,0,1,0,0H7.17a0,0,0,0,1,0,0v-1A2.9,2.9,0,0,1,10.07,18.78Z"/><polygon class="cls-1" points="12 2.64 13.49 5.66 16.83 6.14 14.41 8.5 14.98 11.82 12 10.25 9.02 11.82 9.59 8.5 7.17 6.14 10.51 5.66 12 2.64"/><line class="cls-1" x1="12" y1="18.78" x2="12" y2="10.09"/><line class="cls-1" x1="18.76" y1="22.64" x2="5.24" y2="22.64"/></svg>
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