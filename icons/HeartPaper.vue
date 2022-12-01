
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.74,5.06A2.08,2.08,0,0,0,12,6,2.08,2.08,0,0,0,8.18,7.14c0,3.12,3.82,4.17,3.82,4.17s3.82-1.05,3.82-4.17A2.08,2.08,0,0,0,13.74,5.06Z"/><polygon class="cls-1" points="20.59 22.5 3.41 22.5 3.41 1.5 20.59 1.5 20.59 6.27 20.59 22.5"/><line class="cls-1" x1="7.23" y1="14.86" x2="16.77" y2="14.86"/><line class="cls-1" x1="7.23" y1="18.68" x2="16.77" y2="18.68"/></svg>
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