
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,9.14H17.73a0,0,0,0,1,0,0v6.68a2.86,2.86,0,0,1-2.86,2.86H9.14a2.86,2.86,0,0,1-2.86-2.86V9.14A0,0,0,0,1,6.27,9.14Z"/><rect class="cls-1" x="10.09" y="18.68" width="3.82" height="3.82"/><path class="cls-1" d="M9.14,1.5h5.73a1.91,1.91,0,0,1,1.91,1.91V9.14a0,0,0,0,1,0,0H7.23a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,9.14,1.5Z"/><rect class="cls-1" x="7.23" y="1.5" width="9.55" height="3.82" rx="1.91"/></svg>
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