
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.78,20.59a5.18,5.18,0,0,1-4.86-3.37,25.77,25.77,0,0,1-1.2-4.14,10.66,10.66,0,0,1-.22-2A9.55,9.55,0,0,1,20.4,9.14H14.86A1.91,1.91,0,0,0,13,11.05v4.36a5.17,5.17,0,0,1-5.17,5.18Z"/><circle class="cls-1" cx="8.18" cy="14.86" r="1.91"/><polyline class="cls-1" points="12.07 18.31 16.77 22.5 22.5 22.5 22.5 18.68 22.5 14.86 12.96 14.86 10.09 14.86"/><line class="cls-1" x1="18.68" y1="14.86" x2="18.68" y2="22.5"/><line class="cls-1" x1="12.95" y1="18.68" x2="22.5" y2="18.68"/></svg>
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