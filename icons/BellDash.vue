
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.38,14.82V10.15A8.4,8.4,0,0,0,12,1.75h0a8.4,8.4,0,0,0-8.4,8.4v4.67L1.72,16.68v1.87H22.25V16.68Z"/><path class="cls-1" d="M14.62,18.55a2.64,2.64,0,0,1,.16.93,2.8,2.8,0,1,1-5.6,0,2.64,2.64,0,0,1,.17-.93"/><line class="cls-1" x1="22.25" y1="1.75" x2="1.25" y2="22.75"/></svg>
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