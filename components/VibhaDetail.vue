<template>
  <div class="Vibha-detail-page">
    <div class="Vibha-detail-left">
      <div class="Vibha-detail-top">
        <p class="Vibha-detail-top-header">In 2020</p>
        <br />
        <img class="Vibha-detail-top-img" src="/Vibhalogo.jpg" />
      </div>
      <div class="vertical-line"></div>
      <div class="Vibha-detail-bottom">
        <p>
          In 2020, the company has expanded the business to capture the
          potential for housing development in the Vibhavadi
          Rangsit-Phaholyothin area, which is a high growth district. It is
          surrounded by various amenities including the Green and Red Skytrain
          connects traveling to the inner and outer Bangkok. The area also
          provides easy access to department stores, universities, hospitals,
          and parks that are scattered around <span class="inline-block">the area.</span>
        </p>
        <br />
        <p>
          Hence, in 2020, the company initiated the Vibha Residence project, the
          modern luxury single houses at the location of Vibhavadi Road Soi 60
          or Phaholyothin Soi 49/1, focusing on customers who want a low-rise
          house with reasonable price and quality. The construction of the first
          phase is expected to begin in <span class="inline-block">March 2021.</span>
        </p>
        <br />
        <p class="Vibha-detail-description-swapDesktop">
          ในปี 2563 เนื่องจากทางบริษัทฯ
          เล็งเห็นศักยภาพการพัฒนาที่อยู่อาศัยในย่านวิภาวดีรังสิต – พหลโยธิน
          ซึ่งเป็นย่านที่รายล้อมด้วยสิ่งอำนวยความสะดวกต่างๆ
          ทั้งรถไฟฟ้าสายสีเขียว และ <span class="inline-block">สายสีแดง</span>
        </p>
      </div>
    </div>
    <div class="Vibha-detail-right">
      <img
        src="/Vibhadetail-img.jpg"
        class="Vibha-detail-img Vibha-detail-img-desktop"
        alt=""
      />
      <img
        src="/Vibhadetail-img-mobile.jpg"
        class="Vibha-detail-img Vibha-detail-img-mobile"
        alt=""
      />
      <div class="Vibha-detail-description-right">
        <div class="Vibha-detail-description-swapMobile">
          <p class="Vibha-detail-swapMobile">
            ในปี 2563 เนื่องจากทางบริษัทฯ
            เล็งเห็นศักยภาพการพัฒนาที่อยู่อาศัยในย่านวิภาวดีรังสิต – พหลโยธิน
            ซึ่งเป็นย่านที่รายล้อมด้วยสิ่งอำนวยความสะดวกต่างๆ
            ทั้งรถไฟฟ้าสายสีเขียว และ <span class="inline-block">สายสีแดง</span>
          </p>
          <p class="Vibha-detail-swapMobile">
            เชื่อมต่อทั้งกรุงเทพชั้นในและชั้นนอก รวมถึงสถานที่สำคัญ
            ห้างสรรพสินค้าและสวนสาธารณะที่กระจายอยู่รอบพื้นที่ จึงริเริ่มโครงการ
            วิภา เรสซิเดนท์ บ้านเดี่ยวระดับ LUXURY
            มุ่งเน้นลูกค้าที่ต้องการที่อยู่อาศัยแนวราบที่เหมาะสมทั้งราคาและคุณภาพ
            โดยคาดว่าจะเริ่มก่อสร้างเฟสแรก <span class="inline-block">ในปี 2564</span>
          </p>
        </div>

        <p class="Vibha-detail-description-swapDesktop">
          เชื่อมต่อทั้งกรุงเทพชั้นในและชั้นนอก รวมถึงสถานที่สำคัญ
          ห้างสรรพสินค้าและสวนสาธารณะที่กระจายอยู่รอบพื้นที่ จึงริเริ่มโครงการ
          วิภา เรสซิเดนท์ บ้านเดี่ยวระดับ LUXURY
          มุ่งเน้นลูกค้าที่ต้องการที่อยู่อาศัยแนวราบที่เหมาะสมทั้งราคาและคุณภาพ
          โดยคาดว่าจะเริ่มก่อสร้างเฟสแรก <span class="inline-block">ในปี 2564</span>
        </p>
      </div>
      <div class="Vibha-detail-tree-center">
        <img src="/tree.jpg" class="Vibha-detail-tree" alt="" />
      </div>
      <br />
    </div>
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "vue-property-decorator";

