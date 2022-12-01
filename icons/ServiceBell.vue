
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="22.5 22.5 1.5 22.5 1.5 20.59 2.46 18.68 21.55 18.68 22.5 20.59 22.5 22.5"/><path class="cls-1" d="M11.75,5.32h.49a9.3,9.3,0,0,1,9.3,9.3v.25a0,0,0,0,1,0,0H2.45a0,0,0,0,1,0,0v-.25A9.3,9.3,0,0,1,11.75,5.32Z"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="5.32"/><line class="cls-1" x1="9.14" y1="1.5" x2="14.86" y2="1.5"/><rect class="cls-1" x="5.32" y="14.86" width="13.36" height="3.82"/></svg>
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