<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
                <h1>Vuex</h1>
                <app-result ></app-result>
                <NewResult></NewResult><br>

                <hr>
                <app-counter ></app-counter><br>
                <another-counter></another-counter>
            </div>
        </div>
    </div>
</template>

<script>
    import Counter from './components/Counter.vue';
    import Result from './components/Result.vue';
    import NewResult from './components/NewResult.vue';
    import anotherCounter from './components/anotherCounter.vue'


    export default {
        
        components: {
            appCounter: Counter,
            appResult: Result,
            NewResult,
            anotherCounter
        }
    }
</script>

