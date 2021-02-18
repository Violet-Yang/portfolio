<template>
  <div>
    <div style="background-color: #f3f3f3; width: 100vw;">
      <section
        class="menu"
        style="
          background-color: #f3f3f3;
          border-bottom: 1px solid lightgray;
          max-width: 1000px;
        "
      >
        <div style="display: flex" class="menu-content">
          <div id="logo">Y.JIEUN</div>
          <div class="menu-list">
            <div class="click-menu"><a href="#home">HOME</a></div>
            <div class="click-menu"><a href="#about-me">ABOUT ME</a></div>
            <div class="click-menu"><a href="#portfolio">PORTFOLIO</a></div>
            <div class="click-menu"><a href="#home">BLOG</a></div>
          </div>
        </div>

        <div
          style="width: 100%; height: 100%; background-color: slateblue"
          class="menu-content-s flex-align-center flex-between"
        >
          <div style="margin-left: 20px" id="logo-s">Y.JIEUN</div>
          <div style="margin-right: 20px">
            <img style="width: 100%" src="static/img/barbadak.png" />
          </div>
        </div>
      </section>

      <!--about me-->
      <section class="about-me" id="about-me">
        <div class="content1">
          <h1
            style="
              font-size: 34px;
              letter-spacing: 4px;
              line-height: 1.2;
              font-weight: bold;
              margin-top: 120px;
            "
          >
            JUNIOR <br />
            FRONT-END ENGINEER
          </h1>
          <hr />
          <p style="margin-top: 40px" class="info">
            <span style="font-size: 25px; font-weight: bold">양지은</span>
            <br />
            1991.04.10<br />
            +82 10-6644-0155 <br />
            violet91410@gmail.com
          </p>

          <!-- circles -->
          <div class="circles">
            <!--1st circle-->
            <div class="circle-area">
              <div class="motto">
                <div style="display: flex; justify-content: center">
                  <div class="circle">
                    <img style="width: 90%" src="static/img/dog.png" />
                  </div>
                </div>
                <h2>MOTTO</h2>
                <p class="pen">
                  <span style="color: #42b983; font-weight: bold"
                    >도전하는 삶</span
                  >을 지향하는 웹 개발자입니다. 자기계발로 시작했던 퍼블리싱에서
                  신세계를 경험하고, 자바스크립트에 푹 빠져 프론트엔드 개발자가
                  되었습니다.
                </p>
              </div>
            </div>
            <!-- 2nd circle-->
            <div class="circle-area">
              <div class="motto">
                <div style="display: flex; justify-content: center">
                  <div class="circle">
                    <img style="width: 90%" src="static/img/dog.png" />
                  </div>
                </div>
                <h2>PUBLISHER</h2>
                <p class="pen">
                  <span style="font-weight: bold"
                    >HTML5, CSS3, Javascript(ES6+), MEDIA QUERIES</span
                  >를 사용하여 요구사항을 구현할 수 있습니다.
                </p>
              </div>
            </div>
            <!-- 3nd circle-->
            <div class="circle-area">
              <div class="motto">
                <div style="display: flex; justify-content: center">
                  <div class="circle">
                    <img style="width: 90%" src="static/img/dog.png" />
                  </div>
                </div>
                <h2>Front-end Developer</h2>
                <p class="pen">
                  웹의 전반적인 지식을 가지고 있으며,
                  <span style="font-weight: bold">Vue</span>를 사용한
                  <span style="font-weight: bold">Single Page Application</span>
                  개발에 자신이 있습니다.<br />
                  또한, 개발지식을 기억하고자 학습블로그를 기록하며
                  공부중입니다.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section
        class="portfolio"
        id="portfolio"
        style="background-color: #ffffff;"
      >
        <div class="content2">
          <h1
            style="
              font-size: 40px;
              letter-spacing: 5px;
              line-height: 1.2;
              padding-top: 120px;
            "
          >
            PORTFOLIO
          </h1>
          <hr />
          <div
            class="portfolio-list"
            style="display: flex; justify-content: center; margin-top: 50px;"
          >
            <div
              class="each"
              style="
                margin: 0 auto;
                padding: 10px;
                text-align: left;
              "
            >
              <div class="area" style="border-left: 3px solid black;">
                <div class="text-area" style="padding-left : 10px">
                  <h2 style="font-size: 15px">2020.09 ~ 2021.01</h2>
                  <h2 style="letter-spacing: -1.4px">별별귤팜</h2>

                  <div class="overview">
                    <div class="flex-align-center" style="margin-top: 5px">
                      <img
                        style="width: 6%; max-width: 30px"
                        src="static/img/icon_github.png"
                      /><span class="description"
                        ><a href="">Github Link</a></span
                      >
                    </div>
                    <div class="flex-align-center" style="margin-top: 7px">
                      <img
                        style="width: 6%; max-width: 30px"
                        src="static/img/icon_globe.png"
                      /><span class="description"
                        ><a href="https://www.bbgfarm.shop/">Site Link</a></span
                      >
                    </div>
                  </div>
                </div>
                  <div class="img-area" style="padding-left: 10px">
                    <img src="static/img/img_bbgfam.jpg" />
                  </div>

                  <div class="img-area-s">
                    <div>
                      <img
                        style="width: 100%"
                        src="static/img/img_bbgfam_s.JPG"
                      />
                    </div>
                  </div>

                  <p
                    class="intro"
                    style="
                      width: 100%;
                      font-size: 14px;
                      font-weight: 400;
                      line-height: 1.6;
                      margin: 5px 0;
                      letter-spacing: -0.9px;
                      padding-left : 10px
                    "
                  >
                    제주도 산 귤, 농장을 소개하고 판매하는 플랫폼
                    <br />
                    5인 팀에서 프론트엔드 일부 개발 담당
                  </p>

                <div class="between-box" style="max-width: 1200px; margin: 15px">
                  <div class="between-box-in1">
                    <h3 style="font-weight: 550; letter-spacing: -0.8px">
                      What I did
                    </h3>
                    <div class="underline"></div>
                    <p class="contain-text">
                      메인, 농장, 장바구니 화면 및 기능 개발
                    </p>
                  </div>

                  <div class="between-box-in2">
                    <h3 style="font-weight: 550; letter-spacing: -0.8px">
                      Stack
                    </h3>
                    <div class="underline"></div>
                    <p class="contain-text">
                      HTML5/CSS3 기반 퍼플리싱<br />
                      Vue.js 활용 프론트엔드 기능 구현<br />
                      Rest API 연동
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- contact -->
      <section class="contact" id="contact" style="background-color: #f3f3f3">
        <div class="content3">
          <h1
            style="
              font-size: 40px;
              letter-spacing: 5px;
              padding-top: 120px;
              line-height: 1.2;
            "
          >
            BLOG
          </h1>
          <hr />
          <h1 style="font-size: 40px; letter-spacing: 5px; line-height: 1.2">
            CONTACT
          </h1>
          <h1 style="font-size: 40px; letter-spacing: 5px; line-height: 1.2">
            CONTACT
          </h1>
          <h1 style="font-size: 40px; letter-spacing: 5px; line-height: 1.2">
            CONTACT
          </h1>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "Index",
  created() {
    let vue = this;
    this.currentScrollValue = document.documentElement.scrollTop;

    document.addEventListener("scroll", function () {
      vue.currentScrollValue = document.documentElement.scrollTop; //document는 html, scrollTop은top으로부터 scroll된 값을 의미한다.
      // console.log("currentScrollValue is " + vue.currentScrollValue);
    });
  },
};
</script>

