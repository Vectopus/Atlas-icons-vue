
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.83,3.38H11A1.91,1.91,0,0,0,9.12,5.29h0A1.92,1.92,0,0,0,11,7.21H13a1.91,1.91,0,0,1,1.91,1.91h0A1.91,1.91,0,0,1,13,11H8.17"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.38"/><line class="cls-1" x1="12" y1="11.04" x2="12" y2="13.92"/><path class="cls-1" d="M11,21.58h-1L6.25,17.75H4.33a2.88,2.88,0,0,0-2.87,2.87V23.5"/><circle class="cls-1" cx="4.33" cy="13.92" r="1.92"/><path class="cls-1" d="M13,21.58h1l3.83-3.83h1.92a2.88,2.88,0,0,1,2.87,2.87V23.5"/><circle class="cls-1" cx="19.67" cy="13.92" r="1.92"/></svg>
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