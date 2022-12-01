
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.93,10a2.85,2.85,0,0,1,0,4"/><path class="cls-1" d="M18,8a5.72,5.72,0,0,1,0,8.1"/><path class="cls-1" d="M20,5.93a8.57,8.57,0,0,1,0,12.14"/><rect class="cls-1" x="1.5" y="8.18" width="4.77" height="7.64"/><polygon class="cls-1" points="13.91 3.41 13.91 20.59 12.24 20.59 6.27 15.82 6.27 8.18 12.24 3.41 13.91 3.41"/></svg>
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