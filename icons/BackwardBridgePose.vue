
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="8.67" cy="14.39" r="2.39"/><path class="cls-1" d="M14.89,3.39h-3A8,8,0,0,0,4.33,8.61h0A1.8,1.8,0,0,0,6,11H6A1.79,1.79,0,0,0,7.69,9.91h0a5.81,5.81,0,0,1,5.39-3.65h1.81"/><polyline class="cls-1" points="6.28 11.04 1.5 14.87 1.5 20.61 4.37 20.61"/><polyline class="cls-1" points="14.89 3.39 17.76 3.39 22.54 10.09 22.54 11.04 20.63 19.65 20.63 20.61 23.5 20.61"/></svg>
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