
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,14.84h0A5,5,0,0,1,8.18,10V7.2l3.82-1,3.82,1V10A5,5,0,0,1,12,14.84Z"/><path class="cls-1" d="M18.68,1.48H5.32A3.82,3.82,0,0,0,1.5,5.3v9.54a3.82,3.82,0,0,0,3.82,3.82H9.14L12,21.52l2.86-2.86h3.82a3.82,3.82,0,0,0,3.82-3.82V5.3A3.82,3.82,0,0,0,18.68,1.48Z"/></svg>
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