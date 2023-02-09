
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="17.74" cy="13.93" r="2.87"/><path class="cls-1" d="M22.52,23.5h0a4.78,4.78,0,0,0-4.78-4.78h0A4.78,4.78,0,0,0,13,23.5h0"/><polyline class="cls-1" points="1.48 11.06 7.22 5.33 10.09 8.2 16.78 1.5"/><polyline class="cls-1" points="12.96 1.5 16.78 1.5 16.78 5.33"/></svg>
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