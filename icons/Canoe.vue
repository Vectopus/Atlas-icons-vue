
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,1.5h0a0,0,0,0,1,0,0v0a21,21,0,0,1-21,21h0a0,0,0,0,1,0,0v0A21,21,0,0,1,22.5,1.5Z"/><ellipse class="cls-1" cx="12" cy="12" rx="4.72" ry="2.7" transform="translate(-4.97 12) rotate(-45)"/><polygon class="cls-1" points="5.32 4.17 5.32 5.32 4.17 5.32 1.88 3.03 3.03 1.88 5.32 4.17"/><polygon class="cls-1" points="18.68 19.83 18.68 18.68 19.83 18.68 22.12 20.97 20.97 22.12 18.68 19.83"/><line class="cls-1" x1="5.32" y1="5.32" x2="18.68" y2="18.68"/></svg>
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