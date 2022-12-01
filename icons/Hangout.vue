
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,18.61v3.78c.94,0,8.5-4.72,8.5-12.28a8.5,8.5,0,1,0-8.5,8.5Z"/><rect class="cls-1" x="8.22" y="8.22" width="1.89" height="1.89"/><path class="cls-1" d="M9.17,12.94h0a3.22,3.22,0,0,0,.94-2.28v-.55"/><rect class="cls-1" x="13.89" y="8.22" width="1.89" height="1.89"/><path class="cls-1" d="M14.83,12.94h0a3.19,3.19,0,0,0,.95-2.28v-.55"/></svg>
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