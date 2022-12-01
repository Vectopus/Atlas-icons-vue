
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.55,1.5h1.9A1.9,1.9,0,0,1,4.36,3.41V18.68H23.45"/><circle class="cls-1" cx="8.18" cy="20.59" r="1.91"/><circle class="cls-1" cx="18.68" cy="20.59" r="1.91"/><rect class="cls-1" x="8.18" y="8.18" width="13.36" height="10.5" rx="2"/><polygon class="cls-1" points="18.68 8.18 11.04 8.18 12.14 4.36 17.59 4.36 18.68 8.18"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="18.68"/><line class="cls-1" x1="17.73" y1="11.05" x2="17.73" y2="18.68"/></svg>
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