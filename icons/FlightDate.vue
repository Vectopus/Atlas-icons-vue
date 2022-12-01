
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.11" width="21" height="13.36"/><rect class="cls-1" x="1.5" y="3.39" width="21" height="5.73"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="6.25"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="6.25"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="6.25"/><line class="cls-1" x1="12" y1="11.02" x2="12" y2="18.66"/><line class="cls-1" x1="10.09" y1="19.61" x2="12" y2="18.66"/><line class="cls-1" x1="13.91" y1="19.61" x2="12" y2="18.66"/><line class="cls-1" x1="12" y1="13.89" x2="8.18" y2="15.8"/><line class="cls-1" x1="12" y1="13.89" x2="15.82" y2="15.8"/></svg>
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