
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,22.5H13.91V15.82H10.09v-1h0A11.41,11.41,0,0,1,16.4,13h.37V9.14h0A15.8,15.8,0,0,0,8,11.78L6.27,13,1.5,21.55v.95H4.36"/><polyline class="cls-1" points="16.77 12.96 16.77 17.73 18.68 22.5"/><polyline class="cls-1" points="16.77 10.09 16.77 5.32 18.68 1.5"/><circle class="cls-1" cx="20.59" cy="11.05" r="1.91"/></svg>
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