<style scoped>
a {
  list-style: none;
  text-decoration: none;
  font-size: 16px;
}

/* 메뉴별 밑줄 */
hr {
  color: black;
  margin-top: 30px;
  background-color: black;
  height: 1px;
  width: 106px;
  border: 0;
}

.start-page {
  width: 100%;
  /*background: url("./static/img/giraffe.jpg") fixed no-repeat;*/
}

.menu-content {
  display: flex;
  width: 100%;
  margin: 0 auto;
}

.menu {
  width: 100%;
  height: 60px;
  background-color: #ffffff;
  border-bottom: 1px solid #f2f2f2;
}

/* font YANGJIEUN */
#logo {
  line-height: 60px; /* <-- 해당 css로 옆의 menu flex속성이 적용됨 */
  font-size: 24px;
  width: 300px;
  text-align: left;
  font-weight: bold;
}
#logo-s {
  line-height: 60px; /* <-- 해당 css로 옆의 menu flex속성이 적용됨 */
  font-size: 24px;
  text-align: left;
  font-weight: bold;
  color: white;
}

/* 전체 탑 네비게이션 바*/
.menu-list {
  display: flex;
}

.menu-list > div {
  margin: 0 20px;
}
.click-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
/* about me 부터 content영역 */
/*#about-me, .content {*/
/*  width: 100%;*/
/*  max-width: 1200px;*/
/*  margin: 0 auto;*/
/*}*/

