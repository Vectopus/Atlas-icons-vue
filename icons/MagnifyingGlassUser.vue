
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="14.86" cy="9.14" r="7.64"/><line class="cls-1" x1="1.5" y1="22.5" x2="9.14" y2="14.86"/><circle class="cls-1" cx="14.86" cy="8.18" r="2.86"/><path class="cls-1" d="M19.58,15.14a4.76,4.76,0,0,0-9.43,0"/></svg>
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