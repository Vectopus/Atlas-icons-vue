
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="2.45" y1="12.05" x2="7.23" y2="12.05"/><polyline class="cls-1" points="5.32 14.91 2.46 12.04 5.32 9.18"/><line class="cls-1" x1="21.55" y1="12.05" x2="16.77" y2="12.05"/><polyline class="cls-1" points="18.68 9.18 21.55 12.04 18.68 14.91"/><line class="cls-1" x1="2.45" y1="12.05" x2="7.23" y2="12.05"/><polyline class="cls-1" points="5.32 14.91 2.46 12.04 5.32 9.18"/><line class="cls-1" x1="21.55" y1="12.05" x2="16.77" y2="12.05"/><polyline class="cls-1" points="18.68 9.18 21.55 12.04 18.68 14.91"/><line class="cls-1" x1="12" y1="2.5" x2="12" y2="7.27"/><polyline class="cls-1" points="9.14 5.36 12 2.5 14.86 5.36"/><circle class="cls-1" cx="12" cy="11.09" r="1.91"/><polyline class="cls-1" points="13.91 23.5 13.91 19.68 14.86 18.73 14.86 14.91 9.14 14.91 9.14 18.73 10.09 19.68 10.09 23.5"/></svg>
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