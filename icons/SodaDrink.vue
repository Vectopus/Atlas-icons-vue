
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,14.86C12,16.77,12,12,7.23,14.86"/><line class="cls-1" x1="4.36" y1="9.14" x2="19.64" y2="9.14"/><path class="cls-1" d="M13,5.32V3.41a1.9,1.9,0,0,0-1.9-1.91H7.23"/><polygon class="cls-1" points="16.77 5.32 7.23 5.32 6.27 9.14 8.18 22.5 15.82 22.5 17.73 9.14 16.77 5.32"/></svg>
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