
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="14.89 18.7 14.89 22.52 1.5 22.52 1.5 5.3 14.89 5.3 14.89 9.13"/><rect class="cls-1" x="4.37" y="1.48" width="7.65" height="3.83"/><polyline class="cls-1" points="23.5 18.7 8.2 18.7 8.2 9.13 23.5 9.13"/><line class="cls-1" x1="8.2" y1="7.22" x2="8.2" y2="20.61"/><line class="cls-1" x1="12.02" y1="11.04" x2="12.02" y2="9.13"/><line class="cls-1" x1="15.85" y1="11.04" x2="15.85" y2="9.13"/><line class="cls-1" x1="19.67" y1="11.04" x2="19.67" y2="9.13"/><line class="cls-1" x1="12.02" y1="18.7" x2="12.02" y2="16.78"/><line class="cls-1" x1="15.85" y1="18.7" x2="15.85" y2="16.78"/><line class="cls-1" x1="19.67" y1="18.7" x2="19.67" y2="16.78"/></svg>
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