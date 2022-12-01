
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.91,14a2.05,2.05,0,0,0-2.08-2,2.1,2.1,0,0,0-1.74.9A2.1,2.1,0,0,0,8.36,12a2.06,2.06,0,0,0-2.09,2c0,2.36,3.82,3.71,3.82,3.71S13.91,16.38,13.91,14Z"/><path class="cls-2" d="M20.59,22.5H3.41A1.92,1.92,0,0,1,1.5,20.59V7.23H18.68V20.59A1.92,1.92,0,0,0,20.59,22.5Z"/><path class="cls-2" d="M22.5,3.41V20.59a1.91,1.91,0,0,1-3.82,0V7.23H5.32V1.5h9.54l1.87,1.91Z"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>