
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.46" y="8.17" width="17.22" height="3.83" rx="1.91"/><path class="cls-1" d="M.5,15.83H18.67A3.83,3.83,0,0,0,22.5,12h0"/><line class="cls-1" x1="5.28" y1="12" x2="5.28" y2="15.83"/><line class="cls-1" x1="14.85" y1="12" x2="14.85" y2="15.83"/></svg>
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