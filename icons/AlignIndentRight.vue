
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="15.8" y1="21.57" x2="15.8" y2="2.43"/><polyline class="cls-1" points="22.5 14.87 19.63 12 22.5 9.13"/><line class="cls-1" x1="12.93" y1="20.61" x2="0.5" y2="20.61"/><line class="cls-1" x1="12.93" y1="14.87" x2="0.5" y2="14.87"/><line class="cls-1" x1="12.93" y1="9.13" x2="0.5" y2="9.13"/><line class="cls-1" x1="12.93" y1="3.39" x2="0.5" y2="3.39"/></svg>
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