
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="tape"><path class="cls-1" d="M17.24,12a7.6,7.6,0,1,1-.55-2.86A7.78,7.78,0,0,1,17.24,12Z"/><circle class="cls-1" cx="9.62" cy="12" r="2.86"/><path class="cls-1" d="M21.05,7.24,22,9.14H16.69A7.64,7.64,0,0,0,9.62,4.38H22Z"/></g></svg>
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