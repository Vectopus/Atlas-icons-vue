
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.9,8.44a4.68,4.68,0,0,0-3.9,2.1,4.68,4.68,0,0,0-8.59,2.59c0,7,8.59,9.37,8.59,9.37s8.59-2.34,8.59-9.37A4.69,4.69,0,0,0,15.9,8.44Z"/><path class="cls-1" d="M7.23,9.27v-3a4.77,4.77,0,1,1,9.54,0v3"/><circle class="cls-1" cx="12" cy="15.82" r="0.95"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="16.77"/></svg>
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