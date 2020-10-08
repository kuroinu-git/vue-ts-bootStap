<template>
  <div id="app">
    <header class="blog-header py-3">
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

    <div class="nav-scroller py-1 mb-2">
      <nav
        class="navbar navbar-light navbar-expand-md bg-faded justify-content-center"
        id="nav"
      >
        <li class="nav-item navbar-brand">
          <router-link to="/" class="nav-link m-2 menu-item nav-active"
            >Home</router-link
          >
        </li>
        <li class="nav-item navbar-brand">
          <router-link to="/shop" class="nav-link m-2 menu-item nav-active"
            >Shop
            <i class="fa fa-angle-down"></i>
          </router-link>
        </li>
        <li class="nav-item navbar-brand">
          <router-link to="/todo" class="nav-link m-2 menu-item nav-active"
            >Blog</router-link
          >
        </li>
        <li class="nav-item navbar-brand">
          <router-link to="/about" class="nav-link m-2 menu-item nav-active"
            >Contact</router-link
          >
        </li>
      </nav>
    </div>
    
    <router-view />
  </div>

  <!-- 
 <header class="blog-header py-3">
        <div class="row flex-nowrap justify-content-between align-items-center">
          <div class="col-4 pt-1">
            <a class="text-muted" href="#">Subscribe</a>
          </div>
          <div class="col-4 text-center">
            <a class="blog-header-logo text-dark" href="#">Large</a>
          </div>
          <div class="col-4 d-flex justify-content-end align-items-center">
            <a class="text-muted" href="#">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mx-3"><circle cx="10.5" cy="10.5" r="7.5"></circle><line x1="21" y1="21" x2="15.8" y2="15.8"></line></svg>
            </a>
            <a class="btn btn-sm btn-outline-secondary" href="#">Sign up</a>
          </div>
        </div>
      </header> -->
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav {
  padding: 0px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  font-size: 20px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.fa-shopping-bag:before {
  content: '\f290';
  padding: 40%;
}
.header-nav {
  padding: 10px 40px;
  padding-bottom: 30px;
}
.text-headers {
  margin-inline-start: 10px;
  font-size: 23px;
  font-weight: 300;
  font-family: serif;
  line-height: 1.5;
  color: black;
}
.text-center {
  padding-inline-start: 200px;
}
</style>
