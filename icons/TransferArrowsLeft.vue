
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.23 7.23 7.23 1.5 12.96 1.5"/><line class="cls-1" x1="22.5" y1="16.77" x2="7.23" y2="1.5"/><polyline class="cls-1" points="16.77 16.77 16.77 22.5 11.04 22.5"/><line class="cls-1" x1="1.5" y1="7.23" x2="16.77" y2="22.5"/></svg>
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