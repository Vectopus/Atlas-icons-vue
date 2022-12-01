
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.84,21.16h0A8,8,0,0,1,4.34,12L7,9.32a3.63,3.63,0,0,1,5.14,0l2.57,2.57a3.63,3.63,0,0,1,0,5.14l-2.63,2.63A8,8,0,0,1,2.84,21.16Z"/><line class="cls-1" x1="10.56" y1="21.16" x2="2.84" y2="13.44"/><line class="cls-1" x1="5.41" y1="10.87" x2="13.13" y2="18.59"/><polygon class="cls-1" points="18.36 12 13.82 10.18 12 5.64 15.57 2 15.84 2.62 17.5 6.5 22 8.43 18.36 12"/></svg>
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