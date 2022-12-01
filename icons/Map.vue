
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="14.86 2.46 9.14 6.27 1.5 6.27 1.5 21.55 9.14 21.55 14.86 17.73 22.5 17.73 22.5 2.46 14.86 2.46"/><line class="cls-1" x1="9.14" y1="6.27" x2="9.14" y2="21.55"/><line class="cls-1" x1="14.86" y1="2.45" x2="14.86" y2="17.73"/></svg>
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