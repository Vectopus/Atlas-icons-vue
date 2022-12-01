
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="8.17" x2="5.28" y2="8.17"/><line class="cls-1" x1="1.46" y1="12" x2="5.28" y2="12"/><line class="cls-1" x1="2.41" y1="15.83" x2="5.28" y2="15.83"/><polyline class="cls-1" points="5.28 18.7 22.5 18.7 22.5 5.3 5.28 5.3"/><polyline class="cls-1" points="5.28 5.3 13.89 13.72 22.5 5.3"/><line class="cls-1" x1="11.98" y1="12" x2="5.28" y2="18.7"/><line class="cls-1" x1="22.5" y1="18.7" x2="15.8" y2="12"/></svg>
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