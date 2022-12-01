
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="insurance"><path class="cls-1" d="M12,22.5h0A12.56,12.56,0,0,1,3.41,10.58V5.32L12,1.5l8.59,3.82v5.26A12.56,12.56,0,0,1,12,22.5Z"/><line class="cls-1" x1="8.18" y1="12" x2="15.82" y2="12"/><line class="cls-1" x1="12" y1="8.18" x2="12" y2="15.82"/></g></svg>
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