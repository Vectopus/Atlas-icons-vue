
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,23.52a4.78,4.78,0,0,1,4.77-4.77h0a4.78,4.78,0,0,1,4.78,4.77"/><circle class="cls-1" cx="6.27" cy="13.98" r="2.86"/><path class="cls-1" d="M13,23.52a4.78,4.78,0,0,1,4.78-4.77h0a4.78,4.78,0,0,1,4.77,4.77"/><circle class="cls-1" cx="17.73" cy="13.98" r="2.86"/><polygon class="cls-1" points="12 3.48 12.62 4.73 14.01 4.94 13 5.91 13.24 7.29 12 6.64 10.76 7.29 11 5.91 9.99 4.94 11.38 4.73 12 3.48"/></svg>
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