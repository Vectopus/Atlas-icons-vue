
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8.18" y1="4.34" x2="15.82" y2="4.34"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="8.16"/><polyline class="cls-1" points="16.68 7.21 22.5 7.21 22.5 22.48 1.5 22.48 1.5 7.21 7.32 7.21"/><polyline class="cls-1" points="1.5 7.21 12 17.7 22.5 7.21"/><line class="cls-1" x1="9.14" y1="14.84" x2="1.5" y2="22.48"/><line class="cls-1" x1="22.5" y1="22.48" x2="14.86" y2="14.84"/><polyline class="cls-1" points="16.68 7.21 22.5 7.21 22.5 22.48 1.5 22.48 1.5 7.21 7.32 7.21"/></svg>
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