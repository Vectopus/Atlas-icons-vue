
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.23 16.77 1.5 16.77 1.5 11.04"/><line class="cls-1" x1="16.77" y1="1.5" x2="1.5" y2="16.77"/><polyline class="cls-1" points="16.77 7.23 22.5 7.23 22.5 12.96"/><line class="cls-1" x1="7.23" y1="22.5" x2="22.5" y2="7.23"/></svg>
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