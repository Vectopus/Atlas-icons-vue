
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M23.5,17.74H20.63l-.18.09a17.26,17.26,0,0,1-7.73,1.82h0A1.91,1.91,0,0,1,10.83,18L10.11,13H3.41a1.92,1.92,0,0,1-1.9-2.09,2,2,0,0,1,2-1.74H13.93L12.61,7.81a2,2,0,0,1,0-2.87,2.07,2.07,0,0,1,1.44-.59,2,2,0,0,1,1.43.59l5.15,5.15H23.5"/></svg>
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