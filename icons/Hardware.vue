
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="21" rx="1.91"/><path class="cls-1" d="M16.77,1.5V13.91a4.77,4.77,0,1,1-9.54,0V10.09l.95-.95V5.32l-.95-1V1.5Z"/><circle class="cls-1" cx="12" cy="13.91" r="0.95"/><circle class="cls-2" cx="6.27" cy="19.64" r="0.95"/><circle class="cls-2" cx="17.73" cy="19.64" r="0.95"/><line class="cls-1" x1="12" y1="5.32" x2="13.91" y2="5.32"/></svg>
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