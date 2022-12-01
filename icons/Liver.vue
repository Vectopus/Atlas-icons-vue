
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="liver"><path class="cls-1" d="M20.17,16.28l-7.91,4.88a8.82,8.82,0,0,1-4.63,1.32H6.4a4.9,4.9,0,0,1-4.9-4.9V15.8a8.6,8.6,0,0,1,8.59-8.6H17.6a4.9,4.9,0,0,1,4.9,4.91h0A4.9,4.9,0,0,1,20.17,16.28Z"/><path class="cls-1" d="M7.23,22.48h0A4.78,4.78,0,0,0,12,17.7V10.07"/><path class="cls-1" d="M9.14,7.2h0a4.77,4.77,0,0,0,4.77-4.77V.52"/><path class="cls-1" d="M13,7.2h0a4.77,4.77,0,0,0,4.78-4.77V.52"/></g></svg>
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