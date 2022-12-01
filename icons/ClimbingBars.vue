
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="0.55" x2="1.5" y2="23.45"/><line class="cls-1" x1="12" y1="0.55" x2="12" y2="23.45"/><line class="cls-1" x1="22.5" y1="6.27" x2="22.5" y2="23.45"/><line class="cls-1" x1="1.5" y1="2.45" x2="12" y2="2.45"/><line class="cls-1" x1="1.5" y1="6.27" x2="12" y2="6.27"/><line class="cls-1" x1="1.5" y1="10.09" x2="12" y2="10.09"/><line class="cls-1" x1="1.5" y1="13.91" x2="12" y2="13.91"/><line class="cls-1" x1="1.5" y1="17.73" x2="12" y2="17.73"/><line class="cls-1" x1="1.5" y1="21.55" x2="12" y2="21.55"/><line class="cls-1" x1="12" y1="8.18" x2="22.5" y2="8.18"/><line class="cls-1" x1="12" y1="12" x2="22.5" y2="12"/><line class="cls-1" x1="12" y1="15.82" x2="22.5" y2="15.82"/><line class="cls-1" x1="12" y1="19.64" x2="22.5" y2="19.64"/></svg>
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