
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.32,2A4,4,0,0,0,12,3.72,4,4,0,0,0,8.68,2a3.91,3.91,0,0,0-4,3.83c0,5.76,7.3,9,7.3,9s7.3-3.19,7.3-8.95A3.91,3.91,0,0,0,15.32,2Z"/><path class="cls-1" d="M12,14.78c0,3.65-2.69,4.57-.19,8.22"/><polyline class="cls-1" points="9.26 16.61 12 14.78 14.74 16.61"/></svg>
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