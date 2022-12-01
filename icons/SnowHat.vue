
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="17.73" width="21" height="4.77" rx="2.39"/><path class="cls-1" d="M12,5.32h0a8.59,8.59,0,0,1,8.59,8.59v3.82a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V13.91A8.59,8.59,0,0,1,12,5.32Z"/><path class="cls-1" d="M12,5.32h0a8.59,8.59,0,0,1,8.59,8.59v3.82a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V13.91A8.59,8.59,0,0,1,12,5.32Z"/><path class="cls-1" d="M14.53,5.7a2.86,2.86,0,1,0-5.06,0"/><path class="cls-1" d="M9.14,11.52c0-3.42,1.28-6.2,2.86-6.2s2.86,2.78,2.86,6.2"/></svg>
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