
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="9.14" y="12" width="5.73" height="10.5"/><rect class="cls-1" x="14.86" y="15.82" width="7.64" height="6.68"/><rect class="cls-1" x="1.5" y="18.68" width="7.64" height="3.82"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><path class="cls-1" d="M9.14,10.09A2.86,2.86,0,0,1,12,7.23h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="19.64" cy="7.23" r="1.91"/><path class="cls-1" d="M16.77,13.91a2.86,2.86,0,0,1,2.87-2.86h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="4.36" cy="10.09" r="1.91"/><path class="cls-1" d="M1.5,16.77a2.86,2.86,0,0,1,2.86-2.86h0a2.86,2.86,0,0,1,2.87,2.86"/></svg>
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