<template>
  <div id="app">
    <header class="blog-header">
      <nav
        class="navbar navbar-light navbar-expand-md bg-faded justify-content-center header-nav"
      >
        <div class="col-4 pt-1">
          <a class="navbar-brand">
            <img
              src="https://placekitten.com/g/30/30"
              width="30"
              height="30"
              class="d-inline-block align-top"
            />
            <a class="text-headers"> Clay Shop</a>
          </a>
        </div>

        <div class="col-4 text-center">
          <div class="navbar-collapse collapse w-50">
            <ul class="navbar-nav justify-content-center w-50">
              <li class="nav-item">
                <a
                  style="font-size: 30px; color: black"
                  class="fa fa-instagram navbar-brand"
                  href="/"
                />
              </li>
            </ul>

            <ul class="navbar-nav justify-content-center w-50">
              <li class="nav-item">
                <a
                  style="font-size: 30px; color: black"
                  class="fa fa-twitter navbar-brand"
                  href="/"
                />
              </li>
            </ul>

            <ul class="navbar-nav w-50 justify-content-center w-50">
              <li class="nav-item">
                <a
                  style="font-size: 30px; color: black"
                  class="fa fa-facebook-square navbar-brand"
                  href="/"
                />
              </li>
            </ul>
          </div>
        </div>

        <div class="col-4 d-flex justify-content-end align-items-center">
          <div class="navbar-collapse collapse w-50">
            <ul class="nav navbar-nav ml-auto justify-content-end">
              <li class="nav-item">
                <a
                  style="font-size: 30px; color: black"
                  class="fa fa-search navbar-brand"
                  href="/"
                />
              </li>

              <li class="nav-item">
                <a
                  style="font-size: 30px; color: black"
                  class="fa fa-shopping-bag navbar-brand"
                  href="/"
                />
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>

    <div class="nav-scroller">
      <nav
        class="navbar navbar-light navbar-expand-md bg-faded justify-content-center"
        id="nav"
      >
        <li class="nav-item navbar-brand">
          <router-link
            to="/"
            class="nav-link m-2 menu-item nav-active head-serif"
            >Home</router-link
          >
        </li>
        <li class="nav-item navbar-brand">
          <router-link
            to="/shop"
            class="nav-link m-2 menu-item nav-active head-serif"
            >Shop
            <i class="fa fa-angle-down"></i>
          </router-link>
        </li>
        <li class="nav-item navbar-brand">
          <router-link
            to="/todo"
            class="nav-link m-2 menu-item nav-active head-serif"
            >Blog</router-link
          >
        </li>
        <li class="nav-item navbar-brand">
          <router-link
            to="/about"
            class="nav-link m-2 menu-item nav-active head-serif"
            >Contact</router-link
          >
        </li>
      </nav>
    </div>

    <router-view />
  </div>

</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import '@/assets/styless/app.scss';

@Component({})
export default class App extends Vue {}
</script>
