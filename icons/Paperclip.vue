
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.72,6.22,7,14.08A2.7,2.7,0,0,0,6.25,16h0A2.7,2.7,0,0,0,9,18.68H9a2.69,2.69,0,0,0,1.91-.79l8.32-8.32a4.73,4.73,0,0,0,1.39-3.35h0A4.73,4.73,0,0,0,15.84,1.5h0A4.76,4.76,0,0,0,12.5,2.88L4.41,11a6.72,6.72,0,0,0-2,4.77h0A6.75,6.75,0,0,0,9.18,22.5h0a6.72,6.72,0,0,0,4.77-2l6.62-6.61"/></svg>
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