<template>
    <div id="jumbotron">
        <h3 class="text-center">Questo è un jumbotron interessantissimo!</h3>
        <div class="container">
            <span>E' stato creato con Vite e Vue</span>
            <div>
                <img src="/vite.svg" alt="Logo di vite">
                <img src="../assets/vue.svg" alt="Logo di vue">
            </div>
        </div>
    </div>
</template>

<style>
#jumbotron {
    width: 50%;
    height: 200px;
    margin: auto;
    background-color: rgba(77, 170, 170, 0.6);
    border-radius: 6px;
}

#jumbotron h3 {
    font-size: 20px;
    padding: 20px;
    text-align: center;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.container span {
    font-weight: 600;
}

.container div img {
    width: 60px;
    padding: 15px;
}
</style>