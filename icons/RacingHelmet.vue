
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,13.52v-.94A11.33,11.33,0,0,1,3.41,6.27h0L1.5,4.36v-1C3,2.57,7.27,1.5,12,1.5c6.68,0,10.5,3.82,10.5,8.59v7.44a5,5,0,0,1-5,5h0a5,5,0,0,1-1.48-.23L5.52,19A5.72,5.72,0,0,1,1.5,13.52Z"/><path class="cls-1" d="M22.5,18.68h0a15,15,0,0,1-8.66-2.77l-1.62-1.16a2.81,2.81,0,0,1-1.17-2.29h0a2.82,2.82,0,0,1,3.27-2.78l8.18,1.37"/><line class="cls-1" x1="15.82" y1="10.09" x2="13.91" y2="15.82"/></svg>
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