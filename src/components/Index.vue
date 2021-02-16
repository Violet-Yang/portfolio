<template>
  <div>
    <div>
      <section class="start-page" id="home">
        <img src="static/img/giraffe.jpg" />
      </section>
      <section class="menu" style="background-color: white">
        <div style="display: flex" class="menu-content">
          <div id="logo">Y.JIEUN</div>
          <div class="menu-list">
            <div class="click-menu"><a href="#home">HOME</a></div>
            <div class="click-menu"><a href="#about-me">ABOUT ME</a></div>
            <div class="click-menu"><a href="#portfolio">PORTFOLIO</a></div>
            <div class="click-menu"><a href="#home">BLOG</a></div>
          </div>
        </div>
      </section>

      <!--about me-->
      <section class="about-me" id="about-me">
        <div class="content">
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
            FRONT-END <br />
            ENGINEER
          </h1>
          <hr />
          <p class="info">
            <span style="font-size: 25px; font-weight: bold">양지은</span>
            <br />
            1991.04.10<br />
            +82 10-6644-0155 <br />
            violet91410@gmail.com
          </p>
        </div>

        <!-- circles -->
        <div class="circles">
          <!--1st circle-->
          <div class="circle-area">
            <div class="motto" style="width: 100%">
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
            <div class="motto" style="width: 100%">
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
            <div class="motto" style="width: 100%">
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
                또한, 개발지식을 기억하고자 학습블로그를 기록하고 있습니다.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section
        class="portfolio"
        id="portfolio"
        style="background-color: #f3f3f3"
      >
        <div class="content">
          <h1
            style="
              font-size: 34px;
              letter-spacing: 6px;
              line-height: 1.2;
              padding-top: 120px;
            "
          >
            PORTFOLIO
          </h1>
          <hr />
          <div class="portfolio-list" style="display: flex; margin-top: 120px">
            <div
              class="each"
              style="
                width: 1200px;
                height: 100%;
                background-color: white;
                padding: 10px;
                text-align: left;
              "
            >
              <div style="display: flex">
                <div class="text-area">
                  <h2>01</h2>
                  <p>별별귤팜</p>
                  <p>서비스 출시</p>
                  <div class="overview">
                    <div class="flex-align-center">
                      <img
                        style="width: 3%"
                        src="static/img/ico_menu_.png"
                      /><span class="description">Overview</span>
                    </div>
                    <p style="margin: 15px 0; width: 500px">
                      제주도 산 귤, 제주도 현지농장을 소개하고 판매하는
                      플랫폼입니다.
                    </p>
                  </div>
                  <div class="stack">
                    <div class="flex-align-center">
                      <img style="width: 3%" src="static/img/ico_stack_.png" />
                      <span class="description">Stack</span>
                    </div>
                    <div style="margin-top: 10px">
                      <span class="radius">Vue</span>
                      <span class="radius">Rest API</span>
                    </div>
                  </div>
                  <div class="link">
                    <div class="flex-align-center">
                      <img style="width: 3%" src="static/img/ico_link_.png" />
                      <span class="description">Link</span>
                    </div>
                    <div style="margin-top: 10px">
                      <span class="radius">Service</span>
                      <span class="radius">Github</span>
                    </div>
                  </div>
                </div>
                <div class="img-area">
                  <img style="width: 90%" src="static/img/bbgf.png" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- contact -->
      <section class="portfolio" id="contact" style="background-color: #f3f3f3">
        <div class="content">
          <h1 style="font-size: 34px; letter-spacing: 6px; line-height: 1.2">
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
.about-me, .content {
  width: 900px;
  margin: 0 auto;
}

/* 내정보 */
.info {
  color: #a4a4a4;
  margin: 40px auto;
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
  font-weight: lighter;
  width: 300px;
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
  color: #a4a4a4;
  line-height: 24px;
  letter-spacing: 0;
  font-weight: 300;
}
.description {
  margin: 10px 0;
  font-size: 20px;
  font-weight: bold;
  letter-spacing: -0.2px;
  margin-left: 10px;
  color: #2c3e50;
}

.radius {
  padding: 5px 10px;
  border-radius: 10px;
  background-color: lightgray;
  color: #2c3e50;
}

/* 미디어쿼리 -> 반응형 */
@media (min-width: 768px) and (max-width: 2000px) {
  #logo {
    /*display: flex;*/
    width: 300px;
    margin: 0 auto;
  }
  .menu-list {
    width: 500px;
  }
  .circles {
    display: flex;
  }
}

@media (min-width: 580px) and (max-width: 768px) {
  #logo {
    /*display: flex;*/
    width: 200px;
    margin: 0 auto;
  }
  .circles {
    display: flex;
  }
}
@media (min-width: 320px) and (max-width: 579px) {
  .menu {
    background-color: blueviolet;
    width: 100%;
    height: 60px;
  }
  #logo,
  .menu-list {
    display: none !important;
  }
  .circle-area {
    width: 300px;
  }
}
</style>
