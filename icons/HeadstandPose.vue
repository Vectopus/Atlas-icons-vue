
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="15.83" cy="20.59" r="1.91"/><path class="cls-1" d="M11,11h-.95a1.92,1.92,0,0,0-1.92,1.91v1.92l2.46,3.28"/><path class="cls-1" d="M6.26,16.76l1,1V22.5h1l3.65-3a2.87,2.87,0,0,0,.46-3.92L11,13.89V.5"/></svg>
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