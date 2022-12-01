
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.64,13v.48a5.61,5.61,0,0,0,1.94,4.1,2.86,2.86,0,1,1-4.81,2.11"/><circle class="cls-1" cx="19.64" cy="12" r="0.95"/><polyline class="cls-1" points="14.86 19.64 1.5 19.64 1.5 1.5 20.59 1.5 20.59 9.14"/><line class="cls-1" x1="1.5" y1="7.23" x2="20.59" y2="7.23"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="8.18" y1="4.36" x2="10.09" y2="4.36"/></svg>
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