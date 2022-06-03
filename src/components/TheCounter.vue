<template>
    <h3>{{ finalCounter }} </h3>
</template>

<script>
// import { mapGetters } from "vuex";

export default {
    computed: {
        finalCounter() {
            return this.$store.getters['numbers/finalCounter']
        }

        // ...mapGetters('numbers', ['finalCounter'])
    },
}
</script>