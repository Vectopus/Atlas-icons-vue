
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.36" cy="4.36" r="2.86"/><path class="cls-1" d="M4.36,22.5H7.23L9.67,7.05a3.18,3.18,0,0,1,3.15-2.69h0A3.17,3.17,0,0,1,14.77,5l7.73,6V22.5H11.05"/><path class="cls-1" d="M22.5,11.05l-1.39,1.39h0a2.41,2.41,0,0,1-3.14.22L12,8.18"/></svg>
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