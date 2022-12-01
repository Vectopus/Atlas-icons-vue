
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12.95" r="9.55"/><path class="cls-1" d="M4.44,7.13,2.06,4.75a1.89,1.89,0,0,1,0-2.69A1.93,1.93,0,0,1,3.41,1.5a1.89,1.89,0,0,1,1.34.56L7.33,4.63"/><path class="cls-1" d="M16.67,4.63l2.58-2.57a1.89,1.89,0,0,1,1.34-.56,1.93,1.93,0,0,1,1.35.56,1.89,1.89,0,0,1,0,2.69L19.56,7.13"/></svg>
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