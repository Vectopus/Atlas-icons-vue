
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="10.09" y="1.5" width="3.82" height="3.82"/><rect class="cls-1" x="1.5" y="1.5" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="1.5" width="3.82" height="3.82"/><rect class="cls-1" x="10.09" y="10.09" width="3.82" height="3.82"/><rect class="cls-1" x="1.5" y="10.09" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="10.09" width="3.82" height="3.82"/><rect class="cls-1" x="10.09" y="18.68" width="3.82" height="3.82"/><rect class="cls-1" x="1.5" y="18.68" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="18.68" width="3.82" height="3.82"/></svg>
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