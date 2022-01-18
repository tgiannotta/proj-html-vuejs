<template>
    <header>
        <div class="container">
        <div class="riga-header">
            <div class="logo">
                <h2>Logo</h2>
            </div>
            <nav>
                <ul>
                    <li>
                        <a href="#">Prova</a>
                    </li>
                     <li>
                        <a href="#">Prova</a>
                    </li>
                     <li>
                        <a href="#">Prova</a>
                    </li>
                     <li>
                        <a href="#">Prova</a>
                    </li>
                     <li>
                        <a href="#">Prova</a>
                    </li>
                     <li>
                        <a href="#">Prova</a>
                    </li>
                    <li>
                        <button>Prova</button>
                    </li>
                </ul>
            </nav>
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
    *{
        color: $colore-primario;
    }
    
    .container{
        background-color: #09154d;
        height: 500px;
        .riga-header{
            display: flex;
            justify-content: space-between;
            nav{
                ul{
                    display: flex;
                    
                }
            }
        }

    }
</style>