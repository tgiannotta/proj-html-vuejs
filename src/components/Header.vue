<template>
    <header>
        <div class="container">
            <div class="riga-header">
                <div class="logo">
                    <img src="../assets/img/white-logo-2.png" alt="Logo">
                </div>
                <nav>
                    <ul>
                        <li >
                            <a class="active" href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">About</a>
                        </li>
                        <li>
                            <a href="#">services</a>
                        </li>
                        <li>
                            <a href="#">Blog</a>
                        </li>
                        <li>
                            <a href="#">Contact</a>
                        </li>
                        <li>
                            <a href="#">Portfolio</a>
                        </li>
                        <li>
                            <button><a href="#">Sign In </a></button>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="riga-plan">
                <div class="business-plan">
                    <h3>Business Planning</h3>
                    <h3>Digital Technology</h3>
                    <h3>Modern Solution !</h3>
                    <h5>When, while the lovely valley teems with vapour around<br>meand the meridian sun strikes the upper surface.</h5>
                    <button class="try">Try it now</button>
                    <button class="explore">Explore More</button>
                </div>
                <div class="business-img">
                    <img src="../assets/img/header.png" alt="plan-img">
                </div>
            </div>

        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>



<style lang="scss" scoped>
@import "../style/variables.scss";
    
    header{
         background-color: #09154d;
         height: 900px;
   
    .container{
       

        .riga-header{
            display: flex;
            justify-content: space-between;
            padding: 20px 0px;
            height: 100px;
            .logo{
               
                img{
                    width: 200px;
                   
                    
                }
            }    
            nav{
                line-height: 100px;
                font-size: 20px;
                ul{
                    
                    display: flex;
                   li{
                       margin-right: 30px;
                       a{
                           color: $colore-primario;
                           .active{
                                color: #f9636b;  
                            }
                       } 
                    
                   }
                    
                }
            }
        }
        .riga-plan{
           position: relative;
           
            .business-plan{  
             
                position: absolute;
                        left: 0%;
                        top: 300px
                         
                     
            }  
            h3{
                color: $colore-primario;
                font-size: 60px;
                font-weight: bold;
                margin-bottom: 10px;
            }
            h5{
                color: #0495c1;
                font-size: 15px;
                margin: 50px 0px;
            }
                
        
              
            
            .business-img{
                    position: absolute;
                    right: 0%;
                    top: 100px;
                img{

                    width: 700px;
                    
                }
                
            }
        }
    }
    }
</style>