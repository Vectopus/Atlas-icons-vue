
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="11.45" height="17.18" rx="1.91"/><line class="cls-1" x1="6.27" y1="15.82" x2="8.18" y2="15.82"/><path class="cls-1" d="M7.23,18.68h0a3.82,3.82,0,0,0,3.82,3.82h4.77a3.82,3.82,0,0,0,3.82-3.82V9.14"/><path class="cls-1" d="M16.77,5.32H22.5a0,0,0,0,1,0,0V7.23a1.91,1.91,0,0,1-1.91,1.91H18.68a1.91,1.91,0,0,1-1.91-1.91V5.32A0,0,0,0,1,16.77,5.32Z"/><rect class="cls-1" x="17.73" y="1.5" width="3.82" height="3.82"/><polyline class="cls-1" points="8.18 5.32 6.27 9.14 8.18 9.14 6.27 12.96"/></svg>
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