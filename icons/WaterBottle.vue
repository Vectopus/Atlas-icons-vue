
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.08,14.7a2.08,2.08,0,0,1-4.16,0c0-1.78,2.08-3.86,2.08-3.86S14.08,12.92,14.08,14.7Z"/><path class="cls-1" d="M14.86,4.36V1.5H9.14V4.36h0a4.2,4.2,0,0,0-2.87,4V22.5H17.73V8.34a4.2,4.2,0,0,0-2.87-4Z"/><line class="cls-1" x1="7.23" y1="1.5" x2="16.77" y2="1.5"/></svg>
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