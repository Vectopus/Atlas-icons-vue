
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><rect class="cls-1" x="9.14" y="9.14" width="5.73" height="5.73" rx="2.86"/><path class="cls-1" d="M16.77,7.23h0a6.74,6.74,0,0,1,0,9.54h0"/><path class="cls-1" d="M7.23,16.77h0a6.74,6.74,0,0,1,0-9.54h0"/></svg>
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