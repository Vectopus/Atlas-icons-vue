
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,8.18h3.34a1.43,1.43,0,0,0,1.43-1.43h0a1.43,1.43,0,0,0-1.43-1.43h-1a1.43,1.43,0,0,1-1.43-1.43h0a1.44,1.44,0,0,1,1.43-1.44h3.34"/><line class="cls-1" x1="12" y1="0.55" x2="12" y2="2.45"/><line class="cls-1" x1="12" y1="8.18" x2="12" y2="10.09"/><circle class="cls-1" cx="17.73" cy="14.86" r="2.86"/><path class="cls-1" d="M13,23.45V22.5a4.77,4.77,0,0,1,4.78-4.77h0A4.77,4.77,0,0,1,22.5,22.5v.95"/><circle class="cls-1" cx="6.27" cy="14.86" r="2.86"/><path class="cls-1" d="M1.5,23.45V22.5a4.77,4.77,0,0,1,4.77-4.77h0a4.77,4.77,0,0,1,4.78,4.77v.95"/></svg>
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