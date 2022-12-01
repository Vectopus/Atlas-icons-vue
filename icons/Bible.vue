
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,18.68V22.5H5.32a1.91,1.91,0,0,1-1.91-1.91,1.92,1.92,0,0,1,1.91-1.91Z"/><path class="cls-1" d="M20.59,1.5V18.68H5.32a1.92,1.92,0,0,0-1.91,1.91V3.41A1.92,1.92,0,0,1,5.32,1.5Z"/><line class="cls-1" x1="7.23" y1="1.5" x2="7.23" y2="18.68"/><line class="cls-1" x1="11.05" y1="9.14" x2="16.77" y2="9.14"/><line class="cls-1" x1="13.91" y1="6.27" x2="13.91" y2="13.91"/></svg>
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