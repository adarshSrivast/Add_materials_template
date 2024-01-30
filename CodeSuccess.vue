<template>
    <div class="offset-xl-2 col-xl-8 offset-md-1 col-md-10">
        <section class="activation-code-success">
            <div class="circle">
                <i class="nemo-font nemo-activate-code page-icon fa fa-file" aria-hidden="true"></i>
            </div>
            <h2 class="heading2"> Your code has been activated </h2>
            <div class="content-div-body">
                <p class="emphasize-text mb-3"> You now have access to the following material for <strong>40 months</strong>: </p>
                <p class="mb-0">
                    <strong>CQA PE amd Ebook Umbrella</strong>
                </p>
                <p class="emphasize-text mt-3">Your subscription will end on <strong>Apr 26, 2027</strong></p>
                <p> One last step and you can start learning </p>
                <a class="btn btn-lg btn-white-bg btn-icon mb-2 mt-3" @click="handleCLick()">
                    Learn on my own
                    <i class="fa fa-angle-right" aria-hidden="true"></i>
                </a>
                
            </div>
        </section>
        <section>
            <h2 class="heading2 text-uppercase"> <a href=""> I'M LEARNING WITH A CLASS</a> </h2>
        </section>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

// @import "../assets/scss/helper.scss";
.content-div-body {
    margin: 0 20px;
    @include media-breakpoint-up(sm) {
        width:70%;
        margin: 0 auto;
    }
     @include media-breakpoint-up(lg) {
        width:60%;
    }
}
.heading2 {
    margin: 15px 0 30px 0;
}
.activation-code-success {
    @include media-breakpoint-up(md) {
        padding-top:30% !important;
    }
    @include media-breakpoint-up(lg) {
        padding-top:30px !important;
    }
    .circle {
        background-color: #82C632;
        color: var(--cup-general-color-1);
        width: 112px;
        height: 112px;
        border-radius: 50%;
        margin: 0px auto 12px;
        .page-icon {
            margin:30px 40px;
        }
        @include media-breakpoint-up(lg) {
            margin-top:40px;
        }
    }
}
</style>