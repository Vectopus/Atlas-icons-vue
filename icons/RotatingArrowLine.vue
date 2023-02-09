
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="23.5" y1="12" x2="10.08" y2="12"/><path class="cls-1" d="M15.69,14.88c-.45,4.42-1.94,7.66-3.69,7.66-2.12,0-3.83-4.71-3.83-10.54S9.88,1.46,12,1.46c1.75,0,3.24,3.24,3.69,7.66"/><line class="cls-1" x1="6.25" y1="12" x2="0.5" y2="12"/><polyline class="cls-1" points="17.91 5.72 15.68 9.12 12.29 6.89"/></svg>
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