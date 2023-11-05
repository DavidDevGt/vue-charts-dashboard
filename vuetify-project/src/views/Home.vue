<template>
  <v-app :style="{background: $vuetify.theme.themes.light.colors.primary}">
    <Sidebar />
    <v-main>
      <v-container class="px-6 mt-n2" fluid>
        <v-row>
          <v-col cols="12" sm="4">
            <v-card colors="#B49239" theme="dark" class="rounded-xl" height="150">
              <div class="d-flex flex-no-wrap justify-space-between">
                <div>
                  <v-card-title class="text-h5 mt-10">
                    Boieng 787
                  </v-card-title>
                  <v-card-subtitle>$548</v-card-subtitle>
                </div>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
import Sidebar from "@/components/SideBare.vue";
</script>
<script>
export default {
  data:() => ({
    folders: [
      {
        subtitle: "David Vargas",
        title: "davidwebgt@gmail.com",
        img: "1.png",
      },
    ],
  }),
  components: {
    Sidebar,
  }
}
</script>
