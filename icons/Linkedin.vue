
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="0.5" y="1.48" width="22" height="21.04"/><path class="cls-1" d="M10.07,18.7V12.48a3.34,3.34,0,0,1,3.34-3.35h0a3.35,3.35,0,0,1,3.35,3.35V18.7"/><line class="cls-1" x1="6.24" y1="8.17" x2="6.24" y2="18.7"/><circle class="cls-2" cx="6.24" cy="6.26" r="0.96"/><line class="cls-1" x1="10.07" y1="8.17" x2="10.07" y2="12.96"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>