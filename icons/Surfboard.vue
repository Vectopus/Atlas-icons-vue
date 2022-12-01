
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5,21l.43-1A1.09,1.09,0,0,0,4,18.54L3,19a1.08,1.08,0,0,1-1.48-1.29C2.3,15.17,4.13,12.19,7.3,9c5.51-5.51,12.46-9,14.58-6.91S20.48,11.19,15,16.7c-3.16,3.17-6.14,5-8.65,5.75A1.08,1.08,0,0,1,5,21Z"/><line class="cls-1" x1="18.81" y1="5.19" x2="8.06" y2="15.94"/></svg>
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