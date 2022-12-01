
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.18,17.73a1,1,0,1,1,1,.95,1,1,0,0,1-1-.95"/><circle class="cls-1" cx="14.86" cy="16.77" r="0.95"/><polyline class="cls-1" points="15.82 16.77 15.82 11.04 10.09 12 10.09 17.73"/><path class="cls-1" d="M12,3.41,10.09,1.5H1.5V20.59A1.9,1.9,0,0,0,3.41,22.5H20.59a1.9,1.9,0,0,0,1.91-1.91V3.41Z"/><line class="cls-1" x1="1.5" y1="7.23" x2="22.5" y2="7.23"/></svg>
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