
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.72" cy="4.83" r="2.39"/><polyline class="cls-1" points="22.5 18.7 22.5 21.57 11.98 21.57"/><path class="cls-1" d="M11.5,19.65,9.57,11.94A2.44,2.44,0,0,0,7.2,10.09h0a2.44,2.44,0,0,0-2.38,1.85L2.41,21.57H.5"/><path class="cls-1" d="M12,21.57H10.07a2.45,2.45,0,0,1-2.38-1.86L6.23,13.88"/></svg>
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