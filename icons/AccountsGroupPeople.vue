
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,22.52a2.86,2.86,0,0,1,2.87-2.86h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="19.64" cy="15.84" r="1.91"/><path class="cls-1" d="M9.14,22.52A2.86,2.86,0,0,1,12,19.66h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="15.84" r="1.91"/><path class="cls-1" d="M13,11.07A2.88,2.88,0,0,1,15.82,8.2h0a2.87,2.87,0,0,1,2.86,2.87"/><circle class="cls-1" cx="15.82" cy="4.39" r="1.91"/><path class="cls-1" d="M5.32,11.07A2.87,2.87,0,0,1,8.18,8.2h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="8.18" cy="4.39" r="1.91"/><path class="cls-1" d="M1.5,22.52a2.86,2.86,0,0,1,2.86-2.86h0a2.86,2.86,0,0,1,2.87,2.86"/><circle class="cls-1" cx="4.36" cy="15.84" r="1.91"/></svg>
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