
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,1.5h4.78v21H14.86a2.86,2.86,0,0,0-5.72,0H4.36V1.5h10.5Z"/><rect class="cls-1" x="8.18" y="8.18" height="1.91"/><rect class="cls-1" x="12" y="8.18" height="1.91"/><rect class="cls-1" x="15.82" y="8.18" height="1.91"/></svg>
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