
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.22,22.5h0A4.73,4.73,0,0,1,1.5,17.78h0a4.76,4.76,0,0,1,1.38-3.35L14.43,2.88A4.76,4.76,0,0,1,17.78,1.5h0A4.73,4.73,0,0,1,22.5,6.22h0a4.76,4.76,0,0,1-1.38,3.35L9.57,21.12A4.76,4.76,0,0,1,6.22,22.5Z"/><line class="cls-1" x1="12.95" y1="8.18" x2="15.82" y2="11.05"/><line class="cls-1" x1="8.18" y1="12.95" x2="11.05" y2="15.82"/></svg>
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