
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="5.29"/><line class="cls-1" x1="12" y1="18.71" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="18.71" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/><circle class="cls-1" cx="12" cy="12" r="9.58"/><path class="cls-1" d="M14.88,9.13H11.27a1.19,1.19,0,0,0-1.19,1.19h0a1.19,1.19,0,0,0,.66,1.06l2.52,1.26a1.19,1.19,0,0,1,.66,1.06h0a1.19,1.19,0,0,1-1.19,1.19H9.12"/><line class="cls-1" x1="12" y1="7.21" x2="12" y2="9.13"/><line class="cls-1" x1="12" y1="14.88" x2="12" y2="16.79"/></svg>
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