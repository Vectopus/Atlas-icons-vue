
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><rect class="cls-1" x="6.27" y="6.27" width="11.45" height="11.45"/><line class="cls-1" x1="8.18" y1="4.36" x2="8.18" y2="6.27"/><line class="cls-1" x1="8.18" y1="19.64" x2="8.18" y2="17.73"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="6.27"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="17.73"/><line class="cls-1" x1="15.82" y1="4.36" x2="15.82" y2="6.27"/><line class="cls-1" x1="15.82" y1="19.64" x2="15.82" y2="17.73"/><line class="cls-1" x1="4.36" y1="15.82" x2="6.27" y2="15.82"/><line class="cls-1" x1="19.64" y1="15.82" x2="17.73" y2="15.82"/><line class="cls-1" x1="4.36" y1="12" x2="6.27" y2="12"/><line class="cls-1" x1="19.64" y1="12" x2="17.73" y2="12"/><line class="cls-1" x1="4.36" y1="8.18" x2="6.27" y2="8.18"/><line class="cls-1" x1="19.64" y1="8.18" x2="17.73" y2="8.18"/></svg>
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