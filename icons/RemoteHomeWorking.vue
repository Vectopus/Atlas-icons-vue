
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.18,22.52H6.27V19.66a2.86,2.86,0,0,1,4.89-2,2.39,2.39,0,0,1,.42.53"/><circle class="cls-1" cx="9.14" cy="12.98" r="1.91"/><polygon class="cls-1" points="18.68 22.52 12.96 22.52 13.91 17.75 19.64 17.75 18.68 22.52"/><line class="cls-1" x1="13.91" y1="22.52" x2="9.14" y2="22.52"/><polyline class="cls-1" points="1.5 11.07 12 2.48 22.5 11.07"/><line class="cls-1" x1="19.64" y1="8.2" x2="19.64" y2="15.84"/><line class="cls-1" x1="4.36" y1="16.8" x2="4.36" y2="8.2"/><polyline class="cls-1" points="16.77 6.29 16.77 2.48 19.64 2.48 19.64 8.21"/></svg>
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