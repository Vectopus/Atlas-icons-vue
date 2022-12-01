
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="18.29 16.52 22.5 17.73 22.5 4.36 15.82 2.46 8.18 4.36 1.5 2.46 1.5 15.82 8.18 17.73 11.62 16.87"/><line class="cls-1" x1="8.18" y1="4.36" x2="8.18" y2="17.73"/><line class="cls-1" x1="15.82" y1="11.17" x2="15.82" y2="2.45"/><circle class="cls-1" cx="14.86" cy="14.86" r="3.82"/><line class="cls-1" x1="17.73" y1="17.73" x2="21.55" y2="21.55"/></svg>
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