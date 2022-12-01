
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="5.32" width="21" height="13.36"/><line class="cls-1" x1="15.82" y1="7.23" x2="15.82" y2="14.86"/><line class="cls-1" x1="13.91" y1="15.82" x2="15.82" y2="14.86"/><line class="cls-1" x1="17.73" y1="15.82" x2="15.82" y2="14.86"/><line class="cls-1" x1="15.82" y1="10.09" x2="12" y2="12"/><line class="cls-1" x1="15.82" y1="10.09" x2="19.64" y2="12"/><line class="cls-1" x1="8.18" y1="8.18" x2="10.09" y2="8.18"/><line class="cls-1" x1="8.18" y1="12" x2="10.09" y2="12"/><line class="cls-1" x1="8.18" y1="15.82" x2="10.09" y2="15.82"/></svg>
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