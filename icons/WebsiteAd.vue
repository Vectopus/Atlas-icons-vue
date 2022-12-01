
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="5.73"/><rect class="cls-1" x="1.5" y="7.23" width="21" height="15.27"/><path class="cls-1" d="M9.14,12H11a0,0,0,0,1,0,0v3.82a0,0,0,0,1,0,0H9.14a1.91,1.91,0,0,1-1.91-1.91v0A1.91,1.91,0,0,1,9.14,12Z"/><polygon class="cls-1" points="11.04 12 15.82 10.09 15.82 17.73 11.04 15.82 11.04 12"/><line class="cls-1" x1="11.05" y1="20.59" x2="9.14" y2="15.82"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="8.18" y1="4.36" x2="10.09" y2="4.36"/></svg>
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