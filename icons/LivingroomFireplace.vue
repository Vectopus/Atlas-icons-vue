
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="18.68" width="19.09" height="3.82"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><rect class="cls-1" x="3.41" y="5.32" width="17.18" height="13.36"/><rect class="cls-1" x="2.45" y="1.5" width="19.09" height="3.82"/><path class="cls-1" d="M15.82,14.86a3.82,3.82,0,0,1-7.64,0C8.18,11.68,12,8.5,12,8.5S15.82,11.68,15.82,14.86Z"/><path class="cls-1" d="M13.83,16.85a1.83,1.83,0,1,1-3.66,0c0-1.52,1.83-3.05,1.83-3.05S13.83,15.33,13.83,16.85Z"/></svg>
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