<template>
  <div class="all">
    <div class="contain">
      <header>
      <div class="row header_top">
        <div class="logo col-5">
          <img src="../assets/rabbiz/logo.png" alt="" />
        </div>
        <div class="div_menu col-7">
          <!-- <ul class="menu">
            <li>HOME</li>
            <li>RABBIZ FARM</li>
            <li>TRADE</li>
            <li>SHOT BALL</li>
            <li>DASHBOARD</li>
          </ul> -->
          <nav class="navbar">
            <div class="push-left">
              <button
                id="menu-toggler"
                data-class="menu-active"
                class="hamburger"
              >
                <span class="hamburger-line hamburger-line-top"></span>
                <span class="hamburger-line hamburger-line-middle"></span>
                <span class="hamburger-line hamburger-line-bottom"></span>
              </button>

              <!--  Menu compatible with wp_nav_menu  -->
              <ul id="primary-menu" class="menu nav-menu">
                <li class="menu-item current-menu-item">
                  <a class="nav__link" href="#">Home</a>
                </li>
                <li class="menu-item">
                  <a class="nav__link" href="#">RABBIZ FARM</a>
                </li>
                <li class="menu-item">
                  <a class="nav__link" href="#">TRADE</a>
                </li>
                <li class="menu-item">
                  <a class="nav__link" href="#">SHOT BALL</a>
                </li>
                <li class="menu-item">
                  <a class="nav__link" href="#">DASHBOARD</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
      </div>
      <div class="row header_center">
        <div class="col-6">
          <h1 class="title_solgan">Rabbiz</h1>
          <p class="solgan">A leading Yield Farming from China</p>
        </div>
        <div class="col-6">
          <img id="img_header" src="../assets/rabbiz/img_header.png" alt="" />
        </div>
      </div>
    </header>
    </div>
    

    <div class="introduction">
     
      <div class="contain">
        <div class="title"><i class="title_text">INTRODUCTION</i></div>
        <div class="row troduction_content">
          <div class="col-lg-6 ">
             <img
        id="introduction_img"
        src="../assets/rabbiz/introduction_img.png"
        alt=""
      />
          </div>
          <div class="col-lg-6 introduction_left_text">
            <div class="introduction_textbox">
              <p class="introduction_text">
                Rabbiz is a blockchain-based decentralized financial application
                of Tron(Trx). Thisis a DeFi project that has the most attention
                recently.
              </p>
              <p class="introduction_text">
                Rabbiz is a token with exponential growth over time due to
                trading on major exchanges, accompanied with interesting and fun
                games during user's participation.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="vision_mission_tittle">
        <p>VISION & MISSION</p>
      </div>
    </div>

    <div class="vision_mission">
      <!-- <div>
           <img src="../assets/rabbiz/vision_mission1.png" alt="">
         </div> -->

      <div class="contain">
        <div class="content">
          <span id="vision_mission_text1">
            <p>
              Rabbiz will become the top 30 Crypto in the Cryptocurrency market.
            </p>
          </span>
          <span id="vision_mission_text2">
            <p>
              Rabbiz helps users to maximize personal finances in the most
              efficient manner through its ecosystems.
            </p>
          </span>
          <span id="vision_mission_text3">
            <p>
              Rabbiz offers its users the most diverse, unique ecosystem in the
              financial markets.
            </p>
          </span>
          <span id="vision_mission_text4">
            <p>
              Rabbiz helps users to connect with each other simply, easily and
              conveniently through the internet.
            </p>
          </span>
          <img
            id="vision_mission_img"
            src="../assets/rabbiz/vision_mission.png"
            alt=""
          />
        </div>
      </div>
    </div>
    <div class="vision_mission2">
      <ul class="list_vision_mission">
        <li>
          <span class="cha"><span class="con"></span></span>
          Rabbiz will become the top 30 Crypto in the Cryptocurrency market.
        </li>
        <li>
          <span class="cha"><span class="con"></span></span>
          Rabbiz helps users to maximize personal finances in the most efficient
          manner through its ecosystems.
        </li>
        <li>
          <span class="cha"><span class="con"></span></span>
          Rabbiz offers its users the most diverse, unique ecosystem in the
          financial markets.
        </li>
        <li>
          <span class="cha"><span class="con"></span></span>
          Rabbiz helps users to connect with each other simply, easily and
          conveniently through the internet.
        </li>
      </ul>
    </div>
    <div class="advantages_title">
      <I>ADVANTAGES</I>
    </div>

    <div class="contain">
      <div class="row advantage">
        <div class="col-6 advantages_list_text">
          <div>
            <ul class="list_advantages">
              <li>
                <span class="cha"><span class="con"></span></span>
                The most novel and appealing DeFi application currently.
              </li>
              <li>
                <span class="cha"><span class="con"></span></span>
                Limited amount of tokens, resulting in scarcity.
              </li>
              <li>
                <span class="cha"><span class="con"></span></span>
                High security, low cost, fast and accurate confirmation time.
              </li>
              <li>
                <span class="cha"><span class="con"></span></span>
                Diverse and attractive ecosystem that is easy to join.
              </li>
            </ul>
          </div>
        </div>
        <div class="col-6 div_of_avantages_img">
          <img
            id="advantages_img"
            src="../assets/rabbiz/advantages_img.png"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- token rabbiz -->
    <div class="advantages_title">
      <I>TOKEN RABBIZ</I>
    </div>
    <!-- quan -->
  </div>
