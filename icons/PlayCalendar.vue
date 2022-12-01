
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.11" width="21" height="13.36"/><rect class="cls-1" x="1.5" y="3.39" width="21" height="5.73"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="6.25"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="6.25"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="6.25"/><polygon class="cls-1" points="10.09 17.7 10.09 13.89 13.91 15.79 10.09 17.7"/></svg>
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