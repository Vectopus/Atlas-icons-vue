
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12.93" cy="3.37" r="1.91"/><polyline class="cls-1" points="13.89 19.63 13.89 17.72 18.67 15.8 18.67 14.85 14.85 14.85 14.85 7.2 11.02 7.2 11.02 22.5 9.11 22.5"/><line class="cls-1" x1="11.02" y1="7.2" x2="3.37" y2="7.2"/><polyline class="cls-1" points="14.85 7.2 16.76 7.2 19.63 4.33 19.63 0.5"/></svg>
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