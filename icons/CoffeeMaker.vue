
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,1.5H5.32A3.82,3.82,0,0,0,1.5,5.32V7.23H14.86V18.68H1.5V22.5h21V5.32A3.82,3.82,0,0,0,18.68,1.5Z"/><path class="cls-1" d="M3.41,12H11a0,0,0,0,1,0,0v3.38a3.31,3.31,0,0,1-3.31,3.31h-1a3.31,3.31,0,0,1-3.31-3.31V12A0,0,0,0,1,3.41,12Z"/><line class="cls-1" x1="7.23" y1="9.14" x2="7.23" y2="7.23"/><line class="cls-1" x1="17.73" y1="18.68" x2="19.64" y2="18.68"/><line class="cls-1" x1="17.73" y1="14.86" x2="19.64" y2="14.86"/><line class="cls-1" x1="17.73" y1="11.05" x2="19.64" y2="11.05"/></svg>
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