<template>
<div>
  <div>
    <section class="start-page">
      <img src="static/img/giraffe.jpg">
    </section>
    <section class="menu">
      <div style="display: flex;" class="menu-content">
        <div id="logo">YANG.JIEUN</div>
        <div class="menu-list">
          <div>HOME</div>
          <div>ABOUT ME</div>
          <div>PORTFOLIO</div>
          <div>BLOG</div>
        </div>
      </div>
    </section>

    <!--about me-->
    <section class="about-me">
      <div class="content">
        <h1 style="
        font-size: 34px;
        letter-spacing: 6px;
        line-height: 1.2;">ABOUT ME</h1>
        <p class="info">양지은 <br>
          1991.04.10<br>
          (Mobile) 010-6644-0155 <br>
          violet91410@gmail.com</p>
      </div>

      <!-- circles -->
      <div class="circles" style="margin-top: 30px">
      <!--1st circle-->
        <div class="circle-area">
          <div class="motto" style="width: 100%; ">
            <div class="circle"
            ><img style="width: 90%" src="static/img/dog.png"> </div>
            <h2>MOTTO</h2>
            <p class="pen"> 이 세상에 불가능한 일은 없다고 생각하고 있습니다. 책임감과 열정으로 맡은 일은 꼭 자신있게 해내고자 합니다. 정체되어 있지않고 더 발전하기 위해 항상 노력하고자 합니다.</p>
          </div>
        </div>
      <!-- 2nd circle-->
          <div class="circle-area">
            <div class="motto" style="width: 100%; ">
              <div class="circle"
              ><img style="width: 90%" src="static/img/dog.png"> </div>
              <h2>MOTTO</h2>
              <p class="pen"> 이 세상에 불가능한 일은 없다고 생각하고 있습니다. 책임감과 열정으로 맡은 일은 꼭 자신있게 해내고자 합니다. 정체되어 있지않고 더 발전하기 위해 항상 노력하고자 합니다.</p>
            </div>
          </div>
      <!-- 3nd circle-->
        <div class="circle-area">
          <div class="motto" style="width: 100%; ">
            <div class="circle"
            ><img style="width: 90%" src="static/img/dog.png"> </div>
            <h2>MOTTO</h2>
            <p class="pen"> 이 세상에 불가능한 일은 없다고 생각하고 있습니다. 책임감과 열정으로 맡은 일은 꼭 자신있게 해내고자 합니다. 정체되어 있지않고 더 발전하기 위해 항상 노력하고자 합니다.</p>
          </div>
        </div>
      </div>

    </section>
    <section>home</section>
<!--  <div>home영역</div>-->
<!--  <div>about me</div>-->
<!--  <div>포트폴리오</div>-->
<!--  <div>블로그</div>-->
  </div>
</div>
</template>

<script>
export default {
  name: "Index"
}
</script>

<style scoped>
.start-page {
  width: 100%;
  /*background: url("./static/img/giraffe.jpg") fixed no-repeat;*/
}

.menu-content {
  display: flex;
  width: 900px;
  margin: 0 auto;
}
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
@media (min-width: 320px) and (max-width : 579px) {
  .menu {
   background-color: blueviolet;
    width: 100%;
    height: 60px;
  }
  #logo, .menu-list {
    display: none !important;
  }
  .circle-area {
    width: 300px;
  }

}

.menu {
  width: 100%;
  height: 60px;
  background-color: #ffffff;
  border-bottom: 1px solid #f2f2f2;
}

#logo {
  width: 300px;
  text-align: left;
}
.menu-list {
  display: flex;
}

.menu-list>div{
  margin: 0 20px;
}

.about-me, .content {
  width: 900px;
  margin: 0 auto;
}

.info{
  color: #a4a4a4;
  margin: 40px auto;
  width: 300px;
  line-height: 25px;
  letter-spacing: 1px;
  font-size: 14px;
  font-weight: 300;
  text-align: center;
}

.circle-area{
  width: 300px;
}

.circle {
  width: 120px;
  height: 120px;
  border: 3px solid #f0f0f0;
  border-radius: 70px
}

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

</style>
