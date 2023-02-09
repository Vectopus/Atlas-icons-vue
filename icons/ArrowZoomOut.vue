
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 12 14.94 12 14.88 12"/><polyline class="cls-1" points="0.5 12 9.06 12 9.13 12"/><polyline class="cls-1" points="5.29 15.83 9.13 12 5.29 8.17"/><polyline class="cls-1" points="18.71 8.17 14.88 12 18.71 15.83"/><polyline class="cls-1" points="12 14.88 12 14.94 12 23.5"/><polyline class="cls-1" points="12 9.13 12 9.06 12 0.5"/><polyline class="cls-1" points="8.17 5.29 12 9.13 15.83 5.29"/><polyline class="cls-1" points="15.83 18.71 12 14.88 8.17 18.71"/></svg>
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