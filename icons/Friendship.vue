
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="8.17" cy="3.89" r="2.39"/><polyline class="cls-1" points="10.09 23.5 10.09 14.89 10.09 8.2 6.26 8.2 6.26 14.89 6.26 16.8 6.26 23.5"/><circle class="cls-1" cx="15.83" cy="3.89" r="2.39"/><polyline class="cls-1" points="17.74 23.5 17.74 16.8 17.74 14.89 17.74 8.2 13.91 8.2 13.91 14.89 13.91 23.5"/><polyline class="cls-1" points="17.74 8.2 18.7 8.2 20.61 16.8"/><polyline class="cls-1" points="6.26 8.2 5.3 8.2 3.39 16.8"/><line class="cls-1" x1="10.09" y1="8.2" x2="13.91" y2="8.2"/></svg>
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