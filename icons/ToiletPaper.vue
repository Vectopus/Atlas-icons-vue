
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><ellipse class="cls-1" cx="6.27" cy="9.14" rx="4.77" ry="7.64"/><ellipse class="cls-1" cx="6.27" cy="9.14" rx="0.95" ry="1.91"/><path class="cls-1" d="M6.27,16.77H17.73c2.63,0,4.77-3.41,4.77-7.63S20.36,1.5,17.73,1.5H6.27"/><polyline class="cls-1" points="14.86 16.77 14.86 22.5 1.5 22.5 1.5 10.09"/></svg>
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