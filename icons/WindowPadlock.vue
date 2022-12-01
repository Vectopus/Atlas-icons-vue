
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="14.86 19.64 1.5 19.64 1.5 1.5 20.59 1.5 20.59 12.96"/><line class="cls-1" x1="1.5" y1="7.23" x2="20.59" y2="7.23"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="8.18" y1="4.36" x2="10.09" y2="4.36"/><rect class="cls-1" x="16.77" y="18.68" width="5.73" height="3.82"/><path class="cls-1" d="M19.64,14.86h0a1.91,1.91,0,0,1,1.91,1.91v1.91a0,0,0,0,1,0,0H17.73a0,0,0,0,1,0,0V16.77A1.91,1.91,0,0,1,19.64,14.86Z"/></svg>
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