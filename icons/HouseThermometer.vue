
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 10.57 12 1.98 1.5 10.57"/><path class="cls-1" d="M13.91,17V9.61a1.91,1.91,0,0,0-3.82,0V17a2.86,2.86,0,1,0,3.82,0Z"/><line class="cls-1" x1="15.82" y1="10.57" x2="13.91" y2="10.57"/><line class="cls-1" x1="15.82" y1="14.39" x2="13.91" y2="14.39"/><polyline class="cls-1" points="7.23 22.02 4.36 22.02 4.36 8.66"/><polyline class="cls-1" points="16.77 22.02 19.64 22.02 19.64 8.66"/></svg>
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