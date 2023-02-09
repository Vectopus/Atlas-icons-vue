
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="20.59" r="1.91"/><circle class="cls-1" cx="20.59" cy="20.59" r="1.91"/><circle class="cls-1" cx="3.41" cy="20.59" r="1.91"/><path class="cls-1" d="M9.14,10.09A2.86,2.86,0,0,1,12,7.23h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><polyline class="cls-1" points="3.41 16.77 3.41 13.91 20.59 13.91 20.59 16.77"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="16.77"/></svg>
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