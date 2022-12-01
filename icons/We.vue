
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.63,8.31C1.2,9,2.48,15.8,4.19,15.8s1.7-2.49,2.56-2.49S7.6,15.8,9.3,15.8s3.17-6.47,2.56-7.49C11,6.89,2.48,6.9,1.63,8.31Z"/><path class="cls-1" d="M17.71,12c-.95.95,0,2.85,2.85,1.9s2.85,2.85-1.9,2.85c-3.81,0-4.76-3.8-4.76-4.75a4.41,4.41,0,0,1,4.76-4.75c2.85,0,4.26,2,3.8,3.8C21.51,14.85,17.71,12,17.71,12Z"/></svg>
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