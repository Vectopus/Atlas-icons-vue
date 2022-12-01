
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 22.5 1.5 22.5 1.5 0.5"/><circle class="cls-1" cx="15.85" cy="5.28" r="3.83"/><line class="cls-1" x1="22.54" y1="11.98" x2="18.72" y2="8.15"/><line class="cls-1" x1="6.28" y1="10.07" x2="6.28" y2="22.5"/><line class="cls-1" x1="11.07" y1="16.76" x2="11.07" y2="22.5"/><line class="cls-1" x1="15.85" y1="12.93" x2="15.85" y2="22.5"/></svg>
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