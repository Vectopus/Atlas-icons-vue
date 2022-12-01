
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="18.68" width="21" height="3.82"/><rect class="cls-1" x="2.45" y="1.5" width="19.09" height="17.18"/><rect class="cls-1" x="6.27" y="5.32" width="11.45" height="13.36"/><line class="cls-1" x1="6.27" y1="12" x2="17.73" y2="12"/><line class="cls-1" x1="12" y1="5.32" x2="12" y2="18.68"/></svg>
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