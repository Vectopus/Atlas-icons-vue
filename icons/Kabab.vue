
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.64" cy="4.36" r="2.86"/><path class="cls-1" d="M17.06,5.6a2.82,2.82,0,0,0-1.24-.28A2.86,2.86,0,0,0,13,8.18a2.89,2.89,0,0,0,2.87,2.87,2.86,2.86,0,0,0,2.86-2.87,2.82,2.82,0,0,0-.28-1.24"/><path class="cls-1" d="M13.24,9.42A2.82,2.82,0,0,0,12,9.14,2.86,2.86,0,0,0,9.14,12,2.87,2.87,0,0,0,12,14.86,2.86,2.86,0,0,0,14.86,12a2.82,2.82,0,0,0-.28-1.24"/><line class="cls-1" x1="1.5" y1="22.5" x2="10.09" y2="13.91"/></svg>
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