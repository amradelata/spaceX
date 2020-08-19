<template>
  <div>
    <div class="blackbody">
      <div class="firstsection myhero">
        <img src="~/assets/img/heros/starship.webp" class="heroimg" />
        <div class="title">
          SERVICE TO EARTH ORBIT, THE
          MOON, MARS AND BEYOND
        </div>
      </div>
      <div class="container"></div>
    </div>
    <div class="myvideo">
      <!-- <video loop muted autoplay playsinline>
        <source
          src="https://www.spacex.com/sites/spacex/files/01_starshipspinvertwide_2mbs_1.mp4"
          type="video/mp4"
        />
      </video>-->

      <img src="~/assets/img/ships/Starship-GIF.gif" style="height: 100%; width: 100%" />

      <div class="myvideocontent">
        <div class="row second">
          <div class="col-sm">
            <h2 class="suptitle">STARSHIP</h2>
            <div class="pragraph">
              STARSHIP delivers payloads to space aboard the Dragon spacecraft or inside a composite fairing.
              DRAGON SPACECRAFT
              <br />
              <br />
              <br />Dragon carries cargo in the spacecraft’s pressurized capsule and unpressurized trunk, which can also accommodate secondary payloads. In the future, Dragon will carry astronauts in the pressurized capsule as well.
              LEARN MORE ABOUT DRAGON
              COMPOSITE FAIRING
              <br />
              <br />
              <br />The payload fairing is for the delivery of satellites to destinations in low Earth orbit (LEO), geosynchronous transfer orbit (GTO) and beyond.
              SEE COMPOSITE FAIRING ON STARSHIP
            </div>
            <!--  -->
            <h2 class="suptitle">INTERSTAGE</h2>
            <div
              class="pragraph"
            >The interstage is a composite structure that connects the first and second stages and holds the release and separation system. STARSHIP uses an all-pneumatic stage separation system for low-shock, highly reliable separation that can be tested on the ground, unlike pyrotechnic systems used on most launch vehicles.</div>

            <!--  -->
          </div>
        </div>
      </div>
    </div>
    <div class="youtyop">
      <iframe
        width="100%"
        height="819"
        src="https://www.youtube.com/embed/wzFQJUzoUvM"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>
    <!-- <div class="rAPTORENGINe">
      <img src="https://www.spacex.com/sites/spacex/files/raptor_0.jpg" alt />
      <div class="rAPTORENGINecontent">
        <h2>RAPTOR ENGINE</h2>
        <p>Raptor is a full-flow, staged combustion rocket engine powered by cryogenic methane and liquid oxygen (LOX), rather than the RP-1 kerosene and LOX used in SpaceX’s prior Merlin engine family. The Super Heavy booster is powered by 37 Raptors, while Starship is powered by 6.</p>
      </div>
    </div>-->
    <!--  -->
    <div class="ournwesblack">
      <h5 class="ournews">SPACEX DESIGNS, MANUFACTURES AND LAUNCHES ADVANCED ROCKETS AND SPACECRAFT</h5>
      <div class="container">
        <div class="cards row">
          <div class="card col-sm col-md" style="width: 18rem;">
            <img src="~/assets/img/news/NHQ.jpg" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p
                class="card-text"
              >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
          <div class="card col-sm col-md" style="width: 18rem;">
            <img src="~/assets/img/news/prototype.jpg" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p
                class="card-text"
              >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
          <div class="card col-sm col-md" style="width: 18rem;">
            <img src="~/assets/img/news/NHQ.jpg" class="card-img-top" />
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p
                class="card-text"
              >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import ourNews from '~/components/ourNews.vue'

export default {
  components: {
    ourNews
  }
}
</script>
<style  scoped>
.mOSTPOWERFULROCKEt {
  text-align: center;
}
.mOSTPOWERFULROCKEt h3 {
  border-bottom: 1px dashed #000;
  padding-bottom: 20px;
}
.blackbody {
  background-color: #000;
  color: #f8f8f8;
}
.firstsection {
  position: relative;
  height: 70vh;
  background-size: cover;
  background-position: top center;
}

.title {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 30%;
  margin: 0;
  font-weight: 100;
  line-height: 1;
  margin-top: 0;
  font-size: 50px;
  color: white;
  letter-spacing: -1px;
}
.pragraph {
  margin-bottom: 100px;
}
.pageName {
  font-weight: 500;
  line-height: 1;
  margin-top: 0;
  font-size: 50px;
  border-bottom: 1px dashed #f8f8f8;
  padding-bottom: 35px;
  padding-top: 35px;
  margin-bottom: 35px;
}
.smallrockit img {
  width: 50px;
  position: absolute;
  top: 0;
  left: 40px;
}
.manmune {
  position: relative;
}

.manmune ul {
  margin-top: 50px;
  width: 100%;
}
.manmune ul li {
  list-style: none;
  padding: 13px 20px;
  display: block;
  border-radius: 2px;
  background: #21272b;
  color: #cccccc;
  padding-left: 85px;
  margin: 5px 0;
}
.manmune ul li ::after {
  content: '→';
  position: absolute;
  top: 0;
  left: 100%;
  padding-left: 6px;
  color: aliceblue;
}

.second {
  margin: 200px 0;
}

.suptitle {
  font-weight: 500;
  line-height: 1;
  font-size: 35px;
  padding-bottom: 35px;
}
.pigrocket {
  position: relative;
}
.pigrocket .img {
  display: flex;
  justify-content: space-around;
}
.pigrocket .img img {
  width: 350px;
}

.taple {
  display: inline-block;
}
.rightimgs {
  display: inline-block;
}
.rightimgs > div {
  display: inline-block;
  margin-right: 50px;
  margin-bottom: 200px;
}
.rightimgs > div span {
  display: block;
  display: flex;
  justify-content: space-around;
}
.rightimgs > div h4 {
  border-bottom: 1px solid #fff;
  padding-bottom: 10px;
}
.rightimgs > div h5 {
  font-weight: 300;
  line-height: 40px !important;
  font-size: 35px;
  text-align: center;
}
.rightimgs img {
  width: 100px;
  margin-bottom: 35px;
}
.engan {
  width: 300px !important;
}
.myvideo {
  position: relative;
}
.myvideo video {
  width: 100%;
  /* height: 100vh; */
}
.myvideocontent {
  position: absolute;
  top: 0;
  left: 10%;
  color: #fff;
  width: 30%;
}
.youtyop {
  margin-bottom: -10px;
}
.rAPTORENGINe {
  position: relative;
  margin-top: -10px;
}
.rAPTORENGINe img {
  width: 100%;
}
.rAPTORENGINecontent {
  position: absolute;
  top: 20%;
  left: 10%;
  color: #fff;
  width: 30%;
}
.ournwesblack {
  background: #000;
  color: #fff;
  padding: 100px 0;
}
.ournwesblack .card {
  background: #000;
  color: #fff;
}
.ournwesblack .ournews {
  text-align: center;
  padding: 50px 0;
}
.heroimg {
  width: 100%;
}
.myhero {
  margin-bottom: 180px;
}

@media screen and (max-width: 768px) {
  .myhero {
    margin-bottom: -5px;
  }
  .title {
    width: 100%;
  }
  .rightimgs {
    display: none;
  }
  .myvideocontent,
  .rAPTORENGINecontent {
    position: initial;
    color: #000;
    width: 100%;
    /* top: -20%; */
    left: 10%;
    text-align: center;
    padding: 50px 35px;
  }
  .card {
    margin: 10px auto;
  }
  .heroimg {
    width: 100%;
    height: 60vh;
  }
}
</style>