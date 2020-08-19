<template>
  <div>
    <div class="blackbody">
      <div class="firstsection myhero">
        <img src="~/assets/img/heros/splashdown_1.webp" class="heroimg" />
        <div class="title">
          ALL THIS DATA FROM
          SPACEX API
        </div>
      </div>
      <div class="ournwesblack">
        <h5
          class="ournews"
        >SPACEX DESIGNS, MANUFACTURES AND LAUNCHES ADVANCED ROCKETS AND SPACECRAFT</h5>
        <div class="container">
          <div class="cards row">
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">details</h5>
                <hr />
                <p class="card-text">{{spacexdata.details}}</p>
              </div>
            </div>
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">flight number</h5>
                <hr />
                <p class="card-text">{{spacexdata.flight_number}}</p>
              </div>
            </div>
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">last_date_update</h5>
                <hr />
                <p class="card-text">{{spacexdata.last_date_update}}</p>
              </div>
            </div>
          </div>
          <div class="cards row">
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">launch year</h5>
                <hr />
                <p class="card-text">{{spacexdata.launch_year}}</p>
              </div>
            </div>
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">mission_name</h5>
                <hr />
                <p class="card-text">{{spacexdata.mission_name}}</p>
              </div>
            </div>
            <div class="card col-sm col-md" style="width: 18rem;">
              <div class="card-body">
                <h5 class="card-title">launchsuccess</h5>
                <hr />
                <p class="card-text">{{spacexdata.launch_success}}</p>
              </div>
            </div>
          </div>

          <!--  -->
        </div>
      </div>
    </div>
  </div>
</template>
      
<script>
import axios from 'axios'
const API = 'https://api.spacexdata.com/v3/launches/latest?pretty=true'
export default {
  data() {
    return {
      spacexdata: []
    }
  },
  async created() {
    const res = await axios.get(API)
    this.spacexdata = res.data
    console.log(this.spacexdata)
  }
}
</script>


<style  scoped>
.blackbody {
  background-color: #000;
  color: #f8f8f8;
}
.firstsection {
  position: relative;

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
.ournwesblack {
  background: #000;
  color: #fff;
  padding: 100px 0;
  margin-top: 150px;
}
hr {
  background: #ccc;
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

@media screen and (max-width: 768px) {
  .title {
    width: 100%;
  }
}
</style>