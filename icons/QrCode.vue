
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="QR_Code" data-name="QR Code"><rect class="cls-1" x="1.5" y="1.5" width="8.59" height="8.59"/><polyline class="cls-1" points="6.27 7.23 4.36 7.23 4.36 4.36 7.23 4.36"/><polyline class="cls-1" points="18.68 5.32 18.68 7.23 16.77 7.23"/><polyline class="cls-1" points="7.23 19.64 4.36 19.64 4.36 17.73"/><polyline class="cls-1" points="22.5 10.09 13.91 10.09 13.91 1.5 22.5 1.5 22.5 10.09"/><rect class="cls-1" x="13.91" y="13.91" width="8.59" height="8.59"/><rect class="cls-1" x="1.5" y="13.91" width="8.59" height="8.59"/><rect class="cls-1" x="16.77" y="16.77" width="1.91" height="1.91"/></g></svg>
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