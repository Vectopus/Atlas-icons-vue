
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="scale"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><path class="cls-1" d="M12,4.36h0a4.77,4.77,0,0,1,4.77,4.77v0a0,0,0,0,1,0,0H7.23a0,0,0,0,1,0,0v0A4.77,4.77,0,0,1,12,4.36Z"/><line class="cls-1" x1="12" y1="6.27" x2="12" y2="9.14"/><path class="cls-1" d="M8,19.64H8a2.09,2.09,0,0,1-2-1.69l-.58-2.88a2,2,0,0,1,0-.41V14.1A2.1,2.1,0,0,1,7.42,12H8a2.1,2.1,0,0,1,2.1,2.1v3.44A2.1,2.1,0,0,1,8,19.64Z"/><path class="cls-1" d="M16,19.64h0a2.09,2.09,0,0,0,2-1.69l.58-2.88a2,2,0,0,0,0-.41V14.1a2.1,2.1,0,0,0-2.1-2.1H16a2.1,2.1,0,0,0-2.1,2.1v3.44A2.1,2.1,0,0,0,16,19.64Z"/></g></svg>
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