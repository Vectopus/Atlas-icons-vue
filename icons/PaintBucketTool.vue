
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M21.57,14.89h0a2.32,2.32,0,0,1-.68,1.64l-5.36,5.36a2.32,2.32,0,0,1-1.64.68h0a2.32,2.32,0,0,1-1.63-.68L2.87,12.5,11.5,3.87l9.39,9.39A2.32,2.32,0,0,1,21.57,14.89Z"/><line class="cls-1" x1="11.02" y1="9.14" x2="18.69" y2="1.47"/><line class="cls-1" x1="12.94" y1="2.43" x2="1.43" y2="13.94"/></g></svg>
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