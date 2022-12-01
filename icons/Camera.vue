
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12.95" r="4.77"/><path class="cls-1" d="M16.77,6.27,14.86,3.41H9.14L7.23,6.27H3.41A1.91,1.91,0,0,0,1.5,8.18v10.5a1.9,1.9,0,0,0,1.91,1.91H20.59a1.9,1.9,0,0,0,1.91-1.91V8.18a1.91,1.91,0,0,0-1.91-1.91Z"/><line class="cls-1" x1="4.36" y1="4.36" x2="4.36" y2="6.27"/><line class="cls-1" x1="18.68" y1="9.14" x2="20.59" y2="9.14"/></svg>
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