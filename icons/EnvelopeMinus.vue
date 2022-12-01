
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8.18" y1="2.93" x2="15.82" y2="2.93"/><polyline class="cls-1" points="16.68 5.79 22.5 5.79 22.5 21.07 1.5 21.07 1.5 5.79 7.32 5.79"/><polyline class="cls-1" points="1.5 5.79 12 16.3 22.5 5.79"/><line class="cls-1" x1="9.14" y1="13.43" x2="1.5" y2="21.07"/><line class="cls-1" x1="22.5" y1="21.07" x2="14.86" y2="13.43"/><polyline class="cls-1" points="16.68 5.79 22.5 5.79 22.5 21.07 1.5 21.07 1.5 5.79 7.32 5.79"/></svg>
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