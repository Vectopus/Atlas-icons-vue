
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12.65,17.14,4.46,22.23a1.94,1.94,0,0,1-2.67-2.67l5.09-8.19a2,2,0,0,0,.52.9,2.09,2.09,0,0,0,1.06.57,2,2,0,0,0,2.72,2.72,2.09,2.09,0,0,0,.57,1.06A2,2,0,0,0,12.65,17.14Z"/><path class="cls-1" d="M15.14,15.81a2,2,0,0,1-2.49,1.33,2,2,0,0,1-.9-.52,2.09,2.09,0,0,1-.57-1.06,2,2,0,0,1-2.72-2.72,2.09,2.09,0,0,1-1.06-.57,2,2,0,0,1-.52-.9,2,2,0,0,1,.52-2,1.92,1.92,0,0,1,.77-.48,7.1,7.1,0,0,1,2.09-5.32,7.17,7.17,0,1,1,4.88,12.23Z"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:round;stroke-linejoin:round;}
</style>