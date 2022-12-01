
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,3.41A5.73,5.73,0,0,0,12,6,5.73,5.73,0,0,0,1.5,9.14C1.5,17.73,12,20.59,12,20.59S22.5,17.73,22.5,9.14A5.72,5.72,0,0,0,16.77,3.41Z"/><path class="cls-1" d="M16.77,7.23a1.9,1.9,0,0,1,1.91,1.91,6.25,6.25,0,0,1-1.95,4.43"/></svg>
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