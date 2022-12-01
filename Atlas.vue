<template>
    <component :is="dynamicComponent" :size=size :weight="fontWidth[weight]? fontWidth[weight]: fontWidth.medium "/>
</template>

<script>
import { defineAsyncComponent } from "vue";
import FontWidth from "./font-width"

export default {
    
    props: {
        icon: {
            type: String,
            required: true,
        },
        size: {
            type: Number,
            default: 24
        },
        weight: {
            type: String,
            default: "medium"
        }
    },

    data: () => {
        return {
            fontWidth: FontWidth
        }
    },

    computed: {
        dynamicComponent() {
            return defineAsyncComponent(() => import(`./icons/${this.icon}.vue`));
        },
    },
};
</script>