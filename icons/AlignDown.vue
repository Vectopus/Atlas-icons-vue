
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="2.42" x2="23.5" y2="2.42"/><line class="cls-1" x1="0.5" y1="10.08" x2="14.88" y2="10.08"/><line class="cls-1" x1="0.5" y1="17.75" x2="9.13" y2="17.75"/><line class="cls-1" x1="18.71" y1="9.13" x2="18.71" y2="20.63"/><polyline class="cls-1" points="22.54 17.75 18.71 21.58 14.88 17.75"/></svg>
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