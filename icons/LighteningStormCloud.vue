
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.35,18.67a3.36,3.36,0,1,0,0-6.71h-.57a5,5,0,0,0,.09-1,4.79,4.79,0,0,0-9.58,0,3.84,3.84,0,1,0,0,7.67"/><path class="cls-1" d="M11.11,6.31a5.72,5.72,0,0,1,5.67-4.89,4.57,4.57,0,0,1,.75.05A4.1,4.1,0,0,0,22.45,8a5.7,5.7,0,0,1-4.84,4.8"/><polygon class="cls-1" points="12 17.71 10.08 20.59 10.08 18.67 8.16 18.67 10.08 15.79 10.08 17.71 12 17.71"/></svg>
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