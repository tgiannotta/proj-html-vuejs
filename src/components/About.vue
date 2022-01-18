<template>
    <div class="about-container">
       <div class="area-business">
           <div class="business-img">
               <img src="../assets/img/men-data.png" alt="img6">
               <div class="immagine-sovrapposta">
                <img src="../assets/img/nemoodar.png" alt="">

               </div>
           </div>
           <div class="business-plan">
               <h5>Start your project</h5>
               <h3>Grow your business</h3>
               <h3>With Our Strategy</h3>
               <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface.<br>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface.</p>
               <button class="try"> <a href="#">Try it now</a> </button>
               <button class="explore"><a href="#">Explore More</a></button>
           </div>
       </div>
    </div>
</template>

<script>
export default {
    name: 'About',
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.about-container{
    background-color: $colore-terziario;
    height: 650px;
    .area-business{
        width: 60%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        position: relative;
        .business-img{
            position: relative;
        }
        .business-img img{
            position: absolute;
            width: 400px;
            top: 150px;
            left: 100px;
            z-index: 1;
        }

        .business-plan{
            position: absolute;
            color: $colore-primario;
            right: 0px;
            top: 150px;
        }
        h5{
            margin-bottom: 30px;
            font-size: 15px;
        }
        h3{
            font-size: 50px;
        }
        p{
            margin: 30px 0px;
            color: $colore-quarto;
            font-size: 20px;
        }
        .immagine-sovrapposta{
            position: relative;
            img{
                position: absolute;
                top: 75px;
                left: 70px;
                z-index: 0;
            }
        }
    }

   
}
</style>