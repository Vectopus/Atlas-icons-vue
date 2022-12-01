
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="tie"><path class="cls-1" d="M15.82,3.79v.09a2.38,2.38,0,0,1-.25,1l-.8,1.57a3.24,3.24,0,0,1-.49.7,3.1,3.1,0,0,1-4.56,0,3.17,3.17,0,0,1-.48-.71L8.42,4.81a2.35,2.35,0,0,1-.24-1A2.29,2.29,0,0,1,10.47,1.5h3.06A2.3,2.3,0,0,1,15.82,3.79Z"/><path class="cls-1" d="M16.77,19.64,12,22.5,7.23,19.64,9.72,7.17a3.1,3.1,0,0,0,4.56,0Z"/></g></svg>
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