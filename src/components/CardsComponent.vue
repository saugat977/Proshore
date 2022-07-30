<script>
import CardComponent from '@/components/CardComponent.vue'
import cardsData from '@/data/CardsData.js'

    export default{
        name:'CardsComponent',
        components: {
            CardComponent
            },
            data(){
        return{
            data:cardsData
        }
    }
    }
    
    
</script>

<template>
<div class=" row w-100">
<CardComponent v-for="cardData in data" 
:key="cardData.title"
:cardData = "cardData"
/>
</div>

    
</template>