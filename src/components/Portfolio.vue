<template>
    <div class="portfolio-container">
        <div class="descrizione">
            <h5>Portfolio</h5>
            <h3>Latest work</h3>
        </div>
     
     
        
        
    </div>
</template>

<script>
export default {
    name: 'Portfolio',

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.portfolio-container{
    height: 600px;
    background-color: white;
    .descrizione{
        width: 80%;
        margin: auto;
        padding-top: 70px ;
        h5{
            font-size: 20px;
            color: $colore-secondario;
        }
        h3{
            font-size: 30px;
            padding: 15px 0px;
        }
    }
    
}
</style>