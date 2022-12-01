
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="4.77" rx="2.39"/><rect class="cls-1" x="2.45" y="6.27" width="19.09" height="16.23"/><path class="cls-1" d="M12,10.09h0a5.73,5.73,0,0,1,5.73,5.73V22.5a0,0,0,0,1,0,0H6.27a0,0,0,0,1,0,0V15.82A5.73,5.73,0,0,1,12,10.09Z"/><path class="cls-1" d="M14.86,19.64a2.86,2.86,0,0,1-5.72,0c0-1.59,2.86-4.78,2.86-4.78S14.86,18.05,14.86,19.64Z"/><path class="cls-2" d="M13.43,21.07a1.43,1.43,0,0,1-2.86,0c0-.79,1.43-2.39,1.43-2.39S13.43,20.28,13.43,21.07Z"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>