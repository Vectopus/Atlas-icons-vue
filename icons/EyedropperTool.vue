
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M4.44,20.8l-1.15.78-.9-.9.77-1.15,1.41-4,13.3-13.3a2.71,2.71,0,0,1,1.92-.79h0A2.71,2.71,0,0,1,22.5,4.18h0a2.75,2.75,0,0,1-.79,1.92L8.41,19.4Z"/><line class="cls-1" x1="11.27" y1="5.91" x2="18.05" y2="12.7"/></g></svg>
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