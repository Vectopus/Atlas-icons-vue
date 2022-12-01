
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><ellipse class="cls-1" cx="12" cy="3.21" rx="3.91" ry="1.95"/><line class="cls-1" x1="11.02" y1="11.02" x2="12.98" y2="11.02"/><path class="cls-1" d="M20.79,6.14l-1,2L17.7,7.32a6.21,6.21,0,0,1-1.83,1.06L14.21,20.81A2.23,2.23,0,0,1,12,22.75h0a2.23,2.23,0,0,1-2.21-1.94L8.2,8.87l-.07-.49A6.21,6.21,0,0,1,6.3,7.32l-2.12.77-1-1.95L5.7,3.65c1-1.41,3.47-2.4,6.3-2.4s5.27,1,6.3,2.4Z"/></svg>
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