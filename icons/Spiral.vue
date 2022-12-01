
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M1.45,15.29A11.73,11.73,0,0,1,13.17,3.56a9.38,9.38,0,0,1,9.38,9.38,7.5,7.5,0,0,1-7.5,7.5,6,6,0,0,1-6-6,4.8,4.8,0,0,1,4.8-4.8,3.84,3.84,0,0,1,3.84,3.84,3.07,3.07,0,0,1-3.07,3.07,2.46,2.46,0,0,1-2.46-2.45,2,2,0,0,1,2-2A1.57,1.57,0,0,1,15.7,13.7"/></g></svg>
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