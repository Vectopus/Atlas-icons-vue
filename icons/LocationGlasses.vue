
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.91,11h4.88a2,2,0,0,1,2,2v7.81a2,2,0,0,1-2,2H14.93l-1.42-2.12a1.81,1.81,0,0,0-3,0L9.07,22.75H3.21a2,2,0,0,1-2-2V13a2,2,0,0,1,2-2H8.09"/><line class="cls-1" x1="4.18" y1="14.93" x2="6.14" y2="14.93"/><line class="cls-1" x1="4.18" y1="18.84" x2="6.14" y2="18.84"/><path class="cls-1" d="M15.91,5.16C15.91,8.09,12,11,12,11S8.09,8.09,8.09,5.16a3.91,3.91,0,0,1,7.82,0Z"/><circle class="cls-2" cx="12" cy="5.16" r="0.98"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>