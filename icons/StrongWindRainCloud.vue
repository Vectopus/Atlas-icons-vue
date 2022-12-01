
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.5,14.89h11A2.39,2.39,0,1,0,9.11,12.5"/><path class="cls-1" d="M.5,18.72H9.11A1.91,1.91,0,1,1,7.2,20.63"/><path class="cls-1" d="M22.5,12.5a4.3,4.3,0,0,0-4.3-4.3h-.57a6.12,6.12,0,0,0,.09-1,5.74,5.74,0,1,0-11.48,0A4.78,4.78,0,0,0,1.46,12"/><line class="cls-1" x1="22.5" y1="15.85" x2="22.5" y2="19.67"/><line class="cls-1" x1="22.5" y1="21.59" x2="22.5" y2="23.5"/><line class="cls-1" x1="18.67" y1="13.93" x2="18.67" y2="17.76"/><line class="cls-1" x1="18.67" y1="19.67" x2="18.67" y2="21.59"/><line class="cls-1" x1="14.85" y1="15.85" x2="14.85" y2="19.67"/><line class="cls-1" x1="14.85" y1="21.59" x2="14.85" y2="23.5"/></svg>
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