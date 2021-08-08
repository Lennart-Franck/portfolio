<template>
  <v-app dark>
    <v-app-bar :clipped-left="clipped" color="secondary" app flat>
      <v-app-bar-nav-icon
        class="d-flex d-md-none white--text"
        @click.stop="drawer = !drawer"
      />
      <v-toolbar-title class="primary--text ml-auto "
        ><v-img max-width="44" src="/dev.svg"></v-img>
      </v-toolbar-title>
      <div class="d-sm-flex mr-auto ml-auto d-none">
        <div
          v-for="link in links"
          :key="link.name"
          class="ma-3 text-subtitle-1 font-weight-medium white--text"
        >
          <v-btn :href="link.to" tile plain color="primary">
            {{ link.name }}
          </v-btn>
        </div>
      </div>
    </v-app-bar>
    <v-main>
      <div class="secondary">
        <nuxt />
      </div>
    </v-main>
    <v-navigation-drawer v-model="drawer" dark temporary fixed>
      <v-list>
        <v-list-item>
          <v-list-item-action>
            <v-icon light>
              mdi-repeat
            </v-icon>
          </v-list-item-action>
          <v-list-item-title>Switch drawer (click me)</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      links: [
        {
          name: "Home",
          to: "#home"
        },
        {
          name: "Über mich",
          to: "#about"
        },
        {
          name: "Kenntnisse",
          to: "#services"
        },
        {
          name: "Erfahrung",
          to: "#portfolio"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Lennart Franck"
    };
  }
};
</script>
<style></style>
