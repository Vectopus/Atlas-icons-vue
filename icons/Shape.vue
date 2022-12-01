
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M22.53,4.33V19.68A31.08,31.08,0,0,0,12,17.76,31.08,31.08,0,0,0,1.43,19.68V4.33A31.08,31.08,0,0,0,12,6.25,31.08,31.08,0,0,0,22.53,4.33Z"/></g></svg>
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