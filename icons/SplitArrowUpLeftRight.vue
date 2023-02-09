
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="6 8 2 12 6 16"/><polyline class="cls-1" points="18 16 22 12 18 8"/><path class="cls-1" d="M12,24V18a6,6,0,0,0-6-6H2"/><path class="cls-1" d="M12,24V18a6,6,0,0,1,6-6h4"/><polyline class="cls-1" points="16 6 12 2 8 6"/><line class="cls-1" x1="12" y1="2" x2="12" y2="18"/></svg>
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