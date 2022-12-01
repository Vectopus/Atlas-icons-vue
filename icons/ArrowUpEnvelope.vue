
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="8.18 6.29 12 2.48 15.82 6.29"/><line class="cls-1" x1="12" y1="12.02" x2="12" y2="2.48"/><polyline class="cls-1" points="18.59 7.25 22.5 7.25 22.5 22.52 1.5 22.52 1.5 7.25 5.41 7.25"/><polyline class="cls-1" points="1.5 7.25 12 17.75 22.5 7.25"/><line class="cls-1" x1="9.14" y1="14.89" x2="1.5" y2="22.52"/><line class="cls-1" x1="22.5" y1="22.52" x2="14.86" y2="14.89"/><polyline class="cls-1" points="18.59 7.25 22.5 7.25 22.5 22.52 1.5 22.52 1.5 7.25 5.41 7.25"/></svg>
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