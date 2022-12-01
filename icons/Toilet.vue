
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.43" y="1.5" width="6.68" height="10.5" rx="1.91"/><path class="cls-1" d="M5.34,12V22.5h9.55l-1-3.82h0A6.68,6.68,0,0,0,20.61,12H5.34Z"/><line class="cls-1" x1="10.11" y1="9.14" x2="21.57" y2="9.14"/></svg>
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