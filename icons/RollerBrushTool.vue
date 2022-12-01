
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.43" y="1.46" width="17.26" height="7.67" rx="1.92"/><path class="cls-1" d="M18.69,5.3h3.84V12H12.94A1.92,1.92,0,0,0,11,13.93v1"/><path class="cls-1" d="M9.1,14.89h3.84a0,0,0,0,1,0,0v5.75A1.92,1.92,0,0,1,11,22.56h0A1.92,1.92,0,0,1,9.1,20.64V14.89a0,0,0,0,1,0,0Z"/></g></svg>
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