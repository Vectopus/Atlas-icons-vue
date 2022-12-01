
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.4" y="1.49" width="21.1" height="7.67"/><rect class="cls-1" x="1.4" y="14.91" width="21.1" height="7.67"/><line class="cls-1" x1="11.95" y1="14.91" x2="11.95" y2="9.16"/><line class="cls-1" x1="5.24" y1="4.36" x2="5.24" y2="6.28"/><line class="cls-1" x1="9.07" y1="4.36" x2="9.07" y2="6.28"/><line class="cls-1" x1="5.24" y1="17.79" x2="5.24" y2="19.71"/><line class="cls-1" x1="9.07" y1="17.79" x2="9.07" y2="19.71"/><line class="cls-1" x1="19.62" y1="5.32" x2="15.79" y2="5.32"/><line class="cls-1" x1="19.62" y1="18.75" x2="15.79" y2="18.75"/></g></svg>
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