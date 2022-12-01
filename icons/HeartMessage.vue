
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.53,11.09A1.93,1.93,0,0,0,13.6,9.15,1.89,1.89,0,0,0,12,10a1.89,1.89,0,0,0-1.6-.87,1.93,1.93,0,0,0-1.93,1.94c0,2.26,3.53,3.55,3.53,3.55S15.53,13.35,15.53,11.09Z"/><path class="cls-2" d="M21.5,12A9.5,9.5,0,1,0,12,21.5h9.5l-2.66-2.92A9.43,9.43,0,0,0,21.5,12Z"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>