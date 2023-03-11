<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    props: {
        msg: String,
    },
    setup() {
        const info = "This is sihaixianyu's personal blog."

        return {
            info
        }
    }
})
</script>

<template>
    <h1>{{ msg }}</h1>
    <p>{{ info }}</p>
</template>

<style scoped></style>
