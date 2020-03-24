<template>
    <section class="section-hero section-shaped my-0">
        <div class="shape shape-style-1 shape-primary">
            <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
        </div>
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <div class="col-lg-12 text-center pt-lg">
                        <img src="img/brand/r_logo_red.png" style="width: 30%;" class="img-fluid">
                        <marquee-text>
                            <p class="lead text-white mt-4 mb-5" id="msg">{{ msg }}</p>
                        </marquee-text>
                        <div class="btn-wrapper">
                            <base-button tag="a"
                                         href="https://www.linkedin.com/in/ringgicahyo/"
                                         class="mb-3 mb-sm-0"
                                         type="primary"
                                         icon="fa fa-linkedin">
                                Follow LinkedIn
                            </base-button>
                            <base-button tag="a"
                                         href="https://instagram.com/ringgicahyoo"
                                         class="mb-3 mb-sm-0"
                                         type="neutral"
                                         icon="fa fa-instagram">
                                Follow Instagram
                            </base-button>
                        </div>
                    </div>
                </div>
                <div class="row align-items-center justify-content-around stars-and-coded">
                    <div class="col-sm-4">
                        <span class="text-white alpha-7 ml-3">Visit me on <i class="fa fa-github-alt"></i></span>
                        <a href="https://github.com/ringgicahyo" target="_blank" title="Support me on Github">
                            <img src="img/brand/github-white-slim.png" style="height: 22px; margin-top: -3px">
                        </a>
                    </div>
                    <div class="col-sm-4 mt-4 mt-sm-0 text-right">
                        <span class="text-white alpha-7">Developed with </span><i class="fa fa-heart"></i>
                        <span class="text-white alpha-7"> by</span>
                        <a href="http://ringgicahyo.web.id" target="_blank" title="Ringgi Cahyo">
                            <img src="img/brand/r_logo_red.png" class="ml-1" style="height: 30px;">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    data () {
        return {
            msg: '| This website is currently under development. Thank you for visiting. Please come back later. |'
        }
    }
};
</script>
<style>
#msg {
    font-weight: 400;
}
</style>
