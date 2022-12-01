
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="12" width="21" height="3.82" rx="1.91"/><rect class="cls-1" x="3.41" y="15.82" width="17.18" height="6.68"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><line class="cls-1" x1="7.23" y1="15.82" x2="7.23" y2="22.5"/><line class="cls-1" x1="12" y1="15.82" x2="12" y2="22.5"/><line class="cls-1" x1="16.77" y1="15.82" x2="16.77" y2="22.5"/><path class="cls-1" d="M4.36,2.45C7.67,5.13,3,6.46,6.27,9.14"/><path class="cls-1" d="M11.05,1.5c3.3,2.67-1.4,4,1.9,6.68"/><path class="cls-1" d="M17.73,2.45c3.3,2.68-1.4,4,1.91,6.69"/></svg>
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