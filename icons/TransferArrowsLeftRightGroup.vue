
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="10.09" r="1.91"/><circle class="cls-1" cx="19.64" cy="10.09" r="1.91"/><path class="cls-1" d="M1.5,16.77a2.86,2.86,0,0,1,2.86-2.86h0a2.86,2.86,0,0,1,2.87,2.86"/><path class="cls-1" d="M16.77,16.77a2.86,2.86,0,0,1,2.87-2.86h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="4.36" cy="10.09" r="1.91"/><path class="cls-1" d="M14.86,16.77A2.86,2.86,0,0,0,12,13.91h0a2.86,2.86,0,0,0-2.86,2.86"/><polyline class="cls-1" points="15.82 4.36 7.23 4.36 10.09 1.5"/><polyline class="cls-1" points="8.18 19.64 16.77 19.64 13.91 22.5"/></svg>
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