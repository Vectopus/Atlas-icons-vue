
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.11,22.5H7.25V13L5.4,4.64a2.6,2.6,0,0,1-.06-.56h0A2.59,2.59,0,0,1,7.92,1.5H8a2.56,2.56,0,0,1,2,.93L12.1,5a7.92,7.92,0,0,1,1.83,5.06h0V12l3.82,10.5h1.91"/><path class="cls-1" d="M5.34,2.45,8.89,6.72a5.25,5.25,0,0,1,1.22,3.37h0A1.91,1.91,0,0,0,12,12h0a1.9,1.9,0,0,0,1.91-1.91"/><circle class="cls-1" cx="13.45" cy="16.3" r="2.39"/></svg>
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