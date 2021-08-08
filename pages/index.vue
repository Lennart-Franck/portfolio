<template>
  <div class="parent">
    <section id="home">
      <v-container  fill-height> 
      <v-row align="center" justify="center">
        <v-col cols="12" class="text-center" sm="6">
          <div class="white--text text-h4 text-sm-h2 font-weight-bold">
            Hey, ich bin Lennart
          </div>
          <div
            class="grey--text text--lighten-3 mt-sm-6 mt-2 text-subtitle-1 text-sm-h6 font-weight-normal"
          >
            Softwareentwickler und Technikenthusiast
          </div>
        </v-col>
        <v-col cols="8" sm="4">
          <v-img class="mx-auto" src="/Lennart_Foto.png" max-width="300" />
        </v-col>
      </v-row>
    </v-container>
    </section>
    <section class="accent">
      <v-container id="about"  fill-height>
        <v-row align="center" justify="center">
          <v-col cols="12" sm="6">
              <div class="mt-16">
                <div class="text-center font-weight-bold text-sm-h3 text-h5 white--text">
                  Über mich
                  <div class="border mt-2"></div>
                </div>
              </div>
            </v-img>
          </v-col>
          <v-col>
            <div class="grey--text text-body-1">
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
              <p>
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nu pariatur excepteur sint occaecat.
              </p>
                
                
            </div>
            <div class="text-center">
              <v-btn
                  color="primary"
                  outlined
                  class="primary--text"
                  height="60"
                  width="150"
                  >Download CV</v-btn>
            </div>
            
          </v-col>
        </v-row>
    </v-container>
    </section>
    <section id="services">
      <v-container fill-height>
      <v-row justify="center" align="center">
        <div class="text-center">
          <p class="font-weight-bold text-h5 text-sm-h3 white--text">
            Kenntnisse
          </p>
          <div class="border"></div>
          <p class="grey--text text--lighten-1 text-body-2 text-sm-body-1  mt-sm-10 mt-2 w-100">
            Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
            officia deserunt mollit anim id est laborum. Sed ut perspiciatis
            unde omnis iste natur
          </p>
        </div>

        <v-row class="pa-3" >
          <v-col cols="6" sm="6">
            <v-card color="rounded-lg">
              <v-img
                max-height="300"
                gradient="45deg, rgba(36,226,254,0.9)0%,rgba(36,176,254,0.92)45%, rgba(35,126,253, 0.95)100%"
              >
                <div class="d-flex flex-column pa-sm-10">
 
                  <v-card-title class="white--text text-h6 text-sm-h4 font-weight-bold">
                    C#
                  </v-card-title>
                  <v-card-text class="white--text text-sm-body-1 text-body-2">
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat
                  </v-card-text>
                </div>
              </v-img>
            </v-card>
          </v-col>
          <v-col cols="6" sm="6">
            <v-card color="rounded-lg">
              <v-img
                max-height="300"
                gradient="45deg, rgb(255,211,36,0.9)0%,rgba(254,187,36,0.92)45%, rgba(253,163,35,0.95)100%"
              >
                <div class="d-flex flex-column pa-sm-10">

                  <v-card-title class="white--text text-h6 text-sm-h4 font-weight-bold">
                    Python
                  </v-card-title>
                  <v-card-text class="white--text text-sm-body-1 text-body-2">
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat
                  </v-card-text>
                </div>
              </v-img>
            </v-card>
          </v-col>
          <v-col cols="6" sm="6">
            <v-card color="rounded-lg">
              <v-img
                max-height="300"
                gradient="45deg, rgba(248,47,160,0.9)0%,rgba(214,54,208,0.92)54%,rgba(180,61,255,0.95)100%"
              >
                <div class="d-flex flex-column pa-sm-10">
                  <v-card-title class="white--text text-h6 text-sm-h4 font-weight-bold">
                    JavaScript
                  </v-card-title>
                  <v-card-text class="white--text text-sm-body-1 text-body-2">
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat
                  </v-card-text>
                </div>
              </v-img>
            </v-card>
          </v-col>
          <v-col cols="6" sm="6">
            <v-card color="rounded-lg">
              <v-img
                max-height="300"
                gradient="45deg, rgba(0,188,128,0.9)0%,rgba(2,204,71,0.92)54%,rgba(3,220,13,0.95)100%"
              >
                <div class="d-flex flex-column pa-sm-10">
                  <v-card-title class="white--text text-h6 text-sm-h4 font-weight-bold">
                    Dart
                  </v-card-title>
                  <v-card-text class="white--text text-sm-body-1 text-body-2">
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat
                  </v-card-text>
                </div>
              </v-img>
            </v-card>
          </v-col>
        </v-row>
      </v-row>
    </v-container>
    </section>
    <section class="accent" id="portfolio">
      <v-container fill-height>
        <v-row justify="center" align="center">
          <div class="text-center">
            <p class="font-weight-bold text-sm-h3 text-h5 white--text">
              Erfahrung
            </p>
            <div class="border"></div>
            <p class="grey--text text--lighten-1 text-body-2 text-sm-body-1 mt-sm-10 mt-2 w-100">
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum. Sed ut perspiciatis
              unde omnis iste natur
            </p>
          </div>

          <v-row class="pa-2">
            <v-col cols="12" md="4">
              <v-hover v-slot="{ hover }">
                <v-card
                  :color="hover ? 'info' : 'secondary'"
                  class="experience"
                  tile
                >
                  <div class="d-flex flex-column pa-sm-10 pa-2 grey--text">
                    <p class="text-body-2">
                      JUNE 2012 - 2016
                    </p>
                    <p class="white--text text-sm-h5 text-subtitle-1 font-weight-bold my-n1">
                      Product Designer
                    </p>
                    <p class="text-subtitle-2 primary--text text-sm-h6">
                      Adobe Inc.
                    </p>
                    <p class="text-body-2 text-sm-body-1">
                      Lorem ipsum dolor sit amet, coectetur adipisicing elit,
                      sed do eiusmod temp incididunt ut labore.
                    </p>
                  </div>
                </v-card>
              </v-hover>
            </v-col>
            <v-col cols="12" md="4">
              <v-hover v-slot="{ hover }">
                <v-card
                  :color="hover ? 'info' : 'secondary'"
                  class="experience"
                  tile
                >
                  <div class="d-flex flex-column pa-sm-10 pa-2 grey--text">
                    <p class="text-body-2">
                      JUNE 2012 - 2016
                    </p>
                    <p class="white--text text-sm-h5 text-subtitle-1 font-weight-bold my-n1">
                      Product Designer
                    </p>
                    <p class="text-subtitle-2 primary--text text-sm-h6">
                      Adobe Inc.
                    </p>
                    <p class="text-body-2 text-sm-body-1">
                      Lorem ipsum dolor sit amet, coectetur adipisicing elit,
                      sed do eiusmod temp incididunt ut labore.
                    </p>
                  </div>
                </v-card>
              </v-hover>
            </v-col>
            <v-col cols="12" md="4">
              <v-hover v-slot="{ hover }">
                <v-card
                  :color="hover ? 'info' : 'secondary'"
                  class="experience"
                  tile
                >
                  <div class="d-flex flex-column pa-sm-10 pa-2 grey--text">
                    <p class="text-body-2">
                      JUNE 2012 - 2016
                    </p>
                    <p class="white--text text-sm-h5 text-subtitle-1 font-weight-bold my-n1">
                      Product Designer
                    </p>
                    <p class="text-subtitle-2 primary--text text-sm-h6">
                      Adobe Inc.
                    </p>
                    <p class="text-body-2 text-sm-body-1">
                      Lorem ipsum dolor sit amet, coectetur adipisicing elit,
                      sed do eiusmod temp incididunt ut labore.
                    </p>
                  </div>
                </v-card>
              </v-hover>
            </v-col>
          </v-row>
        </v-row>
    </v-container>

    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
html,
body {
  height: 100vh;
  overflow: hidden;
  scroll-behavior: smooth;
}

.parent {
  overflow: scroll;
  height: 100vh;
  scroll-snap-type: y;
  scroll-snap-points-y: repeat(100vh);
  scroll-snap-type: y mandatory;
}

section {
  height: 100vh;
  scroll-snap-align: start;
  position: relative;
}

.border {
  content: "";
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  height: 4px;
  background-color: #feb633;
  transition: all 0.3s;
}

.blue-gradient {
  background-image: -webkit-linear-gradient(
    -48deg,
    rgb(36, 226, 254) 0%,
    rgb(36, 176, 254) 54%,
    rgb(35, 126, 253) 100%
  );
}

.experience {
  border-style: solid;
  border-width: 1px 1px 1px 1px;
  border-color: #5a5a5a !important;
}
</style>
