
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.29" y="2.42" width="13.42" height="13.42"/><line class="cls-1" x1="3.38" y1="15.83" x2="20.63" y2="15.83"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><polyline class="cls-1" points="6.25 23.5 9.13 15.83 14.88 15.83 17.75 23.5"/><line class="cls-1" x1="7.21" y1="19.67" x2="15.83" y2="19.67"/></svg>
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