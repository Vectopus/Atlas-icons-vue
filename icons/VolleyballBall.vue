
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M12,12A9,9,0,0,1,8.56,7a25.2,25.2,0,0,1-1-4.54h0"/><path class="cls-1" d="M21,6.64h0C13.77,5.13,9.75,6.5,8.56,7a3.45,3.45,0,0,0-.38.19"/><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M12,12a9,9,0,0,1,6-.5,24.72,24.72,0,0,1,4.45,1.38"/><path class="cls-1" d="M12.12,22.5c5-5.54,5.76-9.71,5.89-11,0-.27,0-.42,0-.42"/><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M12,12a8.91,8.91,0,0,1-2.58,5.45A25,25,0,0,1,6,20.62"/><path class="cls-1" d="M2.85,6.85c2.32,7.05,5.51,9.84,6.57,10.6a3.4,3.4,0,0,0,.36.24"/></svg>
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