
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,1.5h1.91a0,0,0,0,1,0,0V7.23a0,0,0,0,1,0,0H15.82a1.91,1.91,0,0,1-1.91-1.91V3.41A1.91,1.91,0,0,1,15.82,1.5Z"/><line class="cls-1" x1="21.55" y1="2.45" x2="17.73" y2="2.45"/><line class="cls-1" x1="21.55" y1="6.27" x2="17.73" y2="6.27"/><polygon class="cls-1" points="11.04 11.04 9.14 13.91 11.04 13.91 11.04 11.04"/><polygon class="cls-1" points="12 15.82 13.91 12.96 12 12.96 12 15.82"/><path class="cls-1" d="M20.59,13.43a9.07,9.07,0,1,1-9.07-9.07h2.39"/></svg>
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