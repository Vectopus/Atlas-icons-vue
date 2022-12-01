
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="10.39" y="2.21" width="7.6" height="15.19" transform="translate(-2.78 12.91) rotate(-45)"/><path class="cls-1" d="M13,14,4.79,22.14a2,2,0,0,1-1.47.61,2.07,2.07,0,0,1-2.07-2.07,2,2,0,0,1,.61-1.47L10,11Z"/><path class="cls-1" d="M20.41,5.66a2.05,2.05,0,0,1-.6,1.46L18.34,8.59,15.41,5.66l1.47-1.47a2.07,2.07,0,0,1,3.53,1.47Z"/></svg>
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