
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="9.13"/><line class="cls-1" x1="12" y1="14.88" x2="12" y2="23.5"/><polyline class="cls-1" points="15.83 18.71 12 14.88 8.17 18.71"/><polyline class="cls-1" points="8.17 5.29 12 9.13 15.83 5.29"/><line class="cls-1" x1="21.58" y1="12" x2="2.42" y2="12"/></svg>
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