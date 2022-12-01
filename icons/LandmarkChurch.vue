
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="14.87 11.02 15.83 22.5 8.17 22.5 9.13 11.02 11.04 6.24 12.96 6.24 14.87 11.02"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="6.24"/><line class="cls-1" x1="10.09" y1="2.41" x2="13.91" y2="2.41"/><path class="cls-1" d="M14.87,11c1.91,4.78,4.78,6.7,7.65,7.65V22.5H15.83L14.87,11"/><path class="cls-1" d="M9.13,11c-1.91,4.78-4.78,6.7-7.65,7.65V22.5H8.17L9.13,11"/><line class="cls-1" x1="12" y1="18.67" x2="12" y2="22.5"/><line class="cls-1" x1="12" y1="12.93" x2="12" y2="14.85"/></svg>
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