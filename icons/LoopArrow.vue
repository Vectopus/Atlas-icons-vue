
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,12H6.75A5.25,5.25,0,0,1,1.5,6.75h0A5.25,5.25,0,0,1,6.75,1.5h0A5.25,5.25,0,0,1,12,6.75V9.14"/><path class="cls-1" d="M12,12h5.25a5.25,5.25,0,0,1,5.25,5.25h0a5.25,5.25,0,0,1-5.25,5.25h0A5.25,5.25,0,0,1,12,17.25V13.91"/><polyline class="cls-1" points="14.86 6.27 12 9.14 9.14 6.27"/></svg>
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