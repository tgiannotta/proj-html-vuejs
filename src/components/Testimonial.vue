<template>
<div class="testimonial-container">

        <div class="descrizione">
                <h5>Testimonial</h5>
                <h3>What people Say</h3>
                <p>When, while the lovely valley teems with vapour around>meand the meridian sun surface</p>
        </div>
        <div class="people-cards">
                <div class="single-people">
                    <img src="../assets/img/fabio.png" alt="fabio">
                        <div class="elementi">
                            <h3>3 STELLE SU 5</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <h3>Michael Angel</h3>
                            <p>Michael Angel</p>
                        </div>
                </div>
                <div class="single-people">
                                     <img src="../assets/img/filip.png" alt="fabio">
                                      <div class="elementi">
                            <h3>3 STELLE SU 5</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <h3>Michael Angel</h3>
                            <p>Michael Angel</p>
                        </div>

                </div>
                <div class="single-people">
                                <img src="../assets/img/viktor.png" alt="fabio">
                                 <div class="elementi">
                            <h3>3 STELLE SU 5</h3>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <h3>Michael Angel</h3>
                            <p>Michael Angel</p>
                        </div>

                </div>
        </div>
        <div class="pubblicita-container">
            <div class="icone-pubblicita">
                <img src="../assets/img/client1.png" alt="1">                
            </div>
             <div class="icone-pubblicita">
                <img src="../assets/img/client2.png" alt="2">                
            </div>
             <div class="icone-pubblicita">
                <img src="../assets/img/client3.png" alt="3">                
            </div>
             <div class="icone-pubblicita">
                <img src="../assets/img/client4.png" alt="4">                
            </div>
             <div class="icone-pubblicita">
                <img src="../assets/img/client5.png" alt="5">                
            </div>
        </div>
</div>
    
</template>

<script>
export default {
    name: 'Testimonial'
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

.descrizione{
    text-align: center;
    margin-bottom: 100px;
    h5{
        color: $colore-secondario;
        padding-bottom: 20px;
        font-size: 20px;
    }
    h3{
        font-size: 30px;
        padding-bottom: 20px;

    }
    p{
        font-size: 20px;
        margin-bottom: 20px;
    }
}
.people-cards{
    display: flex;
    width: 80%;
    margin: auto;
    padding-bottom: 400px;
    .single-people{
        width: calc(100% / 3);
        height: 150px;
    position: relative;

        img{
            position: absolute;
            width: 150px;
            height: 150px;
            border: 5px solid purple;
            border-radius: 50%;
            top: 0px;
            left: 180px;
        }
        .elementi{
            position: absolute;
            top: 170px;
            left: 185px;
            h3{
                font-size: 20px;
                padding: 20px 0px;
            }
            p{
                font-size: 18px;
            }
        }
    }

}
.pubblicita-container{
    width: 70%;
    margin:auto;
    display: flex;
    .icone-pubblicita{
        width: calc(100% / 5);
        img{
            width: 150px;
            height: 100px;
        }
        
    }
}
</style>