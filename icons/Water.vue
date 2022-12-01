
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.5,3.4c1.92,0,1.92.95,3.83.95S6.25,3.4,8.16,3.4s1.92.95,3.83.95,1.92-.95,3.83-.95,1.92.95,3.84.95,1.92-.95,3.84-.95"/><path class="cls-1" d="M.5,9.15c1.92,0,1.92.95,3.83.95s1.92-.95,3.83-.95,1.92.95,3.83.95,1.92-.95,3.83-.95,1.92.95,3.84.95,1.92-.95,3.84-.95"/><path class="cls-1" d="M.5,14.9c1.92,0,1.92.95,3.83.95s1.92-.95,3.83-.95,1.92.95,3.83.95,1.92-.95,3.83-.95,1.92.95,3.84.95,1.92-.95,3.84-.95"/><path class="cls-1" d="M.5,20.65c1.92,0,1.92,1,3.83,1s1.92-1,3.83-1,1.92,1,3.83,1,1.92-1,3.83-1,1.92,1,3.84,1,1.92-1,3.84-1"/></svg>
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