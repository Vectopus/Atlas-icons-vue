
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,12.94V7.28A1.84,1.84,0,0,0,11.44,6a1.8,1.8,0,0,0-1.5-.55,2,2,0,0,0-1.72,2v8.4l-1.3-1.31a2,2,0,0,0-1.42-.58,2,2,0,0,0-1.41,3.42l5.08,5.08"/><path class="cls-1" d="M12,12.94V6.44a2,2,0,0,1,1.42-1.93,1.89,1.89,0,0,1,2.36,1.82v6.21l3.09.26a1.79,1.79,0,0,1,1.63,1.78h0a17.16,17.16,0,0,1-1.8,7.64l-.09.17"/><path class="cls-1" d="M8.22,11.6a4.19,4.19,0,0,1-1.45-1,4.72,4.72,0,0,1,4.18-8,4.73,4.73,0,0,1,6.28,7.05,4.48,4.48,0,0,1-1.45,1"/></svg>
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