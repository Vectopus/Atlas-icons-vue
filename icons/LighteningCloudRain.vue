
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.45,14.85A4.7,4.7,0,0,1,1.5,12,4.78,4.78,0,0,1,6.27,7.23a5.73,5.73,0,0,1,11.46,0,6,6,0,0,1-.09.95h.56a4.29,4.29,0,0,1,4.3,4.3,4.35,4.35,0,0,1-.95,2.71"/><polygon class="cls-1" points="7.23 16.77 5.32 19.64 5.32 17.73 3.41 17.73 5.32 14.86 5.32 16.77 7.23 16.77"/><line class="cls-1" x1="18.68" y1="14.86" x2="18.68" y2="18.68"/><line class="cls-1" x1="18.68" y1="20.59" x2="18.68" y2="22.5"/><line class="cls-1" x1="14.86" y1="12.95" x2="14.86" y2="16.77"/><line class="cls-1" x1="14.86" y1="18.68" x2="14.86" y2="20.59"/><line class="cls-1" x1="11.05" y1="14.86" x2="11.05" y2="18.68"/><line class="cls-1" x1="11.05" y1="20.59" x2="11.05" y2="22.5"/></svg>
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