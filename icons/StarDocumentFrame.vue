
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 10.09 12.6 11.35 13.95 11.55 12.97 12.53 13.2 13.91 12 13.26 10.8 13.91 11.03 12.53 10.05 11.55 11.4 11.35 12 10.09"/><line class="cls-1" x1="8.18" y1="18.68" x2="15.82" y2="18.68"/><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="21"/><path class="cls-1" d="M8.18,6.27A8.73,8.73,0,0,1,12,5.32a8.73,8.73,0,0,1,3.82.95"/></svg>
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