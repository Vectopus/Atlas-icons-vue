
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.3,10.53a7.51,7.51,0,0,0,.38-2.43,4.68,4.68,0,0,0-8.59-2.59A4.68,4.68,0,0,0,1.5,8.1c0,7,8.59,9.37,8.59,9.37s.4-.11,1-.35"/><path class="cls-1" d="M19.12,10.44A3.37,3.37,0,0,0,16.3,12a3.39,3.39,0,0,0-6.21,1.87c0,5.08,6.21,6.77,6.21,6.77s6.2-1.69,6.2-6.77A3.38,3.38,0,0,0,19.12,10.44Z"/></svg>
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