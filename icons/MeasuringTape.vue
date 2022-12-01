
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,3.43h0a7.64,7.64,0,0,1,7.64,7.64V18.7a0,0,0,0,1,0,0H3.41A1.91,1.91,0,0,1,1.5,16.8V11.07A7.64,7.64,0,0,1,9.14,3.43Z"/><polyline class="cls-1" points="14.86 18.7 22.5 18.7 22.5 21.57"/><line class="cls-1" x1="17.73" y1="11.07" x2="17.73" y2="15.84"/><circle class="cls-1" cx="9.14" cy="11.07" r="3.82"/></svg>
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