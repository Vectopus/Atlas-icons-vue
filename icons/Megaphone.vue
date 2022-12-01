
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="8.18" x2="1.5" y2="15.82"/><line class="cls-1" x1="22.5" y1="2.45" x2="22.5" y2="21.55"/><polygon class="cls-1" points="22.5 4.36 22.5 19.64 12 16.3 4.36 14.56 1.5 13.91 1.5 10.09 22.5 4.36"/><path class="cls-1" d="M12,16.3v1.43a1.92,1.92,0,0,1-1.91,1.91H6.27a1.92,1.92,0,0,1-1.91-1.91V14.56"/></svg>
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