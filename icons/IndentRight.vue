
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="3.4" x2="23.5" y2="3.4"/><line class="cls-1" x1="0.5" y1="9.15" x2="14.88" y2="9.15"/><line class="cls-1" x1="0.5" y1="15.85" x2="14.88" y2="15.85"/><line class="cls-1" x1="0.5" y1="21.6" x2="23.5" y2="21.6"/><polyline class="cls-1" points="22.54 14.9 19.67 12.02 22.54 9.15"/></svg>
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