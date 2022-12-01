
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.64" cy="11.05" r="1.91"/><path class="cls-1" d="M16.77,15.82h0A2.87,2.87,0,0,1,19.64,13h0a2.87,2.87,0,0,1,2.86,2.87h0"/><circle class="cls-1" cx="4.36" cy="11.05" r="1.91"/><path class="cls-1" d="M1.5,15.82h0A2.87,2.87,0,0,1,4.36,13h0a2.87,2.87,0,0,1,2.87,2.87h0"/><polyline class="cls-1" points="10.09 2.46 7.23 5.32 18.68 5.32"/><polyline class="cls-1" points="13.91 21.55 16.77 18.68 5.32 18.68"/></svg>
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