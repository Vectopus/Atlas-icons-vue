
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,22.5h0A11.87,11.87,0,0,1,2.45,10.86V3.41L12,1.5l9.55,1.91v7.45A11.87,11.87,0,0,1,12,22.5Z"/><polyline class="cls-1" points="7.23 10.93 10.81 14.51 16.77 8.54"/></svg>
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