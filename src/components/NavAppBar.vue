<template>
  <v-layout>
    <v-app-bar
      scroll-behavior="fade-image"
      scroll-threshold="1000"
      image="https://www.mdpi.com/1996-1073/15/14/5297"
    >
    <v-v-navigation drawer >
      <div>
          <v-img
            class="logo"
            src="https://logos-world.net/wp-content/uploads/2020/10/Free-Logo-700x394.png"
          ></v-img>
          <v-btn class="d-inline pa-2 texttyp">หน้าแรก</v-btn>
          <v-btn class="d-inline pa-2 texttyp">บริการของเรา</v-btn>
          <v-btn class="d-inline pa-2 texttyp">SUBPOWER</v-btn>
          <v-btn class="d-inline pa-2 texttyp">บทความ</v-btn>
          <v-btn class="d-inline pa-2 texttyp">ผลงานที่ผ่านมา</v-btn>
          <v-btn class="d-inline pa-2 texttyp">เกี่ยวกับเรา</v-btn>
          <v-btn class="d-inline pa-2 texttyp">สนใจบริการของเรา</v-btn>
        </div>
      </v-v-navigation>
      <template v-slot:append>
        <v-btn icon="mdi-magnify"></v-btn>
        <v-btn icon="mdi-basket"></v-btn>
      </template>
    </v-app-bar>
  </v-layout>
</template>

<script>
export default {
  name: "NavAppBar",
};
</script>

<style>
.texttyp {
  font-family: "Mitr", sans-serif;
  font-weight: bold;
  font-size: 1rem;
}
.logo {
  max-width: 70px;
  height: auto;
}
</style>
