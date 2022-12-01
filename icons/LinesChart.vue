
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 22.5 1.5 22.5 1.5 0.5"/><line class="cls-1" x1="13.93" y1="5.28" x2="4.37" y2="5.28"/><line class="cls-1" x1="21.59" y1="11.02" x2="4.37" y2="11.02"/><line class="cls-1" x1="17.76" y1="16.76" x2="4.37" y2="16.76"/></svg>
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