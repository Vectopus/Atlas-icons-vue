
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="10" x2="12" y2="2"/><line class="cls-1" x1="12" y1="22" x2="12" y2="14"/><polyline class="cls-1" points="8 18 12 22 16 18"/><polyline class="cls-1" points="16 6 12 2 8 6"/><line class="cls-1" x1="22" y1="12" x2="2" y2="12"/></svg>
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