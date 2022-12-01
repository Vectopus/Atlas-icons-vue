
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="13.91" width="21" height="8.59"/><circle class="cls-1" cx="4.84" cy="18.2" r="0.48"/><circle class="cls-1" cx="9.61" cy="18.2" r="0.48"/><circle class="cls-1" cx="14.39" cy="18.2" r="0.48"/><circle class="cls-1" cx="19.16" cy="18.2" r="0.48"/><rect class="cls-1" x="9.14" y="5.32" width="5.73" height="4.77"/><path class="cls-1" d="M12,1.5h0a1.91,1.91,0,0,1,1.91,1.91V5.32a0,0,0,0,1,0,0H10.09a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,12,1.5Z"/></svg>
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