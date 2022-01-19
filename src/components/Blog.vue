<template>
    <div class="blog-container">
        <div class="descrizione">
            <h5>Blog</h5>
            <h3>Latest Posts</h3>
            <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface.</p>
            

        </div>
        <div class="table">
                <div class="single-table-sx">
                    <h5>April,212019 · by Paul</h5>
                    <h3>Amazon gets CCI nod to acquire 49% stake in</h3>
                    <p>When, while the lovely valley teems with vapour around<br>meand the meridian sun s...</p>
                    <button class="white">Read more</button>
                </div>
                 <div class="single-table middle">
                     <h5>April,212019 · by Paul</h5>
                    <h3>Amazon gets CCI nod to <br>acquire 49% stake in</h3>
                    <p>When, while the lovely valley <br> teems with vapour around<br>meand the meridian sun s...</p>
                    <button class="white">Read more</button>

                </div>
                 <div class="single-table">
                     <h5>April,212019 · by Paul</h5>
                    <h3>Amazon gets CCI nod to <br> acquire 49% stake in</h3>
                    <p>When, while the lovely valley<br> teems with vapour around<br>meand the meridian sun s...</p>
                    <button class="white">Read more</button>

                </div>

            </div>
    </div>
</template>

<script>
export default {
    name:'Blog',
}
</script>


<style lang="scss" scoped>
@import "../style/variables.scss";

.blog-container{
    background-color: white;
    height: 800px;
    margin-top: 600px;
    .descrizione{
        text-align: center;
        h5{
            color: $colore-secondario;
            font-size: 20px;
            padding-bottom: 20px;
        }
        h3{
            font-size: 60px;
            padding-bottom: 30px;

        }
        p{
            font-size: 20px;
            padding-bottom: 30px;


        }
    }
    .table{
        display: flex;
        width: 80%;
        margin: auto;
        padding-top: 50px;
        color: white;
        .single-table-sx{
            position: relative;
            width:50%;
             height: 400px;
            background-image: url("../assets/img/personpc.jpg");
            background-size: cover;
            filter: grayscale(70%);
            border-radius: 5%;
            margin: 2px 0px;
            h5{
                position: absolute;
                bottom: 90px;
                left: 60px;
                font-size: 15px;
            }
            h3{
                position: absolute;
                left: 60px;
                bottom: 55px;
                font-size: 20px;
            }
            p{
                position: absolute;
                left:60px;
                bottom: 5px;
                font-size: 20px;
            }
            button{
                position: absolute;
                right: 5px;
                bottom:10px
            }
        }
    }   .single-table{
            position: relative;
            width: 25%;
             height: 400px;
            background-color: $colore-terziario;
            border-radius: 5%;
            margin: 2px 0px;
            h5{
                position: absolute;
                left: 30px;
                top: 30px;
                font-size: 16px;
            }
            h3{
                position: absolute;
                left: 30px;
                top: 80px;
                font-size: 20px;
            }
            p{
                position: absolute;
                left: 30px;
                top: 160px;
            }
            button{
                position: absolute;
                left: 30px;
                bottom: 10px;
            }
            
            }
            .middle{
                margin: 2px 50px;
        }  
}
</style>