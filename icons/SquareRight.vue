
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="15.83" y="1.46" width="6.71" height="6.71"/><line class="cls-1" x1="12" y1="1.46" x2="0.5" y2="1.46"/><line class="cls-1" x1="12" y1="8.17" x2="0.5" y2="8.17"/><line class="cls-1" x1="0.5" y1="15.83" x2="23.5" y2="15.83"/><line class="cls-1" x1="0.5" y1="22.54" x2="12.96" y2="22.54"/></svg>
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