
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.5,14.87h11a2.39,2.39,0,1,0-2.39-2.39"/><path class="cls-1" d="M.5,18.7H9.11A1.91,1.91,0,1,1,7.2,20.61"/><path class="cls-1" d="M14.85,16.78H18.2a4.31,4.31,0,0,0,0-8.61h-.57a6,6,0,0,0,.09-1,5.74,5.74,0,1,0-11.48,0A4.78,4.78,0,0,0,1.46,12"/></svg>
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