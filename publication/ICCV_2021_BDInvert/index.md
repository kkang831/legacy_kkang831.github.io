---
layout: splash
author_profile: False
title: "BDInvert"
---

<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>BDInvert</title>
        <!-- Font Awesome icons (free version)-->
        <script src="https://use.fontawesome.com/releases/v5.13.0/js/all.js" crossorigin="anonymous"></script>
        <!-- Google fonts-->
        <link href="https://fonts.googleapis.com/css?family=Merriweather+Sans:400,700" rel="stylesheet" />
        <link href="https://fonts.googleapis.com/css?family=Merriweather:400,300,300italic,400italic,700,700italic" rel="stylesheet" type="text/css" />
        <!-- Third party plugin CSS-->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.min.css" rel="stylesheet" />
        <!-- Core theme CSS (includes Bootstrap)-->
        <link href="css/styles.css" rel="stylesheet" />
    </head>

    <body id="page-top">
        <!-- ###################################################################################################################
        Navigation bar
        ################################################################################################################### -->
        <nav class="navbar navbar-expand-lg navbar-dark bg-secondary sticky-top px-5" id="mainNav">
        <!-- navbar-dark or navbar-light change button color (of small view) -->
        <!-- navbar-secondary change the navbar background color -->
            <div class="container">
                <a class="navbar-brand js-scroll-trigger" href="#page-top">BDInvert</a>
                <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav ml-auto my-2 my-lg-0">
                        <li class="nav-item active"><a class="nav-link js-scroll-trigger" href="#abstract">Abstract</a></li>
                        <!-- <li class="nav-item active"><a class="nav-link js-scroll-trigger" href="#bibtex">Bibtex</a></li> -->
                        <li class="nav-item active"><a class="nav-link js-scroll-trigger" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>

        <!-- ###################################################################################################################
        Title
        ################################################################################################################### -->
        <div class="container d-block d-sm-block mt-5 pt-5">
            <div class="row h-100 align-items-center justify-content-center text-center">
                <div class="col-lg-10 col-md-10 align-self-center">
                    <h1 class="text-black font-weight-bold">GAN Inversion for Out-of-Range Images with Geometric Transformations</h1>
                    <hr class="divider my-4 align-center" />
                    <h1 class="text-black font-weight-bold">ICCV 2021</h1>
                    <!-- author -->
                    <div class="row font-weight-bold mt-5">
                        <div class="col-lg-4 col-md-4 text-center text-black">
                            <a class="d-block" href="{{site.url}}">Kyoungkook Kang</a>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center text-black">
                            <a class="d-block" href="{{site.seongtae}}">Seongtae Kim</a>
                        </div>
                        <div class="col-lg-4 col-md-4 text-center text-black">
                            <a class="d-block" href="{{site.scho}}">Sunghyun Cho</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row justify-content-center mb-5">
                <div class="col-lg-3 col-md-4 text-center">
                    <div class="mt-5">
                        <a style="color: inherit;" href="paper.pdf"><i class="far fa-4x fa-file text-black mb-4"></i></a>
                        <h3 class="h4 mb-2"><a style="color: inherit;"  href="paper.pdf">Paper</a></h3>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 text-center">
                    <div class="mt-5">
                        <a style="color: inherit;"  href="supple.pdf"><i class="far fa-4x fa-file text-black mb-4"></i></a>
                        <h3 class="h4 mb-2"><a style="color: inherit;"  href="supple.pdf">Supplementary</a></h3>
                    </div>
                </div>
                <div class="col-lg-3 col-md-4 text-center">
                    <div class="mt-5">
                        <a style="color: inherit;"  href="https://github.com/kkang831/BDInvert_Release"><i class="fab fa-4x fa-github text-black mb-4"></i></a>
                        <!-- <h3 class="h4 mb-2"><a style="color: inherit;"  >Code</a></h3> -->
                        <h3 class="h4 mb-2"><a style="color: inherit;"  href="https://github.com/kkang831/BDInvert_Release">Code</a></h3>
                    </div>
                </div>
            </div>
            <div class="mt-5">
                <img src="teaser.png" class="rounded mx-auto d-block" alt="..." style="width: 90%;">
            </div>
        </div>

        <!-- ###################################################################################################################
        Abstract
        ################################################################################################################### -->
        <section class="about bg-white pt-5" id="abstract">
            <div class="pt-5 pb-5"></div>
            <div class="container text-center">
                <div class="row justify-content-center">
                    <div class="col-lg-12 text-center">
                        <h2 class="text mt-0">Abstract</h2>
                        <hr class="divider my-4 align-center" />
                    </div>
                    <div class="col-lg-12 text-justify">
                        <p class="text-50-justify mb-4" style="font-size: 20px;">
                        For successful semantic editing of real images, it is critical for a GAN inversion method to find an in-domain latent code that aligns with the domain of a pre-trained GAN model. Unfortunately, such in-domain latent codes can be found only for in-range images that align with the training images of a GAN model. In this paper, we propose BDInvert, a novel GAN inversion approach to semantic editing of out-of-range images that are geometrically unaligned with the training images of a GAN model. To find a latent code that is semantically editable, BDInvert inverts an input out-of-range image into an alternative latent space than the original latent space. We also propose a regularized inversion method to find a solution that supports semantic editing in the alternative space. Our experiments show that BDInvert effectively supports semantic editing of out-of-range images with geometric transformations.
                        </p>
                    </div>
                </div>
                <!-- <div class="mt-5 col-md-12 col-lg-12">
                    <img src="assets/img/qualatitive_result_web.png" class="rounded mx-auto d-block" alt="..." style="width: 100%;">
                </div> -->
            </div>
        </section>

        <!-- ###################################################################################################################
        Bibtex
        ################################################################################################################### -->
        <!-- <div class="pb-5"></div>
        <div class="container mt-5" id="bibtex">
            <h2 class="text-center">Bibtex</h2>
            <hr class="divider my-4 align-center" />
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">@inproceedings{rim_2020_ECCV,</h5></div>
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">&nbsp;title={Real-World Blur Dataset for Learning and Benchmarking Deblurring Algorithms},</h5></div>
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">&nbsp;author={Jaesung Rim, Haeyun Lee, Jucheol Won, Sunghyun Cho},</h5></div>
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">&nbsp;booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},</h5></div>
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">&nbsp;year={2020},</h5></div>
            <div class="row justify-content-center"><h5 class="text-left mt-0 col-lg-10">}</h5></div>
        </div> -->

        <!-- ###################################################################################################################
        Contact
        ################################################################################################################### -->
        <section class="page-section" id="contact">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-8 text-center">
                        <h2 class="mt-0">Let's Get In Touch!</h2>
                        <hr class="divider my-4 align-center" />
                        <p class="text-muted mb-5">Please feel free to contact us with any feedback, questions, or comments </p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-4 ml-auto text-center mb-5 mb-lg-0">
                        <a class="d-block" href="{{site.url}}"><i class="fas fa-home fa-3x mb-3 text-muted"></i></a>
                        <a class="d-block" href="{{site.url}}">{{site.url}}</a>
                    </div>
                    <div class="col-lg-4 mr-auto text-center mb-5 mb-lg-0">
                        <a class="d-block" href="{{site.LAB}}"><i class="fas fa-home fa-3x mb-3 text-muted"></i></a>
                        <a class="d-block" href="{{site.LAB}}">{{site.LAB}}</a>
                    </div>
                    <div class="col-lg-4 mr-auto text-center mb-5 mb-lg-0">
                        <a class="d-block" href="mailto:{{site.author.email}}"><i class="fas fa-envelope fa-3x mb-3 text-muted"></i></a>
                        <!-- Make sure to change the email address in BOTH the anchor text and the link target below!-->
                        <a class="d-block" href="mailto:{{site.author.email}}">{{site.author.email}}</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- ###################################################################################################################
        Footer
        ################################################################################################################### -->
        <!-- <footer class="bg-light py-5">
            <div class="container"><div class="small text-center text-muted">Copyright © 2020 - Start Bootstrap</div></div>
        </footer> -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.bundle.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-easing/1.4.1/jquery.easing.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
        <script src="js/scripts.js"></script>
    </body>
</html>
