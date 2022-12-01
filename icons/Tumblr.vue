
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.21,1.79h4.65V7.36H18.5v3.71H13.86v4.25a2.25,2.25,0,0,0,2.25,2.25h0a2.21,2.21,0,0,0,1-.24l1.38-.69v3.72l-1.35.9a5.74,5.74,0,0,1-3.16.95h0a5.7,5.7,0,0,1-5.7-5.7V11.07H5.5V7.36h0A4.91,4.91,0,0,0,9.21,2.6Z"/></svg>
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