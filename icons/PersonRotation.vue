
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="5.16" r="3.91"/><path class="cls-1" d="M17.34,12.52c3.24.66,5.41,1.93,5.41,3.39,0,1.91-3.79,3.51-8.8,3.84"/><path class="cls-1" d="M6.66,12.52c-3.24.66-5.41,1.93-5.41,3.39,0,2,4.28,3.71,9.75,3.89"/><polyline class="cls-1" points="8.09 16.89 11.02 19.82 8.09 22.75"/><path class="cls-1" d="M17.86,15.91v-1h0A5.86,5.86,0,0,0,12,9.07h0a5.86,5.86,0,0,0-5.86,5.86h0v1"/></svg>
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