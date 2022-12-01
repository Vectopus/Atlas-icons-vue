
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.32,16.68a4.77,4.77,0,0,1,.95-9.45,5.73,5.73,0,0,1,11.46,0,6,6,0,0,1-.09.95h.56a4.29,4.29,0,0,1,.48,8.56"/><line class="cls-1" x1="11.05" y1="12.95" x2="12.95" y2="12.95"/><line class="cls-1" x1="11.05" y1="16.77" x2="12.95" y2="16.77"/><line class="cls-1" x1="11.05" y1="20.59" x2="12.95" y2="20.59"/><line class="cls-1" x1="14.86" y1="14.86" x2="16.77" y2="14.86"/><line class="cls-1" x1="14.86" y1="18.68" x2="16.77" y2="18.68"/><line class="cls-1" x1="14.86" y1="22.5" x2="16.77" y2="22.5"/><line class="cls-1" x1="7.23" y1="14.86" x2="9.14" y2="14.86"/><line class="cls-1" x1="7.23" y1="18.68" x2="9.14" y2="18.68"/><line class="cls-1" x1="7.23" y1="22.5" x2="9.14" y2="22.5"/></svg>
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