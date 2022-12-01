
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.2,8.18h-.56a6,6,0,0,0,.09-.95,5.73,5.73,0,0,0-11.46,0,4.77,4.77,0,0,0,0,9.54H18.2a4.3,4.3,0,1,0,0-8.59Z"/><line class="cls-1" x1="14.86" y1="18.68" x2="12.95" y2="22.5"/><line class="cls-1" x1="19.64" y1="18.68" x2="17.73" y2="22.5"/><line class="cls-1" x1="10.09" y1="18.68" x2="8.18" y2="22.5"/><line class="cls-1" x1="5.32" y1="18.68" x2="3.41" y2="22.5"/></svg>
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