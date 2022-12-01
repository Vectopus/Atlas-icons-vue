
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="dollar_3" data-name="dollar 3"><polyline class="cls-1" points="12 22.5 12 19.64 12 4.36 12 1.5"/><path class="cls-1" d="M6.27,16.77h0a2.87,2.87,0,0,0,2.87,2.87h4.77a3.82,3.82,0,0,0,3.82-3.82h0A3.82,3.82,0,0,0,13.91,12H10.09A3.82,3.82,0,0,1,6.27,8.18h0a3.82,3.82,0,0,1,3.82-3.82h4.77a2.87,2.87,0,0,1,2.87,2.87h0"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>