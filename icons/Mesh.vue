
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.42" y="2.42" width="19.17" height="19.17"/><line class="cls-1" x1="12" y1="23.5" x2="12" y2="18.71"/><line class="cls-1" x1="12" y1="5.29" x2="12" y2="0.5"/><polyline class="cls-1" points="16.79 16.69 16.79 16.79 16.79 23.5"/><polyline class="cls-1" points="16.79 7.31 16.79 7.21 16.79 0.5"/><polyline class="cls-1" points="7.21 16.69 7.21 16.79 7.21 23.5"/><polyline class="cls-1" points="7.21 7.31 7.21 7.21 7.21 0.5"/><line class="cls-1" x1="23.5" y1="12" x2="18.71" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/><polyline class="cls-1" points="23.5 7.21 16.79 7.21 16.69 7.21"/><polyline class="cls-1" points="7.31 7.21 7.21 7.21 0.5 7.21"/><polyline class="cls-1" points="23.5 16.79 16.79 16.79 16.69 16.79"/><polyline class="cls-1" points="7.31 16.79 7.21 16.79 0.5 16.79"/><path class="cls-1" d="M18.71,12a6.66,6.66,0,0,1-1.92,4.69l-.1.1a6.69,6.69,0,0,1-9.38,0l-.1-.1a6.69,6.69,0,0,1,0-9.38l.1-.1a6.69,6.69,0,0,1,9.38,0l.1.1A6.66,6.66,0,0,1,18.71,12Z"/></svg>
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