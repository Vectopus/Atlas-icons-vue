
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,21.55H8.5l2.33.95h7.92a2.86,2.86,0,0,0,2.85-2.59l.88-9.13c0-.14,0-.28,0-.42h0a2.18,2.18,0,0,0-2.18-2.18H15.63l.52-1.09a6.27,6.27,0,0,0,.62-2.73h0A2.86,2.86,0,0,0,13.91,1.5h0A1.9,1.9,0,0,0,12,3.41h0a6,6,0,0,1-1.25,3.66l-2.33,3H6.27"/><rect class="cls-1" x="1.5" y="9.14" width="4.77" height="13.36"/></svg>
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