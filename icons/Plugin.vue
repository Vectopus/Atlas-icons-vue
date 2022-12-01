
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.64,11.05h-1V5.32H13v-1a2.86,2.86,0,1,0-5.72,0v1H1.5v5.73h1a2.86,2.86,0,1,1,0,5.72h-1V22.5H7.23v-.95a2.86,2.86,0,1,1,5.72,0v.95h5.73V16.77h1a2.86,2.86,0,0,0,0-5.72Z"/></svg>
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