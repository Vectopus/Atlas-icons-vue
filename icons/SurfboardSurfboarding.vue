
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,1.5s0,8.59-5.73,14.32C10.09,22.5,4.36,22.5,4.36,22.5V19.64H1.5s0-5.73,6.68-12.41C13.91,1.5,22.5,1.5,22.5,1.5Z"/><line class="cls-1" x1="6.27" y1="17.73" x2="9.14" y2="14.86"/><line class="cls-1" x1="22.5" y1="1.5" x2="12" y2="12"/></svg>
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