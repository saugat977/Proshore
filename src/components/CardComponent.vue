<script>
    export default{
        name:'CardComponent',
        props:['cardData'],
    data(){
        return{
             title: this.cardData.title,
             text: this.cardData.text,
             color:this.cardData.color

        }
       
    }
    }
</script>

<template>
    <div class="col-4  p-4 d-flex justify-content-center" :style="{'background-color': color}">
        <div class="card cards-card border border-light border-3  text-white p-2 text-center d-flex justify-content-center align-items-center " :style="{'background-color': color}">
  <div class="card-body cards-card-body ">
    <h5 class="card-title ">{{title}}</h5>
    <div class="card-title-border"></div>
    <p class="card-text mt-3">{{text}}</p>
  </div>
</div>
    </div>
</template>