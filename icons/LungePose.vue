
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="12 16.76 19.65 16.76 19.65 22.5 21.57 22.5"/><path class="cls-1" d="M2.43,22.5h6.7L12,16.76V12a1.91,1.91,0,0,1,1.91-1.91h0A1.91,1.91,0,0,1,15.83,12v2.87"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="11.98"/><circle class="cls-1" cx="14.39" cy="6.72" r="2.39"/></svg>
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