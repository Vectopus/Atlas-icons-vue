
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.84,7.6h1.95a2,2,0,0,1,2,2v7.81a2,2,0,0,1-2,2H14.93l-1.42-2.12a1.81,1.81,0,0,0-3,0L9.07,19.33H3.21a2,2,0,0,1-2-2V9.56a2,2,0,0,1,2-2h2"/><line class="cls-1" x1="4.18" y1="11.51" x2="6.14" y2="11.51"/><line class="cls-1" x1="4.18" y1="15.42" x2="6.14" y2="15.42"/><circle class="cls-1" cx="12" cy="7.6" r="0.98"/><path class="cls-1" d="M9.07,10.53a4.14,4.14,0,0,1,0-5.86"/><path class="cls-1" d="M14.93,4.67a4.14,4.14,0,0,1,0,5.86"/></svg>
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