
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="20.59 7.71 3.41 7.71 10.09 16.61 10.09 22.02 13.91 20.11 13.91 16.61 20.59 7.71"/><line class="cls-1" x1="1.5" y1="7.7" x2="22.5" y2="7.7"/><circle class="cls-1" cx="9.14" cy="4.84" r="2.86"/><path class="cls-1" d="M18.51,7.7a2.71,2.71,0,0,0,.17-1,2.87,2.87,0,0,0-5.73,0,2.51,2.51,0,0,0,.18,1"/></svg>
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