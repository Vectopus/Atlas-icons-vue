
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.73,1.5h0a2.31,2.31,0,0,0-1.63.67L6.27,12v2.86L2.09,19a2,2,0,0,0-.59,1.44h0a2,2,0,0,0,2,2h0A2,2,0,0,0,5,21.91l4.18-4.18H12L21.83,7.9a2.31,2.31,0,0,0,.67-1.63h0a2.33,2.33,0,0,0-.67-1.63L19.36,2.17A2.33,2.33,0,0,0,17.73,1.5Z"/><line class="cls-1" x1="6.27" y1="14.86" x2="9.14" y2="17.73"/><line class="cls-1" x1="7.23" y1="11.05" x2="12.95" y2="16.77"/><circle class="cls-1" cx="4.36" cy="4.36" r="2.86"/></svg>
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