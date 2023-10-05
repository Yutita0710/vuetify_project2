<template>
  <v-row>
    <v-col>
      <v-parallax
        src="https://scx1.b-cdn.net/csz/news/800a/2019/solarcell.jpg"
      ></v-parallax>
    </v-col>
    <v-col>
      <!-- <v-card transparent> -->
        <v-card-title class="text-h4 text-md-h5">
          Maximizing Return with NextE Solar Rooftop
        </v-card-title>
        <v-card-text class="content">
          <ul>
            <li>
              ออกแบบระบบโซล่าเซลล์ด้วยโปรแกรมคอมพิวเตอร์เพื่อให้ได้ประสิทธิภาพสูงสุด
            </li>
            <li>ดำเนินการขออนุญาตทางราชการอย่างถูกต้อง</li>
            <li>
              อุปกรณ์ได้มาตรฐาน คุณภาพสูง ตามมาตรฐานของการไฟฟ้า และ
              ได้รับมาตราฐาน ISO9001:2015 ด้านการออกแบบ และ
              ติดตั้งระบบโซล่าเซลล์
            </li>
            <li>
              บริการติดตั้งครบวงจร เหมาะสำหรับบ้าน ธุรกิจ และ โรงงาน
              คุ้มค่าการลงทุน ลดค่าใช้จ่ายในระยะยาว
            </li>
          </ul>
        </v-card-text>
      <!-- </v-card> -->
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Content1",
};
</script>

<style scoped>
* {
  margin: 0;
  margin-top: 0.5rem;
  padding-left: 3rem;
  padding-right: 3rem;
}

.content {
  width: 600px;
  height: 220px;
}

li{
  font-size: 1rem;
}
</style>
