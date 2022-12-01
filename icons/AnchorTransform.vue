
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.46" y="15.84" width="3.84" height="3.84"/><rect class="cls-1" x="18.72" y="15.84" width="3.84" height="3.84"/><rect class="cls-1" x="10.09" y="4.33" width="3.84" height="3.84"/><circle class="cls-1" cx="2.42" cy="6.25" r="0.96"/><circle class="cls-1" cx="21.6" cy="6.25" r="0.96"/><line class="cls-1" x1="10.09" y1="6.25" x2="3.38" y2="6.25"/><line class="cls-1" x1="13.93" y1="6.25" x2="20.64" y2="6.25"/><path class="cls-1" d="M13.93,6.25l.54.23a10.2,10.2,0,0,1,6.17,9.36h0"/><path class="cls-1" d="M10.09,6.25l-.54.23a10.18,10.18,0,0,0-6.17,9.36h0"/></g></svg>
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