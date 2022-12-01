
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="yen"><line class="cls-1" x1="12" y1="22.5" x2="12" y2="12.95"/><line class="cls-1" x1="7.23" y1="12.95" x2="16.77" y2="12.95"/><line class="cls-1" x1="7.23" y1="16.77" x2="16.77" y2="16.77"/><polyline class="cls-1" points="5.32 1.5 5.32 3.41 12 12.96 18.68 3.41 18.68 1.5"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>