<template>
  <v-app id="app"> </v-app>
</template>

<script>
export default {
  data() {
    return {
      menu: [
        { icon: "home", title: "Link A" },
        { icon: "info", title: "Link B" },
        { icon: "warning", title: "Link C" },
      ],
    };
  },

  methods: {
    menuItems() {
      return this.menu;
    },
  },
};
</script>
