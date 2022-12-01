
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="4.33" y1="3.38" x2="10.08" y2="3.38"/><line class="cls-1" x1="0.5" y1="9.13" x2="10.08" y2="9.13"/><line class="cls-1" x1="0.5" y1="14.88" x2="10.08" y2="14.88"/><line class="cls-1" x1="0.5" y1="20.63" x2="10.08" y2="20.63"/><line class="cls-1" x1="13.92" y1="3.38" x2="23.5" y2="3.38"/><line class="cls-1" x1="13.92" y1="9.13" x2="23.5" y2="9.13"/><line class="cls-1" x1="13.92" y1="14.88" x2="23.5" y2="14.88"/><line class="cls-1" x1="13.92" y1="20.63" x2="19.67" y2="20.63"/></svg>
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