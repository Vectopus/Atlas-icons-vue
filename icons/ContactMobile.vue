
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="21" rx="1.91"/><line class="cls-1" x1="5.32" y1="18.68" x2="18.68" y2="18.68"/><circle class="cls-1" cx="12" cy="8.18" r="1.91"/><path class="cls-1" d="M12,10.09h0A2.86,2.86,0,0,1,14.86,13v1a0,0,0,0,1,0,0H9.14a0,0,0,0,1,0,0V13A2.86,2.86,0,0,1,12,10.09Z"/></svg>
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