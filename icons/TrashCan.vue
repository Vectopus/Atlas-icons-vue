
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="18.68 22.5 5.32 22.5 4.36 9.14 19.64 9.14 18.68 22.5"/><path class="cls-1" d="M15.31,1.5H8.69A3.81,3.81,0,0,0,4.9,4.84l-.54,4.3H19.64l-.54-4.3A3.81,3.81,0,0,0,15.31,1.5Z"/><rect class="cls-1" x="9.14" y="1.5" width="5.73" height="3.82"/><line class="cls-1" x1="21.55" y1="9.14" x2="2.45" y2="9.14"/><line class="cls-1" x1="10.09" y1="18.68" x2="13.91" y2="18.68"/></svg>
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