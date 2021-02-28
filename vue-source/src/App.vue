<template>
  <div class="maindiv">
    <div class="cover-container d-flex  p-3 flex-column ">
      <header class="mb-auto w-100 mx-auto">
        <div>
          <h3 class="float-md-start mb-0">KYUHEN</h3>
          <nav class="nav nav-masthead justify-content-center float-md-end">
            <router-link class="nav-link" tag="a" to="/">Home</router-link>
            <router-link class="nav-link" tag="a" to="details"
              >Details</router-link
            >
            <router-link class="nav-link" tag="a" to="resources"
              >Resources</router-link
            >
            <a class="nav-link" href="#">Submitted Projects</a>
          </nav>
        </div>
      </header>

      <div class="py-5 mx-auto w-100 text-center" style="max-width: 40vw;">
        <div
          style="font-weight: 1000; font-size: 2rem; color:#fff; text-shadow: 2px 0 #fff; letter-spacing:2px; font-weight:bold;"
        >
          KYUHEN
        </div>
        <p class="lead" style="color:darkgray">
          Who can brew the best software?
        </p>
        <div class="container no-gutters">
          <div class="row">
            <div class="col-md-2"></div>
            <div class="col-md-4 padding-0 mt-4">
              <a href="# " class="btn btn-green btn-lg btn-secondary fw-bold "
                >Donate ❤️</a
              >
            </div>
            <div class="col-md-4 padding-0  mt-4">
              <a href="# " class="btn btn-pink btn-lg btn-secondary fw-bold "
                >Submit</a
              >
            </div>
          </div>
          <div class="row mt-4 ">
            <div class="col-md-12 center ">
              <a href="# " class="btn btn-blue btn-lg btn-secondary fw-bold "
                >Submitted Projects</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="content" id="app">
        <RouterView :key="$route.fullPath" />
      </div>
    </div>

    <footer class="mt-auto text-white-50 ">
      <p>
        Website created with ❤️ by
        <a href="https://twitter.com/chickenbonef " style="color:#fff; "
          >@chickenbone</a
        >
        &
        <a href="https://twitter.com/DaveWijk " style="color:#fff; "
          >@DaveWijk</a
        >
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style></style>
