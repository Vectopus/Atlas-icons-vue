
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,13.91a8.59,8.59,0,1,1-8.59-8.59v4.77a3.82,3.82,0,1,0,3.82,3.82Z"/><path class="cls-1" d="M22.5,11.05H16.77A3.82,3.82,0,0,0,13,7.23V1.5A9.56,9.56,0,0,1,22.5,11.05Z"/><line class="cls-1" x1="16.16" y1="19.98" x2="12.79" y2="16.61"/></svg>
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