
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="nose"><path class="cls-1" d="M7.23.52V6.73A4.25,4.25,0,0,1,6.37,9.3l-4,5.35a4.28,4.28,0,0,0-.86,2.58h0a4.29,4.29,0,0,0,4.3,4.29H9.14"/><path class="cls-1" d="M5.32,17.7h.43a3,3,0,0,1,2.91,2.39h0a3,3,0,0,0,2.91,2.39H12"/><path class="cls-1" d="M16.77.52V6.73a4.25,4.25,0,0,0,.86,2.57l4,5.35a4.28,4.28,0,0,1,.86,2.58h0a4.29,4.29,0,0,1-4.3,4.29H14.86"/><path class="cls-1" d="M18.68,17.7h-.43a3,3,0,0,0-2.91,2.39h0a3,3,0,0,1-2.91,2.39H12"/></g></svg>
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