<template>
  <div id="app">
    <nav class="navbar navbar-light navbar-expand-md bg-faded justify-content-center">
      <div class="d-flex w-50 mr-auto">
        <span class="w-50 d-lg-none d-block"></span>
        <a class="navbar-brand">
          <img
            src="https://placekitten.com/g/30/30"
            width="30"
            height="30"
            class="d-inline-block align-top"
          />
          Clay Shop
        </a>
      </div>

      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#collapsingNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="navbar-collapse collapse w-50">
        <ul class="navbar-nav w-50 justify-content-center">
          <li class="nav-item">
            <a style="font-size:30px;color:black" class="fa fa-instagram navbar-brand" href="/" />
          </li>
        </ul>

        <ul class="navbar-nav justify-content-center">
          <li class="nav-item">
            <a style="font-size:30px;color:black" class="fa fa-twitter navbar-brand" href="/" />
          </li>
        </ul>

        <ul class="navbar-nav w-50 justify-content-center">
          <li class="nav-item">
            <a
              style="font-size:30px;color:black"
              class="fa fa-facebook-square navbar-brand"
              href="/"
            />
          </li>
        </ul>
      </div>

      <div class="navbar-collapse collapse w-50">
        <ul class="nav navbar-nav ml-auto justify-content-end">
          <li class="nav-item">
            <a style="font-size:30px;color:black" class="fa fa-search navbar-brand" href="/" />
          </li>

          <li class="nav-item">
            <a style="font-size:30px;color:black" class="fa fa-shopping-bag navbar-brand" href="/" />
          </li>
        </ul>
      </div>
    </nav>

    <nav class="navbar navbar-light navbar-expand-md bg-faded justify-content-center" id="nav">
      <li class="nav-item navbar-brand">
        <router-link to="/" class="nav-link m-2 menu-item nav-active">Home</router-link>
      </li>
      <li class="nav-item navbar-brand">
        <router-link
          to="/shop"
          class="nav-link m-2 menu-item nav-active dropdown-toggle"
          data-toggle="dropdown"
        >Shop</router-link>
      </li>
      <li class="nav-item navbar-brand">
        <router-link to="/todo" class="nav-link m-2 menu-item nav-active">Blog</router-link>
      </li>
      <li class="nav-item navbar-brand">
        <router-link to="/about" class="nav-link m-2 menu-item nav-active">Contact</router-link>
      </li>
    </nav>

    <router-view />
  </div>
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
</style>
