
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.39" y="1.5" width="18.14" height="21"/><line class="cls-1" x1="1.48" y1="6.27" x2="5.3" y2="6.27"/><line class="cls-1" x1="1.48" y1="13.91" x2="5.3" y2="13.91"/><line class="cls-1" x1="1.48" y1="10.09" x2="5.3" y2="10.09"/><line class="cls-1" x1="1.48" y1="17.73" x2="5.3" y2="17.73"/><rect class="cls-1" x="8.16" y="6.27" width="9.55" height="3.82"/><line class="cls-1" x1="7.2" y1="13.91" x2="18.66" y2="13.91"/></svg>
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