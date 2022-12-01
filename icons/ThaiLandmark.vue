
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="22.5 20.59 1.5 20.59 1.5 19.64 3.41 16.77 20.59 16.77 22.5 19.64 22.5 20.59"/><polygon class="cls-1" points="18.68 16.77 5.32 16.77 5.32 15.82 7.23 12.96 16.77 12.96 18.68 15.82 18.68 16.77"/><rect class="cls-1" x="8.18" y="6.27" width="7.64" height="6.68"/><path class="cls-2" d="M12,9.14h0a1,1,0,0,1,1,1V13a0,0,0,0,1,0,0H11a0,0,0,0,1,0,0V10.09A1,1,0,0,1,12,9.14Z"/><line class="cls-1" x1="6.27" y1="6.27" x2="17.73" y2="6.27"/><line class="cls-1" x1="6.27" y1="3.41" x2="17.73" y2="3.41"/><polygon class="cls-1" points="10.09 12.96 13.91 12.96 14.86 20.59 9.14 20.59 10.09 12.96"/></svg>
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