
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="13.93" width="11.45" height="4.77"/><path class="cls-1" d="M19.64,10.11h1A1.91,1.91,0,0,1,22.5,12V16.8a1.91,1.91,0,0,1-1.91,1.91H17.73a0,0,0,0,1,0,0V12a1.91,1.91,0,0,1,1.91-1.91Z"/><path class="cls-1" d="M3.41,10.11h1A1.91,1.91,0,0,1,6.27,12V18.7a0,0,0,0,1,0,0H3.41A1.91,1.91,0,0,1,1.5,16.8V12A1.91,1.91,0,0,1,3.41,10.11Z"/><path class="cls-1" d="M4.36,10.11V7.25A2.87,2.87,0,0,1,7.23,4.39h9.54a2.87,2.87,0,0,1,2.87,2.86v2.86"/><line class="cls-1" x1="4.36" y1="20.61" x2="4.36" y2="18.7"/><line class="cls-1" x1="19.64" y1="20.61" x2="19.64" y2="18.7"/><line class="cls-1" x1="8.18" y1="9.16" x2="10.09" y2="9.16"/><line class="cls-1" x1="13.91" y1="9.16" x2="15.82" y2="9.16"/></svg>
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