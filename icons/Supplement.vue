
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="suplement"><path class="cls-1" d="M7.23,6.27h9.55a0,0,0,0,1,0,0V20.76A1.74,1.74,0,0,1,15,22.5H9a1.74,1.74,0,0,1-1.74-1.74V6.27A0,0,0,0,1,7.23,6.27Z"/><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="4.77"/><rect class="cls-1" x="11.05" y="11.05" width="5.73" height="6.68"/></g></svg>
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