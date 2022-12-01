
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="11.07" y1="3.41" x2="23.5" y2="3.41"/><line class="cls-1" x1="11.07" y1="9.15" x2="23.5" y2="9.15"/><line class="cls-1" x1="11.07" y1="14.89" x2="23.5" y2="14.89"/><line class="cls-1" x1="11.07" y1="20.63" x2="23.5" y2="20.63"/><polyline class="cls-1" points="1.5 7.24 5.33 3.41 9.15 7.24"/><line class="cls-1" x1="5.33" y1="21.59" x2="5.33" y2="3.41"/></svg>
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