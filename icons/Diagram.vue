
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="diagram_conncection" data-name="diagram conncection"><rect class="cls-1" x="1.5" y="9.14" width="5.73" height="5.73" rx="2.86"/><rect class="cls-1" x="18.68" y="1.5" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="10.09" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="18.68" width="3.82" height="3.82"/><polyline class="cls-1" points="18.68 20.59 12.96 20.59 12.96 3.41 18.68 3.41"/><line class="cls-1" x1="18.68" y1="12" x2="7.23" y2="12"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>