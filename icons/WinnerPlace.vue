
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="8.17" y="12.93" width="7.65" height="9.57"/><rect class="cls-1" x="15.83" y="16.76" width="6.7" height="5.74"/><rect class="cls-1" x="1.48" y="18.67" width="6.7" height="3.83"/><circle class="cls-1" cx="12" cy="3.37" r="1.91"/><polyline class="cls-1" points="9.13 11.02 9.13 7.2 14.87 7.2 14.87 11.02"/><polyline class="cls-1" points="14.87 7.2 15.83 7.2 17.74 5.28 17.74 0.5"/><polyline class="cls-1" points="9.13 7.2 8.17 7.2 6.26 5.28 6.26 0.5"/></svg>
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