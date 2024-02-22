<template>
  <div>
    <div class="header-bg">
      <!-- Navigation Bar-->
      <header id="topnav">
        <div class="topbar-main">
          <div class="container-fluid">

            <!-- Logo-->
            <div>
              <router-link to="/" class="logo">
                <span class="logo-light">
                        <i class="mdi mdi-camera-control"></i> TensorFlow.js
                </span>
              </router-link>
            </div>
            <!-- End Logo-->

            <div class="clearfix"></div>

          </div>
          <!-- end container -->
        </div>
        <!-- end topbar-main -->

        <!-- MENU Start -->
        <div class="navbar-custom">
          <div class="container-fluid">

            <div id="navigation">

              <!-- Navigation Menu-->
              <ul class="navigation-menu">

                <!-- Início -->
                <li class="has-submenu">
                  <router-link to="/"><i class="icon-accelerator"></i> Início</router-link>
                </li>

                <!-- Marcas -->
                <li class="has-submenu">
                  <a href="#">
                    <i class="icon-life-buoy"></i>
                    Modelos <i class="mdi mdi-chevron-down mdi-drop"></i>
                  </a>
                  <ul class="submenu">
                    <li>
                      <router-link to="/model1">Modelo 1</router-link>
                    </li>

                    <li>
                      <router-link to="/model2">Modelo 2 </router-link>
                    </li>
                  </ul>
                </li>

              </ul>
              <!-- End navigation menu -->
            </div>
            <!-- end #navigation -->
          </div>
          <!-- end container -->
        </div>
        <!-- end navbar-custom -->
      </header>
      <!-- End Navigation Bar-->
    </div>
  </div>
</template>

<script>

export default {
  name: "NavBar",
  computed: {},
  methods: {},
  created() {}
}
</script>

<style scoped>
#topnav{z-index: 50 !important;}
</style>