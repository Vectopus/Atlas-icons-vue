
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,10.09a2.86,2.86,0,0,1,2.87-2.86h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="19.64" cy="3.41" r="1.91"/><path class="cls-1" d="M9.14,10.09A2.86,2.86,0,0,1,12,7.23h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><path class="cls-1" d="M22.5,12a10.5,10.5,0,0,1-21,0Z"/><line class="cls-1" x1="2.45" y1="16.77" x2="21.55" y2="16.77"/><path class="cls-1" d="M15.82,12c0,5.8-1.71,10.5-3.82,10.5S8.18,17.8,8.18,12"/><path class="cls-1" d="M1.5,10.09A2.86,2.86,0,0,1,4.36,7.23h0a2.86,2.86,0,0,1,2.87,2.86"/><circle class="cls-1" cx="4.36" cy="3.41" r="1.91"/></svg>
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