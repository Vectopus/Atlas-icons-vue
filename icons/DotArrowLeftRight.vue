
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="2" y1="12" x2="9" y2="12"/><polyline class="cls-1" points="6 8 2 12 6 16"/><line class="cls-1" x1="22" y1="12" x2="15" y2="12"/><polyline class="cls-1" points="18 16 22 12 18 8"/><circle class="cls-1" cx="12" cy="12" r="1"/></svg>
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