<template>
  <div class="page-wrapper">
    <TopBar :categories="topBarCategories" />

    <main class="main">
      <div class="intro-section bg-lighter pt-5 pb-6">
        <div class="container">
          <div class="row">
            <div class="col-lg-8">
              <div
                class="intro-slider-container slider-container-ratio slider-container-1 mb-2 mb-lg-0"
              >
                <div
                  class="intro-slider intro-slider-1 owl-carousel owl-simple owl-light owl-nav-inside"
                  data-toggle="owl"
                  data-owl-options='{
                                        "nav": false, 
                                        "responsive": {
                                            "768": {
                                                "nav": true
                                            }
                                        }
                                    }'
                >
                  <div class="intro-slide">
                    <figure class="slide-image">
                      <picture>
                        <source
                          media="(max-width: 480px)"
                          srcset="/images/slider/slide-1-480w.jpg"
                        />
                        <img src="/images/slider/slide-1.jpg" alt="Image Desc" />
                      </picture>
                    </figure>
                    <!-- End .slide-image -->

                    <div class="intro-content">
                      <h3 class="intro-subtitle">Topsale Collection</h3>
                      <!-- End .h3 intro-subtitle -->
                      <h1 class="intro-title">Living Room<br />Furniture</h1>
                      <!-- End .intro-title -->

                      <a href="category.html" class="btn btn-outline-white">
                        <span>SHOP NOW</span>
                        <i class="icon-long-arrow-right"></i>
                      </a>
                    </div>
                    <!-- End .intro-content -->
                  </div>
                  <!-- End .intro-slide -->

                  <div class="intro-slide">
                    <figure class="slide-image">
                      <picture>
                        <source
                          media="(max-width: 480px)"
                          srcset="/images/slider/slide-2-480w.jpg"
                        />
                        <img src="/images/slider/slide-2.jpg" alt="Image Desc" />
                      </picture>
                    </figure>
                    <!-- End .slide-image -->

                    <div class="intro-content">
                      <h3 class="intro-subtitle">News and Inspiration</h3>
                      <!-- End .h3 intro-subtitle -->
                      <h1 class="intro-title">New Arrivals</h1>
                      <!-- End .intro-title -->

                      <a href="category.html" class="btn btn-outline-white">
                        <span>SHOP NOW</span>
                        <i class="icon-long-arrow-right"></i>
                      </a>
                    </div>
                    <!-- End .intro-content -->
                  </div>
                  <!-- End .intro-slide -->

                  <div class="intro-slide">
                    <figure class="slide-image">
                      <picture>
                        <source
                          media="(max-width: 480px)"
                          srcset="/images/slider/slide-3-480w.jpg"
                        />
                        <img src="/images/slider/slide-3.jpg" alt="Image Desc" />
                      </picture>
                    </figure>
                    <!-- End .slide-image -->

                    <div class="intro-content">
                      <h3 class="intro-subtitle">Outdoor Furniture</h3>
                      <!-- End .h3 intro-subtitle -->
                      <h1 class="intro-title">Outdoor Dining <br />Furniture</h1>
                      <!-- End .intro-title -->

                      <a href="category.html" class="btn btn-outline-white">
                        <span>SHOP NOW</span>
                        <i class="icon-long-arrow-right"></i>
                      </a>
                    </div>
                    <!-- End .intro-content -->
                  </div>
                  <!-- End .intro-slide -->
                </div>
                <!-- End .intro-slider owl-carousel owl-simple -->

                <span class="slider-loader"></span
                ><!-- End .slider-loader -->
              </div>
              <!-- End .intro-slider-container -->
            </div>
            <!-- End .col-lg-8 -->
            <div class="col-lg-4">
              <div class="intro-banners">
                <div class="row row-sm">
                  <div class="col-md-6 col-lg-12">
                    <div class="banner banner-display">
                      <a href="#">
                        <img
                          src="/images/banners/home/intro/banner-1.jpg"
                          alt="Banner"
                        />
                      </a>

                      <div class="banner-content">
                        <h4 class="banner-subtitle text-darkwhite">
                          <a href="#">Clearence</a>
                        </h4>
                        <!-- End .banner-subtitle -->
                        <h3 class="banner-title text-white">
                          <a href="#">Chairs & Chaises <br />Up to 40% off</a>
                        </h3>
                        <!-- End .banner-title -->
                        <a href="#" class="btn btn-outline-white banner-link"
                          >Shop Now<i class="icon-long-arrow-right"></i
                        ></a>
                      </div>
                      <!-- End .banner-content -->
                    </div>
                    <!-- End .banner -->
                  </div>
                  <!-- End .col-md-6 col-lg-12 -->

                  <div class="col-md-6 col-lg-12">
                    <div class="banner banner-display mb-0">
                      <a href="#">
                        <img
                          src="/images/banners/home/intro/banner-2.jpg"
                          alt="Banner"
                        />
                      </a>

                      <div class="banner-content">
                        <h4 class="banner-subtitle text-darkwhite">
                          <a href="#">New in</a>
                        </h4>
                        <!-- End .banner-subtitle -->
                        <h3 class="banner-title text-white">
                          <a href="#">Best Lighting <br />Collection</a>
                        </h3>
                        <!-- End .banner-title -->
                        <a href="#" class="btn btn-outline-white banner-link"
                          >Discover Now<i class="icon-long-arrow-right"></i
                        ></a>
                      </div>
                      <!-- End .banner-content -->
                    </div>
                    <!-- End .banner -->
                  </div>
                  <!-- End .col-md-6 col-lg-12 -->
                </div>
                <!-- End .row row-sm -->
              </div>
              <!-- End .intro-banners -->
            </div>
            <!-- End .col-lg-4 -->
          </div>
          <!-- End .row -->

          <div class="mb-6"></div>
          <!-- End .mb-6 -->

          <div
            class="owl-carousel owl-simple"
            data-toggle="owl"
            data-owl-options='{
                            "nav": false, 
                            "dots": false,
                            "margin": 30,
                            "loop": false,
                            "responsive": {
                                "0": {
                                    "items":2
                                },
                                "420": {
                                    "items":3
                                },
                                "600": {
                                    "items":4
                                },
                                "900": {
                                    "items":5
                                },
                                "1024": {
                                    "items":6
                                }
                            }
                        }'
          >
            <a href="#" class="brand">
              <img src="/images/brands/1.png" alt="Brand Name" />
            </a>

            <a href="#" class="brand">
              <img src="/images/brands/2.png" alt="Brand Name" />
            </a>

            <a href="#" class="brand">
              <img src="/images/brands/3.png" alt="Brand Name" />
            </a>

            <a href="#" class="brand">
              <img src="/images/brands/4.png" alt="Brand Name" />
            </a>

            <a href="#" class="brand">
              <img src="/images/brands/5.png" alt="Brand Name" />
            </a>

            <a href="#" class="brand">
              <img src="/images/brands/6.png" alt="Brand Name" />
            </a>
          </div>
          <!-- End .owl-carousel -->
        </div>
        <!-- End .container -->
      </div>
      <div class="mb-6"></div>
      <div class="container">
        <TrandyProductCategories :categories="trendyProductCategories"/>
        <div class="tab-content">
          <div
            class="tab-pane p-0 fade show active"
            id="trendy-top-all-tab"
            role="tabpanel"
            aria-labelledby="trendy-top-all-link"
          >
            <ProductList :productsdata="trendyProducts" />
          </div>
          <ProductTabs v-for="tab in trendyProductCategories" :tabname="tab.name" :tabdata="tab.products" :prefix="'trendy-products'" />
        </div>
      </div>
      <div class="container categories pt-6">
        <h2 class="title-lg text-center mb-4">Shop by Categories</h2>
        <div class="row">
          <div class="col-6 col-lg-4">
            <div class="banner banner-display banner-link-anim">
              <a href="#">
                <img src="/images/banners/home/banner-1.jpg" alt="Banner" />
              </a>
              <div class="banner-content banner-content-center">
                <h3 class="banner-title text-white"><a href="#">Outdoor</a></h3>
                <a href="#" class="btn btn-outline-white banner-link"
                  >Shop Now<i class="icon-long-arrow-right"></i
                ></a>
              </div>
            </div>
          </div>
          <div class="col-6 col-lg-4 order-lg-last">
            <div class="banner banner-display banner-link-anim">
              <a href="#">
                <img src="/images/banners/home/banner-4.jpg" alt="Banner" />
              </a>

              <div class="banner-content banner-content-center">
                <h3 class="banner-title text-white"><a href="#">Lighting</a></h3>
                <!-- End .banner-title -->
                <a href="#" class="btn btn-outline-white banner-link"
                  >Shop Now<i class="icon-long-arrow-right"></i
                ></a>
              </div>
              <!-- End .banner-content -->
            </div>
            <!-- End .banner -->
          </div>
          <!-- End .col-sm-6 col-lg-3 -->
          <div class="col-sm-12 col-lg-4 banners-sm">
            <div class="row">
              <div class="banner banner-display banner-link-anim col-lg-12 col-6">
                <a href="#">
                  <img src="/images/banners/home/banner-2.jpg" alt="Banner" />
                </a>

                <div class="banner-content banner-content-center">
                  <h3 class="banner-title text-white">
                    <a href="#">Furniture and Design</a>
                  </h3>
                  <!-- End .banner-title -->
                  <a href="#" class="btn btn-outline-white banner-link"
                    >Shop Now<i class="icon-long-arrow-right"></i
                  ></a>
                </div>
                <!-- End .banner-content -->
              </div>
              <!-- End .banner -->

              <div class="banner banner-display banner-link-anim col-lg-12 col-6">
                <a href="#">
                  <img src="/images/banners/home/banner-3.jpg" alt="Banner" />
                </a>

                <div class="banner-content banner-content-center">
                  <h3 class="banner-title text-white">
                    <a href="#">Kitchen & Utensil</a>
                  </h3>
                  <!-- End .banner-title -->
                  <a href="#" class="btn btn-outline-white banner-link"
                    >Shop Now<i class="icon-long-arrow-right"></i
                  ></a>
                </div>
                <!-- End .banner-content -->
              </div>
              <!-- End .banner -->
            </div>
          </div>
          <!-- End .col-sm-6 col-lg-3 -->
        </div>
      </div>
      <div class="mb-5"></div>
      <div class="container">
        <RecentProductCategories :categories="recentProductCategories"/>
        <div class="tab-content">
          <div
            class="tab-pane p-0 fade show active"
            id="recent-top-all-tab"
            role="tabpanel"
            aria-labelledby="recent-top-all-link"
          >
            <ProductList :productsdata="recentProducts" />
          </div>
          <ProductTabs v-for="tab in recentProductCategories" :tabname="tab.name" :tabdata="tab.products" :prefix="'recent-products'" />
        </div>
        <div class="more-container text-center">
          <a href="#" class="btn btn-outline-darker btn-more"
            ><span>Load more products</span><i class="icon-long-arrow-down"></i
          ></a>
        </div>
      </div>
      <div class="container">
        <hr />
        <div class="row justify-content-center">
          <div class="col-lg-4 col-sm-6">
            <div class="icon-box icon-box-card text-center">
              <span class="icon-box-icon">
                <i class="icon-rocket"></i>
              </span>
              <div class="icon-box-content">
                <h3 class="icon-box-title">Payment & Delivery</h3>
                <!-- End .icon-box-title -->
                <p>Free shipping for orders over $50</p>
              </div>
              <!-- End .icon-box-content -->
            </div>
            <!-- End .icon-box -->
          </div>
          <!-- End .col-lg-4 col-sm-6 -->

          <div class="col-lg-4 col-sm-6">
            <div class="icon-box icon-box-card text-center">
              <span class="icon-box-icon">
                <i class="icon-rotate-left"></i>
              </span>
              <div class="icon-box-content">
                <h3 class="icon-box-title">Return & Refund</h3>
                <!-- End .icon-box-title -->
                <p>Free 100% money back guarantee</p>
              </div>
              <!-- End .icon-box-content -->
            </div>
            <!-- End .icon-box -->
          </div>
          <!-- End .col-lg-4 col-sm-6 -->

          <div class="col-lg-4 col-sm-6">
            <div class="icon-box icon-box-card text-center">
              <span class="icon-box-icon">
                <i class="icon-life-ring"></i>
              </span>
              <div class="icon-box-content">
                <h3 class="icon-box-title">Quality Support</h3>
                <!-- End .icon-box-title -->
                <p>Alway online feedback 24/7</p>
              </div>
              <!-- End .icon-box-content -->
            </div>
            <!-- End .icon-box -->
          </div>
          <!-- End .col-lg-4 col-sm-6 -->
        </div>
        <!-- End .row -->

        <div class="mb-2"></div>
        <!-- End .mb-2 -->
      </div>
    </main>
    <Footer />
  </div>
  <button id="scroll-top" title="Back to Top"><i class="icon-arrow-up"></i></button>

  <div class="mobile-menu-overlay"></div>
