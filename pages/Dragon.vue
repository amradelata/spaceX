<template>
  <div>
    <div class="blackbody">
      <div class="firstsection" style="  margin-bottom: 100px">
        <img src="~/assets/img/heros/dragon_feature.webp" style="width: 100%" />
        <div class="title">
          FIRST PRIVATE SPACECRAFT TO
          THE SPACE STATION
        </div>
      </div>
      <div class="container">
        <h2 class="pageName">DRAGON</h2>

        <div class="row">
          <div class="col-sm">
            DRAGON is a two-stage rocket designed and manufactured by SpaceX for the reliable and safe transport of satellites and the Dragon spacecraft into orbit. DRAGON is the first orbital class rocket capable of reflight. SpaceX believes rocket reusability is the key breakthrough needed to reduce the cost of access to space and enable people to live on other planets.
            <br />

            <br />DRAGON was designed from the ground up for maximum reliability. DRAGON’s simple two-stage configuration minimizes the number of separation events -- and with nine first-stage engines, it can safely complete its mission even in the event of an engine shutdown.
          </div>
          <div
            class="col-sm"
          >DRAGON made history in 2012 when it delivered Dragon into the correct orbit for rendezvous with the International Space Station, making SpaceX the first commercial company ever to visit the station. Since then DRAGON has made numerous trips to space, delivering satellites to orbit as well as delivering and returning cargo from the space station for NASA. DRAGON, along with the Dragon spacecraft, was designed from the outset to deliver humans into space and under an agreement with NASA, SpaceX is actively working toward this goal.</div>
        </div>
        <!--  -->
        <div class="row firstrow">
          <div class="col-sm rightimgs">
            <div>
              <h4>BURN TIME</h4>
              <h5>397sec</h5>
            </div>
            <div>
              <h4>THRUST</h4>
              <h5>934kN210,000 lbf</h5>
            </div>
            <div>
              <h4>BURN TIME</h4>
              <h5>397sec</h5>
            </div>
            <div>
              <h4>THRUST</h4>
              <h5>934kN210,000 lbf</h5>
            </div>
          </div>
          <div class="col-sm">
            <!-- <video loop muted autoplay playsinline style="width: 100%">
              <source
                src="https://www.spacex.com/sites/spacex/files/spinningdragon_web4x3_text_callouts_v04_fix_1.mp4"
                type="video/mp4"
              />
            </video>-->
            <img class="dragonimg" src="~/assets/img/ships/DragonTrunk_Render_Desktop.webp" />
          </div>
        </div>
        <!--  -->
      </div>
    </div>
    <div class="youtuop">
      <iframe
        width="100%"
        height="819"
        src="https://www.youtube.com/embed/78ATfCaBn6E"
        frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>

    <div class="sut">
      <img src="https://www.spacex.com/sites/spacex/files/suit_not_compressedv2_1_0.jpg" alt />
      <div class="suttext">
        <h3>THE SUIT</h3>
        <p>Designed in-house by SpaceX, each custom-tailored suit is meant to provide a pressurized environment for all crew members aboard Dragon in atypical situations such as cabin depressurization. This suit also routes communications and cooling systems to the astronauts aboard during regular flight. Additional features include the following:</p>
        <p>▪ 3D printed space suit helmet</p>
        <p>▪ Touchscreen compatible gloves</p>
        <p>▪ Flame resistant outer layer</p>
        <p>▪ Hearing protection during ascent and reentry</p>
        <p>▪ Single connection point between the suit and vehicle</p>
        <p>▪ Heel sliders securing feet to footrest</p>
      </div>
    </div>

    <ourNews />
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
.sut {
  position: relative;
}
.sut .suttext {
  position: absolute;
  top: 0;
  color: #fff;
  width: 35%;
  top: 20%;
  left: 10%;
}
.sut img {
  width: 100%;
  margin: 0;
  padding: 0;
  margin-top: -10px;
}
.dragonimg {
  width: 100%;
  height: 50%;
}
.firstrow {
  margin-top: 100px;
}
@media screen and (max-width: 768px) {
  .dragonimg {
    width: 100%;
    height: 100%;
  }
  .title {
    width: 100%;
  }
  .rightimgs {
    display: none;
  }
  .sut .suttext {
    position: initial;
    color: #000;
    width: 100%;
    top: 20%;
    left: 10%;
    text-align: center;
    padding: 100px 35px;
  }
}
</style>