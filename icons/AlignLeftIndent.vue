
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8" y1="2" x2="8" y2="22"/><polyline class="cls-1" points="1 9 4 12 1 15"/><line class="cls-1" x1="11" y1="3" x2="23" y2="3"/><line class="cls-1" x1="11" y1="9" x2="23" y2="9"/><line class="cls-1" x1="11" y1="15" x2="23" y2="15"/><line class="cls-1" x1="11" y1="21" x2="23" y2="21"/></svg>
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