<template>
  <v-app>
    <v-main>
      <v-container>
        <v-row>
          <v-col xs="6" offset-xs="3">
            <Pomodoro />
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Pomodoro from "./components/Pomodoro";

export default {
  name: "App",

  components: {
    Pomodoro,
  },

  data: () => ({
    //
  }),
};
</script>
