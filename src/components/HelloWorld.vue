<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    setup() {
        const msg = "Hello World!"

        return {
            msg
        }
    }
})
</script>

<template>
    <h1>
        {{ msg }}
    </h1>
</template>

<style scoped></style>
