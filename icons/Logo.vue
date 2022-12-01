
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.34" r="2.86"/><circle class="cls-1" cx="19.64" cy="16.75" r="2.86"/><circle class="cls-1" cx="4.36" cy="16.75" r="2.86"/><path class="cls-1" d="M6,19.09a8.59,8.59,0,0,0,12,0"/><path class="cls-1" d="M14.82,4.82a8.57,8.57,0,0,1,5.77,8.11,6.71,6.71,0,0,1-.08,1.1"/><path class="cls-1" d="M3.49,14a6.71,6.71,0,0,1-.08-1.1A8.57,8.57,0,0,1,9.18,4.82"/></svg>
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