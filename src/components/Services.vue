<template>
    <div class="services-container">
        <div class="intestazione">
            <h5>Our Services</h5>
            <h3>What we do</h3>
            <p>When, while the lovely valley teems with vapour around mind the </p>
        </div>
        <div class="colonne-container">
            <div class="colonne-servizi">
                <div class="colonna-singola">
                    <img src="../assets/img/Group-538.png" alt="img1">
                    <h4>Data Analysis</h4>
                    <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface. </p>

                </div>
                 <div class="colonna-singola">
                    <img src="../assets/img/Group-538.png" alt="img2">
                    <h4>Securiy Data</h4>
                    <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface. </p>

                </div>
                 <div class="colonna-singola">
                    <img src="../assets/img/Group-566.png" alt="img3">
                    <h4>Branding Strategy</h4>
                    <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface. </p>

                </div>
                <div class="colonna-singola">
                    <img src="../assets/img/Group-567.png" alt="img4">
                    <h4>Seo Optimitation</h4>
                    <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface. </p>

                </div>
               
               
            </div>
        </div>
        <button class="try">View all services</button>
    </div>
</template>


<script>
export default {
    name: 'Services',
}
</script>



<style lang="scss" scoped>
@import "../style/variables.scss";

    .services-container{
        position: relative;
        background-color: white;
        height: 800px;
        .intestazione{
            text-align: center;
            margin-top: 50px;
            h5{
                color: $colore-secondario;
                font-size: 20px;
                margin-bottom: 10px;
            }
            h3{
                font-size: 50px;
                margin-bottom: 10px;

            }
            p{
                font-size: 20px;
            }

        }
        .colonne-container{
            width: 80%;
            margin:auto;
       
            .colonne-servizi{
            
                margin-top: 50px;
                display: flex;
                justify-content: space-between;
           
            }
        .colonna-singola h4{
            text-align: center;
            font-size: 30px;
            margin: 30px 0px;
         
           
        }
        .colonna-singola img{
            width: 150px;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
       .colonna-singola p{
           text-align: center;
           font-size: 20px;
       }
        }
       button{
           position: absolute;
           top: 80%;
           left: 45%;
       }
    } 

</style>