<script setup>

</script>

<template>
  <div class="max-w-1440">
    <div >
      <div class="section grid">
        <p class="font-white title">Never transcribe manually again</p>
        <p class="content">
          Tanscribe clips from any Avid Media Composer project with ease. Say goodbye to the hassle of exporting to
          Quicktimes or uploading clips one-by-one to a subpar prosumer tool.
          Made for professionals, by professionals.
        </p>
        <div class="section_center">
          <div class="mailinput">
            <input placeholder="Enter your email" />
            <button>Request Beta Access</button>
          </div>
        </div>
      </div>
      <div class="section  section_2 ">
        <img src="../assets/images/section2.png" alt="image" />
      </div>
      <div class="section  section_3">
        <p>EdMon speeds up your transcribing, searching and pre-editing of video, saving you hours of work.</p>
        <div class="watch_btn_t">
          <img src="../assets/images/watch_btn.png" alt="image" />
          <h5>Watch video</h5>
        </div>
      </div>
      <div class="section  V_display section_4">
        <img src="../assets/images/Maskgroup(1).png" alt="Mask group (1)" />
        <div>
          <h3>Batch transcribe</h3>
          <p>With just a few clicks, you can open an Avid project file, select the clips you want to transcribe, and in
            minutes, you/'ll have fully transcribed text available on our cloud-based platform.</p>
        </div>

      </div>
      <div class="section  V_display section_5">
        <div>
          <h3>Online access</h3>
          <p>The transcribed video is stored on our cloud platform, accessible from anywhere and organized in a way that
            matches your Media Composer project.</p>
        </div>
        <img src="../assets/images/Maskgroup(2).png" alt="Mask group(1)" />
      </div>
      <div class="section  V_display section_6">
        <img src="../assets/images/Maskgroup(3).png" alt="Mask group(1)" />
        <div>
          <h3>Text based editing</h3>
          <p>Browse through the text, pick and choose the parts you want, and add them to a rough cut. The process of
            editing is now faster and more efficient, allowing you to search and select in text instead of video.
            Finally,
            export your selections as an AAF file and seamlessly integrate them back into Media Composer.</p>
        </div>

      </div>
      <div class="section  V_display section_7">
        <div>
          <h3>Roundtrip from MC to EdMon (and back)</h3>
          <p>Enjoy the convenience of editing a rough cut in text instead of video, and send your final product back to
            Media Composer for fine-tuning. With our AAF exports, you'll be able to link back to your original Media
            Composer clips instantly.</p>
        </div>
        <img src="../assets/images/Maskgroup(4).png" alt="Mask group (1)" />
      </div>
      <div class="section learn grid">
        <h1>Less pain - more editing.</h1>
        <p>
          EdMon is a professional tool specifically designed for Avid editors. It can transcribe multiple video files in
          one go, created for editors who need to transcribe large volumes of video content (like hours of interviews
          for
          a documentary).
          <br />
          In short, EdMon is the ideal solution for Avid editors who need to transcribe large amounts of video content
          quickly and efficiently. Less pain - more editing.

        </p>
        <div class="section_center">
          <div class="mailinput">
            <input placeholder="Enter your email" />
            <button>Request Beta Access</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
 .grid{
  display: grid;
 }

.section .title {
  text-align: center;
  font-family: 'Inter', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 100px;
  margin: 100px 106px;
  line-height: 121px;
}

.content {
  margin: 10px 349px;
  font-family: 'Inter', sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 141.52%;
  text-align: center;
  letter-spacing: 0.04em;

  color: #C0C0C0;
}

.section_center {
  display: flex;
  justify-content: center;
}

.mailinput {
  margin-top: 35px;
  display: flex;
  width: 660px;
  height: 64px;
  box-sizing: border-box;
  background: #fff0;
  border: 0.5px solid #FFFFFF;
  border-radius: 32px;
  align-items: center;
  justify-content: space-between;
  line-height: 22px;
  padding-left: 32px;
  color: #A8A8A8;
}

.mailinput button {
  box-sizing: border-box;
  width: 235px;
  height: 54px;
  color: #424242;
  border: 0.5px solid #FFFFFF;
  border-radius: 32px;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  margin-right: 5px;
  cursor: pointer;
}

.mailinput input {
  background-color: #fff0;
  font-family: 'Inter', sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  width: 350px;
  height: 40px;
}

.section_2 {
  background-size: cover;
  background-image: url('../assets/images/section2_bg.png');
}

.section_2 img {
  margin-top: 91px;
}

.section_3 {
  background-size: cover;
  height: 770px;
  background-image: url('../assets/images/section3_bg.png');
}

.section_3 p {
  max-width: 928px;
  height: 171px;
  font-style: normal;
  font-weight: 500;
  font-size: 40px;
  line-height: 141.52%;
  text-align: center;
  letter-spacing: 0.04em;

  color: #E0E0E0;
}

.watch_btn_t {
  display: flex;
  align-items: center;
}

.watch_btn_t h5 {
  padding-left: 32px;

}

.V_display {
  flex-direction: row;
  background-repeat: no-repeat;
  background-position: center;

}

.section_4 {
  background-image: url('../assets/images/section4_bg.png');
}

.section_4 img {
  padding-left: 255px;
}

.section_5 {
  background-image: url('../assets/images/section5_bg.png');
}

.section_5 img {
  padding-right: 222px;
}

.section_6 {
  background-image: url('../assets/images/section6_bg.png');
}

.section_6 img {
  padding-left: 255px;
}

.section_7 {
  background-image: url('../assets/images/section7_bg.png');
}

.section_7 img {
  padding-right: 222px;
}

.V_display div {
  max-width: 268px;
  margin: 32px 94px 0 108px;
}

.V_display div p {
  margin-top: 32px;
  font-size: 18px;
  color: #F1F1F1;
}

.V_display div h3 {
  font-size: 32px;
  color: #E0E0E0;
}

.learn {
  background: linear-gradient(180deg, rgba(0, 0, 0, 0)0%, rgba(29, 52, 254, 0.224) 134.17%);
}

.learn h1 {
  font-weight: 700;
  font-size: 80px;
  line-height: 141.52%;
  /* or 113px */

  text-align: center;
  letter-spacing: 0.04em;

  color: #FFFFFF;
}

.learn p {
  max-width: 928px;
  font-weight: 400;
  font-size: 24px;
  line-height: 141.52%;
  /* or 34px */

  text-align: center;

  color: #FFFFFF;
}

@media (max-width: 1200px) {
  .section.grid{
    text-align: left; 
  }
  .section.grid p{
    text-align: left;
    margin-left: 7%;
  }
  .section .title{
    margin-bottom: 0;
  }
}

</style>