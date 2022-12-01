
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="9.11" y="12.02" width="11.48" height="3.83"/><rect class="cls-1" x="10.07" y="1.5" width="9.57" height="5.74"/><polyline class="cls-1" points="11.02 23.5 11.02 15.85 18.67 15.85 18.67 23.5"/><polyline class="cls-1" points="11.98 12.98 11.98 7.24 17.72 7.24 17.72 12.98"/><polyline class="cls-1" points="11.98 15.85 4.33 15.85 4.33 9.15"/><line class="cls-1" x1="2.41" y1="9.15" x2="8.15" y2="9.15"/></svg>
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