
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,22.5H14.86L2.22,10.76A2.25,2.25,0,0,1,1.5,9.11h0a2.28,2.28,0,0,1,.66-1.59L7.79,1.9a1.31,1.31,0,0,1,1-.4h0a1.34,1.34,0,0,1,1.35,1.35h0a1.31,1.31,0,0,0,.4.95l.79.8a5.73,5.73,0,0,0,4.05,1.67h1.44l1.45,5.08a2.91,2.91,0,0,0,2.09,2h0a2.89,2.89,0,0,1,2.19,2.81v4.42A1.9,1.9,0,0,1,20.59,22.5Z"/><polyline class="cls-1" points="22.5 18.68 16.77 18.68 3.41 6.27"/><line class="cls-1" x1="16.77" y1="5.32" x2="16.77" y2="3.41"/><line class="cls-1" x1="14.86" y1="9.14" x2="17.73" y2="9.14"/><line class="cls-1" x1="15.82" y1="12.95" x2="19.64" y2="12.95"/></svg>
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