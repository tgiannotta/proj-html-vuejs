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
                </div>
                <div class="single-people">
                                     <img src="../assets/img/fabio.png" alt="fabio">

                </div>
                <div class="single-people">
                                <img src="../assets/img/fabio.png" alt="fabio">

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
    .single-people{
        width: calc(100% / 3);
        height: 150px;
    border: 1px solid black;
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
    }

}
</style>