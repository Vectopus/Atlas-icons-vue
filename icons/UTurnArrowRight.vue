
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21.59,7.22H9.15A7.65,7.65,0,0,0,1.5,14.87h0a7.65,7.65,0,0,0,7.65,7.65H23.5"/><polyline class="cls-1" points="15.85 1.48 21.59 7.22 15.85 12.96"/></svg>
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