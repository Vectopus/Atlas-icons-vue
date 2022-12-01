
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="21.5 9.15 12 14.85 2.5 9.15 12 3.45 21.5 9.15"/><line class="cls-1" x1="18.65" y1="10.88" x2="18.65" y2="15.8"/><path class="cls-1" d="M18.65,15.8v.95c0,2.1-3,3.8-6.65,3.8s-6.65-1.7-6.65-3.8V10.88"/><line class="cls-1" x1="12" y1="9.15" x2="15.8" y2="12.95"/><line class="cls-1" x1="15.8" y1="16.75" x2="15.8" y2="12.95"/></svg>
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