/* 내정보 */
.info {
  color: #757575;
  margin: 0 auto;
  width: 300px;
  line-height: 25px;
  letter-spacing: 1px;
  font-size: 16px;
  font-weight: 300;
  text-align: center;
}

/* about me 하단 동그라미 영역 div */
.circle-area {
  width: 300px;
  height: 100%;
}
/* about me 하단 동그라미 영역 */
.circle {
  display: flex;
  justify-content: center;
  width: 120px;
  height: 120px;
  border: 3px solid #f0f0f0;
  border-radius: 70px;
}
/* about me 하단 작은제목 영역 */
.motto {
  width: 100%;
  height: 250px;
  margin-top: 40px;
  margin-bottom: 120px;
}
.motto h2 {
  margin-top: 40px;
}
/* about me 하단 제목별 글 영역 */
.pen {
  /*padding: 15px 10px;*/
  text-align: center;
  font-size: 14px;
  width: 260px;
  margin: 30px auto;
  /*color: #a4a4a4;*/
  /*color: #808080;*/
  color: #757575;
  line-height: 24px;
  letter-spacing: 0;
  font-weight: 300;
}

/* 포트폴리오 영역 큰 div */
/*.area {*/
/*  display: flex;*/
/*}*/

/* 아이콘 설명 글씨 */
.description {
  color: rgba(63, 63, 63, 1);
  margin-left: 10px;
}

.description a {
  font-size: 21px;
  letter-spacing: -0.6px;
  color: goldenrod;
}

.description a:hover {
  text-decoration: underline;
}
/* 소제목 밑줄 */
.underline {
  width: 200px;
  height: 1px;
  margin: 3px 0;
  background-color: rgb(52, 58, 64);
}
/* 설명영역 */
.contain-text {
  /*padding: 15px 10px;*/
  font-size: 14px;
  line-height: 24px;
  letter-spacing: -0.5px;
  font-weight: 300;

  color: #232323;
}

/* 영역 안 키워드 */
.radius {
  padding: 5px 10px;
  border-radius: 10px;
  background-color: lightgray;
  color: #2c3e50;
}

/* 미디어쿼리 -> 반응형 */
@media (min-width: 320px) and (max-width: 767px) {
  .menu {
    background-color: blueviolet;
    width: 100%;
    height: 60px;
  }

  #logo,
  .menu-list {
    display: none !important;
  }
  .menu-content {
    display: none;
  }

  .circles {
    display: block;
  }

  .circle-area {
    width: 100%;
  }

  .img-area-s {
    margin-top: 20px;
    margin-left: 10px;

  }
  .img-area {
    display: none;
  }
  .between-box {
    display: block;
  }
  .between-box-in2 {
    margin-top: 10px;
  }
}

@media (min-width: 768px) and (max-width: 1023px) {
  #logo {
    /*display: flex;*/
    width: 200px;
    margin: 0 auto;
  }

  .menu-content-s {
    display: none;
  }

  /*.content1 {*/
  /*  margin: 0 auto;*/
  /*}*/

  .circles {
    display: flex;
    justify-content: center;
  }

  .img-area-s {
    display: none;
  }
  .img-area {
    margin-left: 20px;
  }
  .between-box {
    display: flex;
  }
  .between-box-in1,
  .between-box-in2 {
    width: 50%;
  }
}

@media (min-width: 1024px) and (max-width: 3000px) {
  .menu {
    margin: 0 auto;
  }

  #logo {
    display: flex;
    width: 300px;
    margin: 0 auto;
  }
  .menu-list {
    width: 500px;
  }
  .menu-content-s {
    display: none;
  }

  .circles {
    display: flex;
    justify-content: center;
  }

  .circles,
  area {
    display: flex;
  }

  .img-area-s {
    display: none;
  }
  .img-area {
    margin-left: 20px;
  }
  .between-box {
    display: flex;
  }
  .between-box-in1,
  .between-box-in2 {
    width: 50%;
  }
}
</style>
