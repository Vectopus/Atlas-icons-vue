
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.5,22.52a11.65,11.65,0,0,0,4.78-.95,21,21,0,0,0,5.74.95c2.87,0,10.52-.95,10.52-.95l1-1V14.87c0-4.78-2.87-13.39-2.87-13.39H14.85L12.93,3.39V5.3l1.92,1.92h1.91"/><path class="cls-1" d="M16.76,4.35V8.17a26.41,26.41,0,0,0-1,7.66A5.12,5.12,0,0,0,11,11,7.29,7.29,0,0,0,6.24,13,8.35,8.35,0,0,0,.5,11"/></svg>
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