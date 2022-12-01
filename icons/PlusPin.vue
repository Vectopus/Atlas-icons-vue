
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="location"><path class="cls-1" d="M4,9.5a8,8,0,0,1,16,0,13.83,13.83,0,0,1-3.1,8c-.28.38-.57.74-.86,1.08a27,27,0,0,1-4,3.93S4,16.5,4,9.5Z"/><line class="cls-1" x1="8" y1="9.5" x2="16" y2="9.5"/><line class="cls-1" x1="12" y1="5.5" x2="12" y2="13.5"/></g></svg>
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