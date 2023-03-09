<script lang="ts">
import { defineComponent, onBeforeMount, onMounted } from 'vue';

export default defineComponent({
    setup() {
        const msg = "Hello World!"

        console.log("This is first console output")

        onBeforeMount(() => {
            console.log("This is from onBeforeMount function")
        })

        onMounted(() => {
            console.log("This is from onMounted function")
        })

        console.log("This is second console output")

        return {
            msg,
        }
    }
})
</script>

<template> m
    <h1>
        {{ msg }}
    </h1>
</template>

<style scoped>
.read-the-docs {
    color: #888;
}
</style>
