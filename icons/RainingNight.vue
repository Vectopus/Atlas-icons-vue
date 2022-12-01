
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11.11,6.38a5.73,5.73,0,0,1,5.67-4.9,4.56,4.56,0,0,1,.75.06A4.1,4.1,0,0,0,22.45,8.1a5.7,5.7,0,0,1-4.84,4.8"/><path class="cls-1" d="M14.87,18.73h.48a3.36,3.36,0,1,0,0-6.71h-.57a5,5,0,0,0,.09-1,4.79,4.79,0,1,0-9.58,0,3.84,3.84,0,1,0,0,7.67"/><line class="cls-1" x1="7.21" y1="22.56" x2="7.21" y2="17.77"/><line class="cls-1" x1="10.08" y1="23.52" x2="10.08" y2="18.73"/><line class="cls-1" x1="12.96" y1="22.56" x2="12.96" y2="17.77"/></svg>
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