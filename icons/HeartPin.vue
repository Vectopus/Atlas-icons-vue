
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.62,9.12a7.62,7.62,0,0,0-15.24,0C4.38,14.83,12,21.5,12,21.5S19.62,14.83,19.62,9.12Z"/><path class="cls-1" d="M13.73,6.26a2.1,2.1,0,0,0-1.73.9,2.1,2.1,0,0,0-1.73-.9,2,2,0,0,0-2.08,2c0,3,3.81,4.67,3.81,4.67s3.81-1.67,3.81-4.67A2,2,0,0,0,13.73,6.26Z"/></svg>
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