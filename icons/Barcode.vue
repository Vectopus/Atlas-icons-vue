
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="barcode"><rect class="cls-1" x="1.5" y="4" width="3" height="12"/><rect class="cls-1" x="13.5" y="4" width="3" height="16"/><polygon class="cls-1" points="7.5 21 7.5 20 7.5 3 7.5 4 7.5 21"/><line class="cls-1" x1="10.5" y1="4" x2="10.5" y2="16"/><path class="cls-1" d="M19.5,10v0Z"/><line class="cls-1" x1="22.5" y1="4" x2="22.5" y2="20"/></g></svg>
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