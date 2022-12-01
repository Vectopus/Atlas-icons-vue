
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,16.7H18.2a4.3,4.3,0,1,0,0-8.59h-.56a6,6,0,0,0,.09-.95,5.73,5.73,0,0,0-11.46,0,4.77,4.77,0,0,0,0,9.54h1"/><polygon class="cls-1" points="13.91 16.7 12 19.57 12 17.66 10.09 17.66 12 14.79 12 16.7 13.91 16.7"/></svg>
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