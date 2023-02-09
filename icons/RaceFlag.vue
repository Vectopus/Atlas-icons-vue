
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.43" y="1.5" width="19.13" height="14.35"/><rect class="cls-1" x="7.22" y="1.5" width="9.57" height="14.35"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="15.85"/><line class="cls-1" x1="2.43" y1="6.28" x2="21.57" y2="6.28"/><line class="cls-1" x1="2.43" y1="11.07" x2="21.57" y2="11.07"/><line class="cls-1" x1="2.43" y1="23.5" x2="2.43" y2="15.85"/></svg>
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