</template>

<script>
import TopBar from "../components/layouts/top-bar.vue";
import Footer from "../components/layouts/footer.vue";
import ProductList from "../components/products/product-list.vue";
import RecentProductCategories from '../components/categories/recent_product_categories.vue';
import TrandyProductCategories from '../components/categories/trendy_product_categories.vue';
import ProductTabs from '../components/products/product-tabs.vue'
import axios from 'axios'

export default {
  name: "App",
  components: {
    TopBar,
    Footer,
    ProductList,
    RecentProductCategories,
    TrandyProductCategories,
    ProductTabs
  },
  data() {
    return {
      topBarCategories: [],
      recentProducts: [],
      trendyProducts: [],
      recentProductCategories: [],
      trendyProductCategories: [],
    };
  },
  methods : {
    async getWelcomeData(){
      const welComeDataResponse=await axios.post(import.meta.env.VITE_APP_SERVER+'welcome/get');
      this.recentProducts=welComeDataResponse.data.recentProducts;
      this.trendyProducts=welComeDataResponse.data.trendyProducts;
      this.recentProductCategories=welComeDataResponse.data.recentProductCategories;
      this.trendyProductCategories=welComeDataResponse.data.trendyProductCategories;
      this.topBarCategories=welComeDataResponse.data.allCategories;
    }
  },
  async created() {
    await this.getWelcomeData();
  },
};
</script>
