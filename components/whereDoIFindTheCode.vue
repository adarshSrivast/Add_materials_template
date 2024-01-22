<template>
    <main class="container-fluid">
        <div class="start-learning-wrapper">
            <div class="start-learning">
                <i class=" fa fa-file start-learning-icon"></i>
                <h2 class="start-learning-heading">Where do i find the code?</h2>
                <div class="start-learning-content">
                    <p class="start-learning-code-description">You can find a 16-digit activation code on the inner cover of your Book or get it from your teacher</p>
                    
                    <button class="start-learning-activate-button">
                        <span class="start-learning-activate-button-text">Activate later</span>
                        <i class="fa fa-angle-right start-learning-activate-button-icon"></i>
                    </button>
                </div>
            </div>
            <div class="start-learning-activation">
                <h2 class="start-learning-heading start-learning-code-found-text">OK, I found the activation code</h2>
            </div>
        </div>
    </main>
</template>

<script setup>

</script>

<style scoped>
*{
    box-sizing: border-box;
}

.container-fluid{
    height: 100vh;
    background-color: var(--cup-main-color-1);
    background-color: #8723ff;
    color: var(--general-main-color-1);
    color : white;
    padding : 0px 15px;
    font-size: 14px;
    font-family: Muli,sans-serif;
}

.start-learning{
    text-align: center;
    border-bottom: 1px solid var(--cup-general-color-1);
    border-bottom: 1px solid white;
    padding: 30px 0;
}

.start-learning-icon{
    font-size: 48px;
    margin-bottom : 24px;
}

.start-learning-heading{
    font-size: 14px;
    line-height: 16px;
    font-weight: 600;
    letter-spacing: .5px;
    margin: 15px 0px 30px;
    color: inherit;
}

.start-learning-content{
    margin: 0px 20px;
}

.start-learning-code-description{
    line-height: 1.5;
}
.start-learning-activate-button{
    background-color: white;
    /* background-color: var(--cup-general-color-1); */
    /* color: var(--cup-general-color-1); */
    color: #8723ff;
    border-radius: 24px;
    border: none;
    padding: 14px 20px 14px 25px;
    margin-top: 16px;
    margin-bottom: 48px;
}

.start-learning-activate-button-text{
    font-weight: 700;
    letter-spacing: 0.5px;
}

.start-learning-activate-button-icon{
    font-size: 20px;
    margin-left: 10px;
}

.start-learning-activation{
    padding : 30px 0px;
    text-align: center;
}

.start-learning-code-found-text{
    cursor: pointer;
}

@media (min-width: 576px){
    .start-learning-content {
        width: 70%;
        margin: 0 auto;
    }
}

@media( min-width: 768px){
    .container-fluid{
        overflow: scroll;
    }
    .start-learning{
        /* flex: 0 0 83.3333333333%; */
        max-width: 83.3333333333%;
        margin-left: 8.3333333333%;
        padding-top: 35%;
    }
}

@media( min-width: 992px){
    .start-learning-icon{
        margin: 40px 0;
    }
    .start-learning-wrapper{
        margin-top: 20px;
    }
    .start-learning{
        padding-top: 30px;
        width: 992px;
    }
    .start-learning-content{
        width: 50%;
    }
}

@media(min-width : 1280px){
    .container-fluid{
        display: flex;
        justify-content: center;
    }
    .start-learning-wrapper{
        max-width: 1280px;
    }
}



</style>