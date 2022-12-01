
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="18.68" width="8.59" height="3.82"/><rect class="cls-1" x="13.91" y="18.68" width="8.59" height="3.82"/><polyline class="cls-1" points="9.14 13.91 9.14 18.68 2.46 18.68 3.41 5.32 9.14 5.32 9.14 10.09"/><polyline class="cls-1" points="14.86 13.91 14.86 18.68 21.55 18.68 20.59 5.32 14.86 5.32 14.86 10.09"/><rect class="cls-1" x="4.36" y="1.5" width="3.82" height="3.82"/><rect class="cls-1" x="15.82" y="1.5" width="3.82" height="3.82"/><line class="cls-1" x1="2.45" y1="1.5" x2="10.09" y2="1.5"/><line class="cls-1" x1="13.91" y1="1.5" x2="21.55" y2="1.5"/><rect class="cls-1" x="7.23" y="10.09" width="9.55" height="3.82"/></svg>
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