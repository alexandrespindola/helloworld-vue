<template>
    <div class="is-flex is-flex-direction-column is-align-items-center">
        <h3 class="has-text-centered"> {{ counter }}</h3>
        <button class="" @click="addCounter">Incrementar</button>
    </div>
</template>

<script lang="ts">

import { defineComponent } from 'vue'
export default defineComponent({
    name: 'CounterOption',
    data() {
        let counter = 0;
        return { counter }
    },
    methods: {
        addCounter() {
            this.counter++
        }
    }
})
</script>

<style></style>