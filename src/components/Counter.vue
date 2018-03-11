<template>
    <div>
        <button class="btn btn-primary" @click="increment">Increment1</button>
        <button class="btn btn-primary" @click="decrement">Decrement1</button>
    </div>
</template>

<script>
    import {mapMutations} from 'vuex'
    export default {
        methods: {
            ...mapMutations([
                    'increment',
                    'decrement'
                ])
        }
    }
</script>