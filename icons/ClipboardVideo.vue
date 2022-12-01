
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="15.82 2.46 15.82 2.46 20.59 2.46 20.59 22.5 3.41 22.5 3.41 2.46 8.18 2.46 8.18 2.46"/><path class="cls-1" d="M15.82,1.5V3.41a1.92,1.92,0,0,1-1.91,1.91H10.09A1.92,1.92,0,0,1,8.18,3.41V1.5Z"/><rect class="cls-1" x="7.23" y="10.09" width="5.73" height="6.68"/><polygon class="cls-1" points="12.96 13.91 15.82 16.77 16.77 16.77 16.77 10.09 15.82 10.09 12.96 12.96 12.96 13.91"/></svg>
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