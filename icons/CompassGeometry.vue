
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.75,23.89l-6-13.52-.28-.64A2.89,2.89,0,1,0,10,9.28l.49.49-.27.6-6,13.52L2.5,23.11l6-13.52.22,1.09a4.79,4.79,0,1,1,6.6,0l.22-1.09,6,13.52-1.75.78Z"/><line class="cls-2" x1="8.17" y1="13.92" x2="15.83" y2="13.92"/><line class="cls-2" x1="12" y1="12" x2="12" y2="15.83"/><line class="cls-2" x1="12" y1="0.5" x2="12" y2="3.38"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>