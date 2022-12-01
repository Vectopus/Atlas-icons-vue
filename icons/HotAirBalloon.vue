
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.21,14.79a14.68,14.68,0,0,0-1.35,3.71H10.14a14.68,14.68,0,0,0-1.35-3.71Z"/><path class="cls-1" d="M18.5,8.29c0,1.81-1.65,4.39-3.29,6.5H8.79C7.15,12.68,5.5,10.1,5.5,8.29a6.5,6.5,0,0,1,13,0Z"/><path class="cls-1" d="M14.79,8.29a23.5,23.5,0,0,1-1.42,6.5H10.63a23.5,23.5,0,0,1-1.42-6.5c0-3.6,1.25-6.5,2.79-6.5S14.79,4.69,14.79,8.29Z"/><rect class="cls-1" x="9.21" y="18.5" width="5.57" height="3.71"/></svg>
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