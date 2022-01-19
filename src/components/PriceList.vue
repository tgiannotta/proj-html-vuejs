<template>
    <div class="price-container">
        <div class="description">
            <h5>Price List</h5>
            <h3>Our Pricing</h3>
            <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface.</p>
        </div>
        
        <div class="table">
            <div class="single-table">
                <h3>Designing</h3>
                <h4 class="mrg-bot-30">Process</h4>
                <p class="pos-abs">$</p>
                <h2>40</h2>
                <p class="mrg-bot-30">Per Month</p>
                <p class="mrg-bot-10"><span class="bold">Creative</span> Design Enabled</p>
                <p class="mrg-bot-10"><span class="bold">vibrant</span> Color Usage</p>
                <p class="mrg-bot-10"><span class="bold">Eye</span> Catching Desing</p>
                <p class="mrg-bot-10"><span class="bold">Extreme</span> Typoehy</p>
                <p class="mrg-bot-30"><span class="bold">Exceptional</span> Design</p>
                <button class="try"><a href="#">Order Now &emsp;&emsp;<i class="fas fa-arrow-right"></i></a></button>

                
            </div>
            <div class="single-table middle">
                <h3>Developing</h3>
                <h4 class="mrg-bot-30">Process</h4>
                <p class="pos-abs">$</p>
                <h2>60</h2>
                <p class="mrg-bot-30">Per Month</p>
                <p class="mrg-bot-10"><span class="bold">Creative</span> Design Enabled</p>
                <p class="mrg-bot-10"><span class="bold">vibrant</span> Color Usage</p>
                <p class="mrg-bot-10"><span class="bold">Eye</span> Catching Desing</p>
                <p class="mrg-bot-10"><span class="bold">Extreme</span> Typoehy</p>
                <p class="mrg-bot-30"><span class="bold">Exceptional</span> Design</p>
                <button class="white"><a class="white" href="#">Order Now &emsp;&emsp;<i class="fas fa-arrow-right"></i></a></button>
            </div>
            <div class="single-table">
                <h3>Supporting</h3>
                <h4 class="mrg-bot-30">Process</h4>
                <p class="pos-abs">$</p>
                <h2>80</h2>
                <p class="mrg-bot-30">Per Month</p>
                <p class="mrg-bot-10"><span class="bold">Creative</span> Design Enabled</p>
                <p class="mrg-bot-10"><span class="bold">vibrant</span> Color Usage</p>
                <p class="mrg-bot-10"><span class="bold">Eye</span> Catching Desing</p>
                <p class="mrg-bot-10"><span class="bold">Extreme</span> Typoehy</p>
                <p class="mrg-bot-30"><span class="bold">Exceptional</span> Design</p>
                <button class="try"><a href="#">Order Now &emsp;&emsp;<i class="fas fa-arrow-right"></i></a></button>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'PriceList',
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.price-container{
    height: 500px;
    background-color: $colore-terziario;
   /*  color: $colore-primario; */
    text-align: center;
    padding-top: 50px;
    h5{
        color: $colore-secondario;
        font-size: 15px;
    }
    h3{
        margin: 20px 0px;
        font-size: 30px;
    }
    .price-container > p{
        font-size: 15px;
        margin-bottom: 50px;
    }
    .table{
        display: flex;
        width: 80%;
        margin: auto;
        .single-table{
            position: relative;
            width: calc(100% / 3);
             height: 600px;
            background-color: white;
            text-align: center;
            color: black;
            border: 1px solid black;
            border-radius: 10%;
            margin: 2px 0px;
            h3{
                margin-top: 20px;
                margin-bottom: 10px;
                font-size: 50px;
            }
          

        }
        .middle{
            margin: 2px 50px;
            background-color: $colore-secondario;
            
        }
        .pos-abs{
            top: 130px;
            left: 150px;
        }
        h2{
            font-size: 100px;
        }
        p{
            font-size: 20px;
        }
       
        
        

        
        
        
    }
     .description{
            margin-bottom: 50px;
        }
  
      
}

</style>