
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M3.41,13H1.5V10.09a2.86,2.86,0,0,1,4.89-2,2.72,2.72,0,0,1,.42.53"/><circle class="cls-1" cx="4.36" cy="3.41" r="1.91"/><polygon class="cls-1" points="13.91 12.96 8.18 12.96 9.14 8.18 14.86 8.18 13.91 12.96"/><line class="cls-1" x1="9.14" y1="12.95" x2="4.36" y2="12.95"/><path class="cls-1" d="M17.19,18.15a3.13,3.13,0,0,1,.42-.54,2.86,2.86,0,0,1,4.89,2V22.5H20.59"/><circle class="cls-1" cx="19.64" cy="12.95" r="1.91"/><polygon class="cls-1" points="10.09 22.5 15.82 22.5 14.86 17.73 9.14 17.73 10.09 22.5"/><line class="cls-1" x1="14.86" y1="22.5" x2="19.64" y2="22.5"/></svg>
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