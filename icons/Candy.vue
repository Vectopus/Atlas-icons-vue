
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="8.18" width="11.45" height="7.64" rx="3.82"/><path class="cls-1" d="M20.59,9.14H22.5a0,0,0,0,1,0,0v5.73a0,0,0,0,1,0,0H20.59A2.86,2.86,0,0,1,17.73,12v0A2.86,2.86,0,0,1,20.59,9.14Z"/><path class="cls-1" d="M4.36,9.14H6.27a0,0,0,0,1,0,0v5.73a0,0,0,0,1,0,0H4.36A2.86,2.86,0,0,1,1.5,12v0A2.86,2.86,0,0,1,4.36,9.14Z" transform="translate(7.77 24) rotate(180)"/><line class="cls-1" x1="9.14" y1="8.18" x2="11.05" y2="15.82"/><line class="cls-1" x1="12.95" y1="8.18" x2="14.86" y2="15.82"/></svg>
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