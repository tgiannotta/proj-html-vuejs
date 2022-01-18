<template>
    <footer>
        <div class="container">
            <div class="riga-footer">
                <div class="single-link">
                    <h2>prova</h2>
                </div>
                <div class="single-link">
                    <h2>prova</h2>
                </div>
                <div class="single-link">
                    <h2>prova</h2>
                </div>
                <div class="single-link">
                    <h2>prova</h2>
                </div>

            </div>
        </div>
    </footer>
</template>


<script>
export default {
    name: 'Footer',
}
</script>


<style lang="scss" scoped>
@import "../style/variables.scss";

.container{
    height: 300px;
    background-color: #09154d;
    color: $colore-primario;
    .riga-footer{
        display: flex;
        justify-content: space-between;
}
}

</style>