
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11,21.59h-.95L6.26,17.76H4.35a2.87,2.87,0,0,0-2.87,2.87V23.5"/><circle class="cls-1" cx="4.35" cy="13.93" r="1.91"/><path class="cls-1" d="M13,21.59h.95l3.83-3.83h1.91a2.87,2.87,0,0,1,2.87,2.87V23.5"/><circle class="cls-1" cx="19.65" cy="13.93" r="1.91"/><polyline class="cls-1" points="5.3 9.15 11.04 3.41 13.91 6.28 18.7 1.5"/><polyline class="cls-1" points="14.87 1.5 18.7 1.5 18.7 5.33"/></svg>
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