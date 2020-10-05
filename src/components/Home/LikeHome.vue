<template>
  <div>
    <div class="mh-100" style="height: 60px"></div>
    <div class="mh-100" style="height: 60px"></div>
    <div class="container-carousel">
      <div class="row">
        <div class="col-md-10 mx-auto">
          <h3>MMEMEMEMEMME LIKE</h3>

          <div
            id="myCarousel-card"
            class="carousel slide"
            data-ride="carousel"
            data-interval="0"
          >
            <!-- Carousel indicators -->
            <ol class="carousel-indicators">
              <li
                data-target="#myCarousel-card"
                data-slide-to="0"
                class="active"
              ></li>
              <li data-target="#myCarousel-card" data-slide-to="1"></li>
            </ol>
            <!-- Wrapper for carousel items -->
            <div class="carousel-inner">
              <div class="carousel-item-card active">
                <div class="row">
                  <div class="col-sm-4">
                    <div class="thumb-wrapper-card">
                      <div class="img-box">
                        <img
                          src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
                          class="img-fluid"
                        />
                      </div>
                      <div class="thumb-content-card">
                        <h4>London</h4>
                        <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Nam eu sem tempor, varius
                          quam.asdasasasdasadsadasddas asdsadasdasdsadasdasas
                          asdasdasasdasdasdsadsdasd
                        </p>
                        <div class="cart-section">
                          <div class="row">
                            <div class="col-md-6 col-sm-12 col-xs-6 review"> 
                              <br />
                              <h5 class="detail-price">$ 187.87</h5>
                            </div>
                            <div class="col-md-6 col-sm-12 col-xs-6">
                              <a href="#" class="btn btn-outline-danger"
                                >More</a
                              >
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="col-sm-4">
                    <div class="thumb-wrapper-card">
                      <div class="img-box">
                        <img
                          src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
                          class="img-fluid"
                        />
                      </div>
                      <div class="thumb-content-card">
                        <h4>London</h4>
                        <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Nam eu sem tempor, varius
                          quam.asdasasasdasadsadasddas asdsadasdasdsadasdasas
                          asdasdasasdasdasdsadsdasd
                        </p>
                        <div class="cart-section">
                          <div class="row">
                            <div class="col-md-6 col-sm-12 col-xs-6 review">
                              <br />
                              <h5 class="detail-price">$187.87</h5>
                            </div>
                            <div class="col-md-6 col-sm-12 col-xs-6">
                              <a href="#" class="btn btn-outline-danger"
                                >More</a
                              >
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="col-sm-4">
                   <div class="thumb-wrapper-card">
                      <div class="img-box">
                        <img
                          src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
                          class="img-fluid"
                        />
                      </div>
                      <div class="thumb-content-card">
                        <h4>London</h4>
                        <p>
                          Lorem ipsum dolor sit amet, consectetur adipiscing
                          elit. Nam eu sem tempor, varius
                          quam.asdasasasdasadsadasddas asdsadasdasdsadasdasas
                          asdasdasasdasdasdsadsdasd
                        </p>
                        <div class="cart-section">
                          <div class="row">
                            <div class="col-md-6 col-sm-12 col-xs-6 review">
                              <br />
                              <h5 class="detail-price">$187.87</h5>
                            </div>
                            <div class="col-md-6 col-sm-12 col-xs-6">
                              <a href="#" class="btn btn-outline-danger"
                                >More</a
                              >
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- Carousel controls -->

            <a
              class="carousel-control-prev"
              href="#myCarousel-card"
              data-slide="prev"
            >
              <i class="fa fa-angle-left"></i>
            </a>
            <a
              class="carousel-control-next"
              href="#myCarousel-card"
              data-slide="next"
            >
              <i class="fa fa-angle-right"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/likehome.scss';

@Component({})
export default class LikeHome extends Vue {
  @Prop() private msg!: string;
}
</script>