
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.51,11.35a1.8,1.8,0,0,0-3,0L9.07,13.47H3.21a2,2,0,0,1-2-2V3.69a2,2,0,0,1,2-1.95H20.79a2,2,0,0,1,2,2v7.82a2,2,0,0,1-2,2"/><line class="cls-1" x1="4.18" y1="5.65" x2="6.14" y2="5.65"/><line class="cls-1" x1="4.18" y1="9.56" x2="6.14" y2="9.56"/><circle class="cls-1" cx="15.91" cy="17.37" r="2.93"/><line class="cls-1" x1="15.91" y1="12.49" x2="15.91" y2="14.44"/><line class="cls-1" x1="15.91" y1="20.31" x2="15.91" y2="22.26"/><line class="cls-1" x1="11.68" y1="14.93" x2="13.37" y2="15.91"/><line class="cls-1" x1="18.45" y1="18.84" x2="20.14" y2="19.82"/><line class="cls-1" x1="20.14" y1="14.93" x2="18.45" y2="15.91"/><line class="cls-1" x1="13.37" y1="18.84" x2="11.68" y2="19.82"/></svg>
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