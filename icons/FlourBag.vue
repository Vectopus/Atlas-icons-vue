
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,19.64H5.32q-3.82-7.23,0-15.28H18.68Q22.51,12.4,18.68,19.64Z"/><polygon class="cls-1" points="5.32 19.64 18.68 19.64 19.64 22.5 4.36 22.5 5.32 19.64"/><polygon class="cls-1" points="4.36 1.5 19.64 1.5 18.68 4.36 5.32 4.36 4.36 1.5"/><path class="cls-1" d="M12.35,16a2.36,2.36,0,0,1-1.78.8,2.39,2.39,0,1,1,2.16-3.4"/><circle class="cls-1" cx="13.91" cy="14.86" r="1.91"/><line class="cls-1" x1="8.18" y1="8.18" x2="15.82" y2="8.18"/></svg>
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