@Component
export default class VibhaDetail extends Vue {}
</script>

<style lang="scss" scoped>
@font-face {
  font-family: "DB-Ozone-X";
  src: url(/fonts/DB-Ozone-X.ttf);
}
@font-face {
  font-family: "Kiona-Regular";
  src: url(/fonts/Kiona-Regular.ttf);
}
@font-face {
  font-family: "SukhumvitSet";
  src: url(/fonts/SukhumvitSet.ttf);
}
@font-face {
  font-family: "Cremona";
  src: url(/fonts/Cremona.ttf);
}
@font-face {
  font-family: "Avenir-Next";
  src: url(/fonts/Avenir-Next.ttf);
}
@font-face {
  font-family: "Butler_Medium_Stencil";
  src: url(/fonts/Butler_Medium_Stencil.ttf);
}
body {
  font-size: 0em;
}
.inline-block{
  display: inline-block;
}
.Vibha-detail-page {
  width: 100%;
  display: flex;
  font-family: "DB-Ozone-X";
  color: black;
}
.Vibha-detail-left {
  width: 50%;
}
.Vibha-detail-right {
  width: 50%;
  font-size: 35px;
}
.Vibha-detail-top {
  background-color: #93a49e;
}
.Vibha-detail-bottom {
  padding-left: 18%;
  padding-top: 13%;
  padding-right: 5%;
  padding-bottom: 15%;
  font-size: 24px;
  font-family: "SukhumvitSet";
  font-weight: bold;
}
.Vibha-detail-description-swapDesktop {
  font-size: 24px;
  font-family: "SukhumvitSet";
  font-weight: bold;
}
.Vibha-detail-top p {
  font-size: 88px;
  padding-left: 20%;
  padding-top: 28%;
  font-weight: bold;
}
.Vibha-detail-top img {
  padding-left: 20%;
  width: 50%;
}
.Vibha-detail-img {
  width: 100%;
}
.Vibha-detail-tree {
  width: 14%;
  padding-bottom: 5%;
}
.Vibha-detail-tree-center {
  text-align: center;
  margin-left: -12%;
  margin-top: 4%;
}
.Vibha-detail-right p {
  padding-top: 5%;
}
div.vertical-line {
  width: 4px;
  background-color: #1e2f27;
  height: 120%;
  float: left;
  margin-left: 6.2%;
  position: absolute;
  z-index: 1;
  margin-top: -5%;
}
.Vibha-detail-top-img {
  margin-left: -2%;
  margin-bottom: -10%;
}
.Vibha-detail-top-header {
  margin-left: -2%;
  color: black;
  font-family: "Butler_Medium_Stencil";
  font-weight: bold;
  font-size: 40px;
}
.Vibha-detail-description-right {
  padding-right: 10%;
  padding-left: 2%;
}
.Vibha-detail-img-mobile {
  display: none;
}
.Vibha-detail-description-swapMobile {
  display: none;
}
@media screen and (max-width: 1700px) {
  div.vertical-line {
    height: 121%;
  }
}
@media screen and (max-width: 1500px) {
  .Vibha-detail-top p {
    font-size: 72px;
  }
  .Vibha-detail-bottom {
    font-size: 22px;
  }
  .Vibha-detail-description-swapDesktop {
    font-size: 22px;
  }
}
@media screen and (max-width: 1400px) {
  .Vibha-detail-bottom {
    font-size: 20px;
  }
  .Vibha-detail-description-swapDesktop {
    font-size: 20px;
  }
  div.vertical-line {
    height: 103%;
  }
}
@media screen and (max-width: 1300px) {
  .Vibha-detail-top p {
    font-size: 66px;
  }
  div.vertical-line {
    height: 103%;
  }
}
@media screen and (max-width: 1200px) {
  .Vibha-detail-top p {
    font-size: 60px;
  }
}
@media screen and (max-width: 1100px) {
  div.vertical-line {
    height: 92%;
  }

  .Vibha-detail-top p {
    font-size: 53px;
  }
  .Vibha-detail-bottom {
    font-size: 19px;
  }
  .Vibha-detail-description-swapDesktop {
    font-size: 19px;
  }
}
@media screen and (max-width: 1024px) {
  div.vertical-line{
    height: 55%;
    width: 2px;
}
}
@media screen and (max-width: 1000px) {
  .Vibha-detail-bottom {
    font-size: 16px;
  }
  .Vibha-detail-description-swapDesktop {
    font-size: 16px;
  }
  div.vertical-line {
    height: 83%;
  }
}
@media screen and (max-width: 900px) {
  .Vibha-detail-top p {
    font-size: 43px;
  }
}
@media screen and (max-width: 800px) {
  .Vibha-detail-top p {
    font-size: 40px;
  }
  .Vibha-detail-bottom {
    font-size: 15px;
  }
  .Vibha-detail-description-swapDesktop {
    font-size: 15px;
  }
}
@media screen and (max-width: 768px) {
  .Vibha-detail-left {
    width: 100%;
  }
  .Vibha-detail-bottom {
    font-size: 18px;
  }
  .Vibha-detail-top-img {
    margin-bottom: -8%;
    margin-top: -3%;
  }
  div.vertical-line {
    margin-top: -16%;
    height: 238%;
    width: 2px;
  }
  .Vibha-detail-page {
    display: block;
  }
  .Vibha-detail-right {
    width: 100%;
    font-size: 16px;
  }
  .Vibha-detail-img-mobile {
    display: block;
  }
  .Vibha-detail-img-desktop {
    display: none;
  }
  .Vibha-detail-description-swapDesktop {
    display: none;
  }
  .Vibha-detail-description-swapMobile {
    display: flex;
    width: 100%;
    padding-left: 12%;
  }
  .Vibha-detail-swapMobile {
    width: 50%;
    padding: 2%;
    font-size: 17px;
    font-family: "SukhumvitSet";
    font-weight: bold;
    display: block;
  }
  .Vibha-detail-description-right {
    padding-right: 0%;
    padding-left: 0%;
  }
  .Vibha-detail-tree {
    margin-left: -22%;
    margin-top: -7%;
  }
  .Vibha-detail-top p {
    font-size: 50px;
  }
  .project-type-option {
    height: 0%;
  }
  .Vibha-detail-top p {
    padding-top: 18%;
  }
  div.vertical-line {
    height: 190%;
}
}
@media screen and (max-width: 700px) {
  div.vertical-line {
    height: 225%;
  }
}
@media screen and (max-width: 600px) {
  div.vertical-line {
    height: 217%;
  }
  .Vibha-detail-description-swapMobile {
    padding-left: 11%;
  }
}
@media screen and (max-width: 595px) {
  .Vibha-detail-swapMobile {
    font-size: 16px;
  }
  .Vibha-detail-description-swapMobile {
    padding-left: 9%;
  }
}
@media screen and (max-width: 500px) {
  div.vertical-line {
    height: 180%;
  }
  .Vibha-detail-bottom {
    font-size: 15px;
  }
  .Vibha-detail-swapMobile {
    font-size: 15px;
  }
}
@media screen and (max-width: 400px) {
  div.vertical-line {
    height: 150%;
  }
  .Vibha-detail-swapMobile {
    font-size: 12px;
  }
  .Vibha-detail-bottom {
    font-size: 12px;
  }
}
@media screen and (max-width: 375px) {
  .Vibha-detail-left {
    width: 100%;
  }
  .Vibha-detail-bottom {
    font-size: 12px;
  }
  .Vibha-detail-top-img {
    margin-bottom: -8%;
    margin-top: -3%;
  }
  div.vertical-line {
    height: 145%;
  }
  .Vibha-detail-page {
    display: block;
  }
  .Vibha-detail-right {
    width: 100%;
    font-size: 16px;
  }
  .Vibha-detail-img-mobile {
    display: block;
  }
  .Vibha-detail-img-desktop {
    display: none;
  }
  .Vibha-detail-description-swapDesktop {
    display: none;
  }
  .Vibha-detail-description-swapMobile {
    display: flex;
    width: 100%;
    padding-left: 12%;
  }
  .Vibha-detail-swapMobile {
    width: 50%;
    padding: 2%;
    font-size: 12px;
    font-family: "SukhumvitSet";
    font-weight: bold;
  }
  .Vibha-detail-description-right {
    padding-right: 0%;
    padding-left: 0%;
  }
  .Vibha-detail-tree {
    margin-left: -22%;
    margin-top: -7%;
  }
  .Vibha-detail-top p {
    font-size: 50px;
  }
  .project-type-option {
    height: 0%;
  }
}
</style>