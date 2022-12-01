
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.6,16.77h4.6a4.3,4.3,0,1,0,0-8.59h-.56a6,6,0,0,0,.09-.95,5.73,5.73,0,0,0-11.46,0,4.77,4.77,0,0,0,0,9.54H10.4"/><path class="cls-1" d="M14.86,19.64a2.86,2.86,0,0,1-5.72,0c0-1.91,2.86-4.78,2.86-4.78S14.86,17.73,14.86,19.64Z"/></svg>
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