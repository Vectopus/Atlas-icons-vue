
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 12.98 12.6 14.24 13.95 14.44 12.98 15.42 13.21 16.8 12 16.15 10.79 16.8 11.02 15.42 10.05 14.44 11.4 14.24 12 12.98"/><path class="cls-1" d="M8.17,10.11a8.73,8.73,0,0,1,3.83-1,8.73,8.73,0,0,1,3.83,1"/><rect class="cls-1" x="5.3" y="5.33" width="13.39" height="15.3"/><line class="cls-1" x1="3.39" y1="5.33" x2="20.61" y2="5.33"/><line class="cls-1" x1="13.91" y1="23.5" x2="13.91" y2="20.63"/><line class="cls-1" x1="17.74" y1="23.5" x2="17.74" y2="20.63"/><line class="cls-1" x1="10.09" y1="23.5" x2="10.09" y2="20.63"/><line class="cls-1" x1="6.26" y1="23.5" x2="6.26" y2="20.63"/><polygon class="cls-1" points="17.74 5.33 6.26 5.33 12 1.5 17.74 5.33"/></svg>
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