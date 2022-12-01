
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.36" cy="19.64" r="2.86"/><path class="cls-1" d="M7.23,4.36a2.87,2.87,0,0,0-5.73,0"/><polyline class="cls-1" points="7.23 7.23 22.5 7.23 22.5 22.5 4.36 22.5"/><polyline class="cls-1" points="7.23 19.64 7.23 7.23 7.23 4.36"/><line class="cls-1" x1="1.5" y1="4.36" x2="1.5" y2="19.64"/><line class="cls-1" x1="18.68" y1="10.09" x2="18.68" y2="19.64"/></svg>
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