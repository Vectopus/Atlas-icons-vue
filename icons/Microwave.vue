
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.43" width="21" height="15.27"/><line class="cls-1" x1="18.68" y1="8.25" x2="20.59" y2="8.25"/><line class="cls-1" x1="18.68" y1="12.07" x2="20.59" y2="12.07"/><line class="cls-1" x1="18.68" y1="15.89" x2="20.59" y2="15.89"/><line class="cls-1" x1="16.77" y1="5.39" x2="16.77" y2="19.7"/><line class="cls-1" x1="20.59" y1="22.57" x2="20.59" y2="19.7"/><line class="cls-1" x1="3.41" y1="22.57" x2="3.41" y2="19.7"/><rect class="cls-1" x="4.36" y="8.25" width="9.55" height="7.64"/></svg>
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