
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.6,9.14A3.35,3.35,0,0,0,12,10.29,3.35,3.35,0,0,0,9.4,9.14a2.89,2.89,0,0,0-3.13,2.57c0,3.87,5.73,6,5.73,6s5.73-2.15,5.73-6A2.89,2.89,0,0,0,14.6,9.14Z"/><polygon class="cls-1" points="22.5 22.5 1.5 22.5 1.5 10.09 12 1.5 22.5 10.09 22.5 22.5"/><polyline class="cls-1" points="22.5 10.09 12 18.68 1.5 10.09"/></svg>
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