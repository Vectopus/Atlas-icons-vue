
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="18.68" width="7.64" height="3.82"/><rect class="cls-1" x="8.18" y="14.86" width="7.64" height="3.82"/><rect class="cls-1" x="15.82" y="14.86" width="3.82" height="3.82"/><rect class="cls-1" x="4.36" y="14.86" width="3.82" height="3.82"/><rect class="cls-1" x="12" y="18.68" width="7.64" height="3.82"/><rect class="cls-1" x="4.36" y="11.05" width="7.64" height="3.82"/><rect class="cls-1" x="8.18" y="7.23" width="7.64" height="3.82"/><rect class="cls-1" x="15.82" y="7.23" width="3.82" height="3.82"/><rect class="cls-1" x="4.36" y="7.23" width="3.82" height="3.82"/><rect class="cls-1" x="12" y="11.05" width="7.64" height="3.82"/><rect class="cls-1" x="2.45" y="1.5" width="19.09" height="5.73"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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