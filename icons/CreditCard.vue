
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="creadit_card" data-name="creadit card"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/><rect class="cls-1" x="1.5" y="8.18" width="21" height="3.82"/><path class="cls-1" d="M18.68,15.82h0Z"/></g></svg>
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