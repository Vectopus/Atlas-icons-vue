
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11,23,5.62,17.62a2.12,2.12,0,0,1,3-3L10,16V6.11A2.08,2.08,0,0,1,11.82,4,2,2,0,0,1,14,6v6l5.28.75a2,2,0,0,1,1.72,2h0a18,18,0,0,1-1.91,8.09L19,23"/><path class="cls-1" d="M7.46,2.46a5,5,0,0,0,0,7.08"/><path class="cls-1" d="M4.94,1a7.07,7.07,0,0,0,0,10"/><path class="cls-1" d="M16.54,9.54a5,5,0,0,0,0-7.08"/><path class="cls-1" d="M19.06,11a7.07,7.07,0,0,0,0-10"/></svg>
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