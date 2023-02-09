
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.11" cy="10.57" r="2.39"/><path class="cls-1" d="M1.5,22.5H3.41l3.82-7.64.17-1A5.63,5.63,0,0,1,13,9.14h2.87V13H13a1.91,1.91,0,0,0-1.9,1.91h0l2.86,7.64h1.91"/><polyline class="cls-1" points="15.82 12.96 15.82 17.73 17.73 21.55"/><polyline class="cls-1" points="15.82 9.14 15.82 5.32 18.68 1.5"/></svg>
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