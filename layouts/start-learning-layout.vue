<template>
    <main class="container-fluid px-0">
        <div class="start-learning-header">
            <a target="_blank">
                <i class="fa fa-question-circle"></i>
            </a>
            <h1>Start Learning</h1>
            <a href="" @click="handleClick()">
                <i class="fa fa-times"></i>
            </a>
        </div>
    </main>

    <slot/>
</template>

<style scoped>
.container-fluid {
    background-color: #8723ff;
    color: white;
}
.start-learning-header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 56px;
    padding: 0px 16px;
}

h1{
    font-size: 12px;
    line-height: 14px;
}

i{
    color: white;
}
@media(min-width : 768px){
    .start-learning-header{
        padding: 0px 32px;
    }

}

@media(min-width : 992px){
    .start-learning-header{
        padding: 0px 24px;
    }
}

@media(min-width : 1280px){
    .container-fluid{
        display: flex;
        justify-content: center;
    }
    .start-learning-header{
        min-width : 1280px;
    }

}

</style>

<script setup>


</script>