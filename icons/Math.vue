
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.52" y1="5.28" x2="10.09" y2="5.28"/><line class="cls-1" x1="5.3" y1="0.5" x2="5.3" y2="10.07"/><line class="cls-1" x1="1.48" y1="14.85" x2="9.13" y2="22.5"/><line class="cls-1" x1="9.13" y1="14.85" x2="1.48" y2="22.5"/><line class="cls-1" x1="13.91" y1="5.28" x2="23.48" y2="5.28"/><line class="cls-1" x1="13.91" y1="18.67" x2="23.48" y2="18.67"/><line class="cls-1" x1="17.74" y1="14.85" x2="19.65" y2="14.85"/><line class="cls-1" x1="17.74" y1="22.5" x2="19.65" y2="22.5"/></svg>
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