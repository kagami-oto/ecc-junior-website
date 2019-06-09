<template>
  <div class="main">
    <div class="bricks bricks--left"></div>
    <div class="bricks bricks--right"></div>
    <div id="wrapper">
      <Header/>
      <article>
        <About/>
        <News/>
        <Schedule/>
        <section id="teachers" class="teachers--main">
          <h1 class="section--title with-leaf">TEACHERS</h1>
          <p>ねこねこねこ</p>
          <h2 class="section--header-text">James Bond</h2>
          <p>これはダミーテキストです。先生の自己紹介文をここに記載します。これはダミーテキストです。先生の自己紹介文をここに記載します。これはダミーテキストです。先生の自己紹介文をここに記載します。</p>
        </section>
        <!--teachers-->
        <section id="contact" 　class="contact--main">
          <h1 class="section--title with-leaf">CONTACT</h1>
          <img src="images/" alt="地図入れるとこ" width="348" height="149">
          <h2 class="section--header-text">Address</h2>
          <p>〒123-4567</p>
          <p>東京都世田谷区玉川2-22-13</p>
          <h2 class="section--header-text">Contact Info</h2>
          <p>電話番号 12-1234-1234</p>
          <p>メール bcdef@abc.jp</p>
        </section>
        <!--end #contact-->
      </article>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from "./Header";
import About from "./About";
import News from "./News";
import Schedule from "./Schedule";
import Footer from "./Footer";

export default {
  name: "Main",
  components: {
    Header,
    About,
    News,
    Schedule,
    Footer
  }
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "../css/variables/variables.scss";
@import "../css/variables/colors.scss";
@import "../css/base/reset.scss";
@import "../css/base/base.scss";
</style>
