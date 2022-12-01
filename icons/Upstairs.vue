
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="18.68" width="9.55" height="3.82"/><rect class="cls-1" x="5.32" y="14.86" width="9.55" height="3.82"/><rect class="cls-1" x="9.14" y="11.05" width="9.55" height="3.82"/><polygon class="cls-1" points="22.5 11.04 22.5 22.5 11.04 22.5 11.04 18.68 14.86 18.68 14.86 14.86 18.68 14.86 18.68 11.04 22.5 11.04"/><polyline class="cls-1" points="6.27 1.5 11.04 1.5 11.04 6.27"/><line class="cls-1" x1="11.05" y1="1.5" x2="1.5" y2="11.05"/></svg>
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