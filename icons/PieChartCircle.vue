
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,13.05A4.87,4.87,0,1,1,11,8.18,4.86,4.86,0,0,1,15.82,13.05Z"/><path class="cls-1" d="M11.05,3.41A9.54,9.54,0,1,0,20.59,13"/><path class="cls-1" d="M15.81,13H22.5A11.45,11.45,0,0,0,11.05,1.5V8.19"/><line class="cls-1" x1="17.79" y1="19.7" x2="14.49" y2="16.4"/></svg>
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