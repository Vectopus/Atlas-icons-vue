
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="1.48 3.41 4.35 6.28 9.13 1.5"/><line class="cls-1" x1="16.78" y1="7.24" x2="22.52" y2="1.5"/><line class="cls-1" x1="22.52" y1="7.24" x2="16.78" y2="1.5"/><path class="cls-1" d="M7.22,23.5A4.78,4.78,0,0,1,12,18.72h0a4.78,4.78,0,0,1,4.78,4.78"/><circle class="cls-1" cx="12" cy="13.93" r="2.87"/></svg>
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