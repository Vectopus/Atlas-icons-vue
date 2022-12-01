
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="8.18" y="16.77" width="7.64" height="5.73"/><path class="cls-1" d="M12,13h0a1.91,1.91,0,0,1,1.91,1.91v1.91a0,0,0,0,1,0,0H10.09a0,0,0,0,1,0,0V14.86A1.91,1.91,0,0,1,12,13Z"/><path class="cls-1" d="M8.63,10.53a4.77,4.77,0,0,1,6.74,0"/><path class="cls-1" d="M5.93,7.83a8.59,8.59,0,0,1,12.14,0"/><path class="cls-1" d="M3.23,5.13a12.41,12.41,0,0,1,17.54,0"/></svg>
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