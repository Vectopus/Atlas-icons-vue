
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,12A10.5,10.5,0,1,1,12,1.5,10.5,10.5,0,0,1,22.5,12Z"/><path class="cls-1" d="M1.58,13.26a13.69,13.69,0,0,0,7.72-4,13.69,13.69,0,0,0,4-7.72"/><path class="cls-1" d="M10.74,22.42A14.16,14.16,0,0,1,22.42,10.74"/><line class="cls-1" x1="13.35" y1="13.35" x2="16.05" y2="16.05"/><line class="cls-1" x1="18.07" y1="9.98" x2="19.42" y2="14.02"/><line class="cls-1" x1="9.98" y1="18.07" x2="14.02" y2="19.42"/><line class="cls-1" x1="10.65" y1="10.65" x2="7.95" y2="7.95"/><line class="cls-1" x1="5.93" y1="14.02" x2="4.58" y2="9.98"/><line class="cls-1" x1="14.02" y1="5.93" x2="9.98" y2="4.58"/></svg>
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