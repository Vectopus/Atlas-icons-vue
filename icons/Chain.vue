
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,7.23A4.76,4.76,0,0,1,13,5.32h4.78a4.77,4.77,0,1,1,0,9.54H13a4.77,4.77,0,0,1-4.67-3.81"/><path class="cls-1" d="M15.72,13a4.77,4.77,0,0,0-4.67-3.81H6.27a4.77,4.77,0,0,0,0,9.54h4.78a4.76,4.76,0,0,0,3.37-1.39,3.57,3.57,0,0,0,.44-.52"/></svg>
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