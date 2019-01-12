<template>
    <div class="container">
        <appQuoteGrid></appQuoteGrid>
    </div>
</template>

<script>
import QuoteGrid from './component/QuoteGrid.vue';
    export default {
        components: {
            appQuoteGrid: QuoteGrid
        },
        data(){
            return {
                quotes: [
                    'Just a Quote to see something'
                ],
                maxQuotes: 10
            }
        }
    }
</script>

<style>
</style>
