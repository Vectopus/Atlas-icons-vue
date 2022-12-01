
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.22,16.77h-6A1.79,1.79,0,0,1,2.45,15h0a2.11,2.11,0,0,1,0-.25L4.15,3A1.77,1.77,0,0,1,5.91,1.5h4.31A1.78,1.78,0,0,1,12,3.28V15A1.78,1.78,0,0,1,10.22,16.77Z"/><path class="cls-1" d="M13.78,16.77h6A1.79,1.79,0,0,0,21.55,15h0a2.11,2.11,0,0,0,0-.25L19.85,3A1.77,1.77,0,0,0,18.09,1.5H13.78A1.78,1.78,0,0,0,12,3.28V15A1.78,1.78,0,0,0,13.78,16.77Z"/><path class="cls-1" d="M5.32,16.77H9.14a0,0,0,0,1,0,0v3.82A1.91,1.91,0,0,1,7.23,22.5h0a1.91,1.91,0,0,1-1.91-1.91V16.77A0,0,0,0,1,5.32,16.77Z"/><path class="cls-1" d="M14.86,16.77h3.82a0,0,0,0,1,0,0v3.82a1.91,1.91,0,0,1-1.91,1.91h0a1.91,1.91,0,0,1-1.91-1.91V16.77a0,0,0,0,1,0,0Z"/></svg>
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