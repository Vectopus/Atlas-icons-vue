
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="6 2 2 6 6 10"/><polyline class="cls-1" points="18 10 22 6 18 2"/><path class="cls-1" d="M12,22V12A6,6,0,0,0,6,6H2"/><path class="cls-1" d="M12,22V12a6,6,0,0,1,6-6h4"/></svg>
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