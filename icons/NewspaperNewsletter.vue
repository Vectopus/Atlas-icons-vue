
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,13.91v6.68a1.92,1.92,0,0,1-1.91,1.91,1.93,1.93,0,0,1-1.91-1.91V13.91Z"/><path class="cls-1" d="M20.59,22.5H3.41A1.92,1.92,0,0,1,1.5,20.59V1.5H18.68V20.59a1.93,1.93,0,0,0,1.91,1.91Z"/><rect class="cls-1" x="5.32" y="5.32" width="9.55" height="4.77"/><line class="cls-1" x1="4.36" y1="13.91" x2="8.18" y2="13.91"/><line class="cls-1" x1="4.36" y1="17.73" x2="8.18" y2="17.73"/><rect class="cls-1" x="11.05" y="13.91" width="3.82" height="3.82"/></svg>
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