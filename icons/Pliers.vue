
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,7.23,13.91,9.14a1.91,1.91,0,0,0-3.82,0L7.23,7.23,9.14,1.5h5.72Z"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="1.5"/><path class="cls-1" d="M13.91,9.14a1.66,1.66,0,0,1,0,.32,2,2,0,0,1-1,1.36,2,2,0,0,1-1.84,0,2,2,0,0,1-1-1.36,1.66,1.66,0,0,1,0-.32,1.91,1.91,0,0,1,3.82,0Z"/><path class="cls-1" d="M10.12,9.46a5.73,5.73,0,0,0-3.85,5.4v5.73A1.93,1.93,0,0,0,8.18,22.5a1.91,1.91,0,0,0,1.91-1.91V15.45a11.26,11.26,0,0,1,1-4.63"/><path class="cls-1" d="M13.88,9.46a5.73,5.73,0,0,1,3.85,5.4v5.73a1.93,1.93,0,0,1-1.91,1.91,1.91,1.91,0,0,1-1.91-1.91V15.45a11.26,11.26,0,0,0-1-4.63"/></svg>
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