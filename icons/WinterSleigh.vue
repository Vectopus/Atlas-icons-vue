
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.11,9.13h0A4.78,4.78,0,0,0,4.33,4.35H1.46v5.74A5.74,5.74,0,0,0,7.2,15.83h8.6A4.79,4.79,0,0,0,20.59,11H11A1.91,1.91,0,0,1,9.11,9.13Z"/><path class="cls-1" d="M.5,19.65H18.67a3.82,3.82,0,0,0,3.83-3.82h0"/><line class="cls-1" x1="5.28" y1="15.83" x2="5.28" y2="19.65"/><line class="cls-1" x1="14.85" y1="15.83" x2="14.85" y2="19.65"/></svg>
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