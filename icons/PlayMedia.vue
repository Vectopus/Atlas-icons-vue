
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.73,16.43c0,1.84,3.74,3.74,8.46,3.68"/><path class="cls-1" d="M13.87,20.1c4.66.07,8.4-1.84,8.4-3.67"/><polyline class="cls-1" points="7.8 17.72 10.19 20.11 7.8 22.5"/><polyline class="cls-1" points="1.73 16.43 1.73 1.5 22.27 1.5 22.27 16.43"/><polygon class="cls-1" points="12.93 11.77 11.07 12.7 11.07 10.83 12.93 11.77 12.93 11.77"/><line class="cls-1" x1="5.47" y1="5.23" x2="7.33" y2="5.23"/><line class="cls-1" x1="1.73" y1="5.23" x2="3.6" y2="5.23"/><line class="cls-1" x1="9.2" y1="5.23" x2="11.07" y2="5.23"/><line class="cls-1" x1="12.93" y1="5.23" x2="14.8" y2="5.23"/><line class="cls-1" x1="16.67" y1="5.23" x2="18.53" y2="5.23"/><line class="cls-1" x1="20.4" y1="5.23" x2="22.27" y2="5.23"/></svg>
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