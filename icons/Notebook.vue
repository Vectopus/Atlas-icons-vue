
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.39" y="2.41" width="17.22" height="20.09"/><line class="cls-1" x1="7.22" y1="0.5" x2="7.22" y2="4.33"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="4.33"/><line class="cls-1" x1="16.78" y1="0.5" x2="16.78" y2="4.33"/><line class="cls-1" x1="6.26" y1="11.02" x2="17.74" y2="11.02"/><line class="cls-1" x1="6.26" y1="7.2" x2="17.74" y2="7.2"/><line class="cls-1" x1="6.26" y1="14.85" x2="17.74" y2="14.85"/><line class="cls-1" x1="6.26" y1="18.67" x2="12" y2="18.67"/></svg>
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