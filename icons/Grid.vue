
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><line class="cls-1" x1="0.47" y1="4.34" x2="23.49" y2="4.34"/><line class="cls-1" x1="0.47" y1="12.01" x2="23.49" y2="12.01"/><line class="cls-1" x1="0.47" y1="19.68" x2="23.49" y2="19.68"/><line class="cls-1" x1="19.66" y1="0.5" x2="19.66" y2="23.52"/><line class="cls-1" x1="11.98" y1="0.5" x2="11.98" y2="23.52"/><line class="cls-1" x1="4.31" y1="0.5" x2="4.31" y2="23.52"/></g></svg>
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