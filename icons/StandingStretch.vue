
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><polyline class="cls-1" points="12.96 19.64 12.96 17.73 17.73 15.82 17.73 14.86 13.91 14.86 13.91 7.23 10.09 7.23 10.09 22.5 8.18 22.5"/><line class="cls-1" x1="10.09" y1="7.23" x2="2.45" y2="7.23"/><line class="cls-1" x1="13.91" y1="7.23" x2="21.55" y2="7.23"/></svg>
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