
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,10.09v1a10.49,10.49,0,0,0,6.68,9.77V22.5h7.64V20.82a10.49,10.49,0,0,0,6.68-9.77v-1Z"/><path class="cls-1" d="M10.09,10.09l7.8-7.8a2.7,2.7,0,0,1,3.82,3.82l-4,4"/></svg>
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