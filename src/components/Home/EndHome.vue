<template>
  <!-- Footer -->
  <!-- Footer -->
  <footer class="page-footer font-small indigo">
    <!-- Footer Links -->
    <!-- Grid row-->
    <div class="row text-center d-flex justify-content-center pt-5 mb-3">
      <!-- Grid column -->
      <div class="col-md-2 mb-3 col-footer">
        <h5 class="text-uppercase font-weight-bold">
          <S>Home</S>
        </h5>
      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-2 mb-3 col-footer">
        <h5 class="text-uppercase font-weight-bold">
          <a>Shop</a>
        </h5>
      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-2 mb-3 col-footer">
        <h5 class="text-uppercase font-weight-bold">
          <a>Blog</a>
        </h5>
      </div>
      <!-- Grid column -->

      <!-- Grid column -->
      <div class="col-md-2 mb-3 col-footer">
        <h5 class="text-uppercase font-weight-bold">
          <a>Contact</a>
        </h5>
      </div>
      <!-- Grid column -->
    </div>
    <!-- Grid row-->
    <hr />
    <div class="container bottom_border">
      <div class="row">
        <div class="col-md-3 col-lg-3 col-xl-3 mx-auto mt-3">
          <h5 class="headin5_amrc col_white_amrc pt2">
            <i class="fa fa-facebook"></i> Clay Shop
          </h5>
          <!--headin5_amrc-->
          <p class="mb3">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum.
          </p>
        </div>

        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
          <h5 class="headin5_amrc col_white_amrc pt2">Hot links</h5>
          <!--headin5_amrc-->
          <ul class="footer_ul_amrc">
            <li><a>Home</a></li>
            <li><a>Shop</a></li>
            <li><a>Blog</a></li>
            <li><a>Contact</a></li>
          </ul>
          <!--footer_ul_amrc ends here-->
        </div>

        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mt-3">
          <h5 class="headin5_amrc col_white_amrc pt2">More info</h5>
          <!--headin5_amrc-->
          <ul class="footer_ul_amrc">
            <li><a>How it works</a></li>
            <li>
              <a>About us</a>
            </li>
            <li><a>Decline rules</a></li>
            <li><a>Terms & Coditions</a></li>
          </ul>
          <!--footer_ul_amrc ends here-->
        </div>

        <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mt-3">
          <h5 class="headin5_amrc col_white_amrc pt2">Customer care</h5>
          <!--headin5_amrc ends here-->

          <ul class="footer_ul_amrc">
            <li><a>FAQ</a></li>
            <li>
              <a>Terms of use</a>
            </li>
            <li><a>Privacy Policy</a></li>
            <li><a>Discount system</a></li>
          </ul>
          <!--footer_ul2_amrc ends here-->
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="container-s border-ending">
        <div class="row">
          <div class="col-xs-12 col-sm-6 col-md-6 col-lg-6">
            <div class="copyright">© 2015, Webenlance, All rights reserved</div>
          </div>

          <div class="col-md-7">
            <div class="design">
              <a href="#" class="social"
                ><i class="fa fa-facebook fa-pad" aria-hidden="true"></i
              ></a>
              <a href="#" class="social"
                ><i class="fa fa-twitter fa-pad" aria-hidden="true"></i
              ></a>
              <a href="#" class="social"
                ><i class="fa fa-instagram fa-pad" aria-hidden="true"></i
              ></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script  lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/endhome.scss';
@Component({})
export default class EndHome extends Vue {
  @Prop() private msg!: string;
}
</script>