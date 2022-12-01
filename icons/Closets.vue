
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.43" y="1.5" width="9.57" height="20.09"/><rect class="cls-1" x="12" y="1.5" width="9.57" height="20.09"/><line class="cls-1" x1="4.35" y1="23.5" x2="4.35" y2="21.59"/><line class="cls-1" x1="19.65" y1="23.5" x2="19.65" y2="21.59"/><line class="cls-1" x1="8.17" y1="11.07" x2="8.17" y2="12.98"/><line class="cls-1" x1="15.83" y1="11.07" x2="15.83" y2="12.98"/></svg>
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