</template>

<script>
import jQuery from "jquery";
window.jQuery = jQuery;
jQuery(document).ready(function () {
  // Toggle menu on click
  jQuery("#menu-toggler").click(function () {
    toggleBodyClass("menu-active");
  });

  function toggleBodyClass(className) {
    document.body.classList.toggle(className);
  }
});

export default {};
</script>
<style>
.contain {
    width: 1900px;
    margin: 0 auto;
}

* {
  margin: 0;
  padding: 0;
}
/* .navbar{
  display: none !important;
} */
.advantage {
  padding: 2vw 0px;
}
.advantages_list_text {
  display: flex;
  justify-content: center;
  align-items: center;
}
.list_advantages li {
    list-style: none;
    padding: 18px 0px;
    text-align: left;
    font-weight: 800;
    font-size: 24px;
}
.cha {
  background-color: white;
  border: #fe779f solid 3px;
  height: 25px;
  width: 25px;
  border-radius: 50%;
  display: inline-flex;
  justify-content: center;
  align-items: center;
}
.con {
  background-color: #fe779f;
  height: 15px;
  width: 15px;
  border-radius: 50%;
  display: inline-block;
}
#advantages_img {
  width: 100%;
}
.div_of_avantages_img {
  display: flex;
  justify-content: center;
  align-items: center;
}
.advantages_title {
  background-color: #ff7a9d;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.advantages_title i {
    color: white;
    font-weight: 600;
    font-size: 50px;
    padding: 21px 0px;
}
.vision_mission2 {
  display: none;
}
#vision_mission_img {
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
}
#vision_mission_text4 {
  position: absolute;
  bottom: 22%;
  color: #a16c78;
  text-align: left;
  word-spacing: 5px;
  height: 1vw;
  width: 30%;
  right: 3%;
  z-index: 10;
  font-size: 24px;
}
#vision_mission_text3 {
  position: absolute;
  bottom: 22%;
  color: #a16c78;
  text-align: left;
  font-size: 24px;
  word-spacing: 5px;
  height: 1vw;
  width: 30%;
  left: 4%;
  z-index: 10;
}
#vision_mission_text2 {
  position: absolute;
  color: #a16c78;
  text-align: left;
  word-spacing: 5px;
  height: 1vw;
  width: 30%;
  top: 9%;
  right: 3%;
  z-index: 10;
  font-size: 24px;
}
.vision_mission .content {
  position: relative;
  width: 100%;
  height: 650px;
}

#vision_mission_text1 {
  position: absolute;
  color: #a16c78;
  text-align: left;
  word-spacing: 5px;
  height: 1vw;
  top: 12%;
  left: 4%;
  z-index: 10;
  font-size: 24px;
  width: 30%;
}
.vision_mission {
  padding: 120px 0px;
}
.vision_mission_tittle {
  background-color: #ff7a9d;
  position: absolute;
  width: 100%;
  bottom: -100px;
}
.vision_mission_tittle p {
    color: white;
    font-weight: 600;
    font-size: 50px;
    padding: 12px 0px;
    font-style: italic;
}
.introduction img {
    position: absolute;
    top: 0;
    left: 0;
    height: 675px;
}
.introduction_text {
    line-height: 57px;
    font-size: 26px;
    text-align: left;
    margin: 15px 0px 0px 20px;
}
.introduction_textbox {
  border: 1px solid black;
  border-radius: 10px;
  height: auto;
  width: 100%;
  margin: 120px 0;
}
.introduction_left_text {
  display: flex;
  justify-content: center;
  align-items: center;
}

.introduction_image_form {
  padding-left: 0px !important;
  padding-right: 0px !important;
}
.title {
    background-color: transparent;
    position: absolute;
    z-index: 2;
    top: 2%;
    left: 0;
    width: 100%;
}
/* .title_text {
  font-weight: 800 !important;
  font-size: 70px !important;
} */
.troduction_content {
  display: none;
}
.introduction {
  background-color: transparent;
  position: relative;
 height: 600px;
}
.row {
  margin-left: 0px !important;
  margin-right: 0px !important;
}
.title_solgan {
  font-size: 200px;
  color: white;
  letter-spacing: 20px;
}
.solgan {
  color: white;
  background-color: #fac0ce;
  font-size: 40px;
  display: inline-block;
  letter-spacing: 2px;
}
.header_top {
  height: 10%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.header_center {
  height: 90%;
  display: flex;
  align-items: center;
}
header {
  background: url("../assets/rabbiz/background_header.png") center;
  background-size: cover;
  height: 100vh;
}
.menu li {
    list-style: none;
    float: left;
    padding: 21px;
    color: white;
    font-size: 25px;
    cursor: pointer;
    transition: 0.75s;
}
.menu li:hover {
  color: #cce8ff;
}
.menu {
  float: right;
  margin: 0px 50px;
}
#img_header {
  width: 70%;
  object-fit: cover;
}
.logo {
  height: 100%;
}
.logo img {
  float: left;
  width: 24%;
  font-size: 80px;
  margin-left: 5%;
  margin-top: 3%;
}
.div_menu {
  height: 100%;
}

.title_text {
  color: #ff7a9d;
  font-weight: 600;
  font-size: 50px;
}
.all {
  background-image: url("../assets/rabbiz/background.png");
}
</style>