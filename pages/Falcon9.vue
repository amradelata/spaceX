<template>
  <div class="blackbody">
    <div
      class="firstsection"
      style=" background-image: url('https://www.spacex.com/sites/all/themes/spacex2012/images/falcon9/header___falcon%209.jpg');"
    >
      <div class="title">
        FALCON 9 & DRAGON TO
        RETURN ASTRONAUTS
        TO SPACE
      </div>
    </div>
    <div class="container">
      <h2 class="pageName">FALCON 9</h2>

      <div class="row">
        <div class="col-sm">
          Falcon 9 is a two-stage rocket designed and manufactured by SpaceX for the reliable and safe transport of satellites and the Dragon spacecraft into orbit. Falcon 9 is the first orbital class rocket capable of reflight. SpaceX believes rocket reusability is the key breakthrough needed to reduce the cost of access to space and enable people to live on other planets.
          <br />

          <br />Falcon 9 was designed from the ground up for maximum reliability. Falcon 9’s simple two-stage configuration minimizes the number of separation events -- and with nine first-stage engines, it can safely complete its mission even in the event of an engine shutdown.
        </div>
        <div
          class="col-sm"
        >Falcon 9 made history in 2012 when it delivered Dragon into the correct orbit for rendezvous with the International Space Station, making SpaceX the first commercial company ever to visit the station. Since then Falcon 9 has made numerous trips to space, delivering satellites to orbit as well as delivering and returning cargo from the space station for NASA. Falcon 9, along with the Dragon spacecraft, was designed from the outset to deliver humans into space and under an agreement with NASA, SpaceX is actively working toward this goal.</div>
        <div class="col-sm manmune">
          <div class="smallrockit">
            <img
              src="https://www.spacex.com/sites/all/themes/spacex2012/images/falcon9/falcon9-render_same_size_file.png"
            />
          </div>

          <ul>
            <li>Falcon 9</li>
            <li>Launch Manifest</li>
            <li>Launch Manifest</li>
          </ul>
        </div>
      </div>
      <!--  -->

      <div class="row second">
        <div class="col-sm">
          <h2 class="suptitle">PAYLOAD</h2>
          <div class="pragraph">
            Falcon 9 delivers payloads to space aboard the Dragon spacecraft or inside a composite fairing.
            DRAGON SPACECRAFT
            <br />
            <br />
            <br />Dragon carries cargo in the spacecraft’s pressurized capsule and unpressurized trunk, which can also accommodate secondary payloads. In the future, Dragon will carry astronauts in the pressurized capsule as well.
            LEARN MORE ABOUT DRAGON
            COMPOSITE FAIRING
            <br />
            <br />
            <br />The payload fairing is for the delivery of satellites to destinations in low Earth orbit (LEO), geosynchronous transfer orbit (GTO) and beyond.
            SEE COMPOSITE FAIRING ON FALCON HEAVY
          </div>
          <!--  -->
          <h2 class="suptitle">INTERSTAGE</h2>
          <div
            class="pragraph"
          >The interstage is a composite structure that connects the first and second stages and holds the release and separation system. Falcon 9 uses an all-pneumatic stage separation system for low-shock, highly reliable separation that can be tested on the ground, unlike pyrotechnic systems used on most launch vehicles.</div>
          <!--  -->
          <h2 class="suptitle">FIRST STAGE</h2>
          <div
            class="pragraph"
          >Falcon 9’s first stage incorporates nine Merlin engines and aluminum-lithium alloy tanks containing liquid oxygen and rocket-grade kerosene (RP-1) propellant. After ignition, a hold-before-release system ensures that all engines are verified for full-thrust performance before the rocket is released for flight. Then, with thrust greater than five 747s at full power, the Merlin engines launch the rocket to space. Unlike airplanes, a rocket's thrust actually increases with altitude; Falcon 9 generates more than 1.7 million pounds of thrust at sea level but gets up to over 1.8 million pounds of thrust in the vacuum of space. The first stage engines are gradually throttled near the end of first-stage flight to limit launch vehicle acceleration as the rocket’s mass decreases with the burning of fuel.</div>
          <!--  -->
          <div
            class="pragraph"
          >The interstage is a composite structure that connects the first and second stages and holds the release and separation system. Falcon 9 uses an all-pneumatic stage separation system for low-shock, highly reliable separation that can be tested on the ground, unlike pyrotechnic systems used on most launch vehicles.</div>
          <!--  -->
          <h2 class="suptitle">FIRST STAGE</h2>
          <div class="pragraph">
            <div class="taple">
              <dl>
                <dt class="stat">Engines</dt>
                <dd class="number number-large">9</dd>
              </dl>
              <dl>
                <dt class="stat">BURN TIME</dt>
                <dd class="number number-large">162sec</dd>
              </dl>BURN TIME
            </div>
            <img
              src="https://www.spacex.com/sites/spacex/files/images/falcon9/falcon9-merlin-engines-solo.png"
            />
          </div>
          <!--  -->
        </div>
        <div class="col-sm pigrocket">
          <div class="img">
            <img
              src="https://www.spacex.com/sites/all/themes/spacex2012/images/falcon9/falcon9-render_same_size_file.png"
            />
          </div>
        </div>

        <div
          class="col-sm"
          style="color: red"
        >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Omnis voluptatum deserunt nam, eligendi at quibusdam magnam, autem odio ipsum eos earum rem sit, quia soluta. Molestiae incidunt dolorem repellendus est.</div>
      </div>
    </div>
  </div>
</template>

<style  scoped>
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
  width: 30px;
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
  width: 166px;
}

.taple {
  display: inline-block;
}

@media screen and (max-width: 768px) {
  .title {
    width: 100%;
  }
}
</style>