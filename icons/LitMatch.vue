
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21,10.75a6,6,0,0,1-12,0c0-5,4-5,5-9C17,2.75,21,6.75,21,10.75Z"/><ellipse class="cls-1" cx="15" cy="12" rx="2.83" ry="2.12" transform="translate(-4.09 14.12) rotate(-45)"/><line class="cls-1" x1="13" y1="14" x2="4" y2="23"/></svg>
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