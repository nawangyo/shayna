<template>
    <section class="hero-section">
        <carousel class="hero-items" :autoplay="2000" :wrap-around="true">
            <slide class="carousel__item" style="background-image: url('/img/hero-1.jpg'); height: 500px;">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </slide>
            <slide class="carousel__item" style="background-image: url('/img/hero-2.jpg'); height: 500px;">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </slide>
            <slide class="carousel__item" style="background-image: url('/img/hero-3.jpg'); height: 500px;">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </slide>

            <template #addons>
                <pagination />
            </template>
        </carousel>
    </section>
</template>

<script>

import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination } from 'vue3-carousel';

export default {
    name: 'SliderSection',
    components: 
    {
        Carousel,
        Slide,
        Pagination,
    }
}
</script>