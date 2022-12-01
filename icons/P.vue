
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,10.57h0a4.29,4.29,0,0,1-4.29,4.29H12v2.87H7.23V6.27h5.25A4.3,4.3,0,0,1,16.77,10.57Z"/><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/></svg>
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