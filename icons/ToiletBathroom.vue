
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,11H17.73a0,0,0,0,1,0,0v1a5.65,5.65,0,0,1-5.65,5.65h-.16a5.65,5.65,0,0,1-5.65-5.65V11A0,0,0,0,1,6.27,11Z"/><line class="cls-1" x1="19.64" y1="11.05" x2="4.36" y2="11.05"/><polyline class="cls-1" points="14.9 16.97 15.82 22.5 8.18 22.5 9.1 16.97"/><rect class="cls-1" x="7.23" y="1.5" width="9.55" height="9.55" rx="1.91"/><line class="cls-1" x1="5.32" y1="4.36" x2="7.23" y2="4.36"/><line class="cls-1" x1="12.95" y1="4.36" x2="14.86" y2="4.36"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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