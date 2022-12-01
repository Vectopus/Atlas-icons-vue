
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="14.85" r="7.65"/><polyline class="cls-1" points="8.17 8.23 8.17 3.37 15.83 3.37 15.83 8.23"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.37"/><path class="cls-1" d="M4.35,12.93c7.65-2.86,7.65,1.92,15.3,0"/><path class="cls-1" d="M4.35,17.72c7.65-2.87,7.65,1.91,15.3,0"/></svg>
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