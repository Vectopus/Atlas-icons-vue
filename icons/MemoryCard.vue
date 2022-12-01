
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,3.41V22.5H3.41V17.73h1V13h-1V8.18L5.32,5.32V1.5H18.68Z"/><line class="cls-1" x1="9.14" y1="1.5" x2="9.14" y2="5.32"/><line class="cls-1" x1="12.95" y1="1.5" x2="12.95" y2="5.32"/><line class="cls-1" x1="16.77" y1="1.5" x2="16.77" y2="5.32"/><line class="cls-1" x1="8.18" y1="17.73" x2="15.82" y2="17.73"/></svg>
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