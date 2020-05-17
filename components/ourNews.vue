<template>
  <div>
    <h5 class="ournews">SPACEX DESIGNS, MANUFACTURES AND LAUNCHES ADVANCED ROCKETS AND SPACECRAFT</h5>
    <div class="container">
      <div class="cards row">
        <div class="card col-sm col-md" style="width: 18rem;">
          <img
            src="https://www.spacex.com/sites/spacex/files/home_block_reusable.jpg"
            class="card-img-top"
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#">Go somewhere</a>
          </div>
        </div>
        <div class="card col-sm col-md" style="width: 18rem;">
          <img
            src="https://www.spacex.com/sites/spacex/files/rideshare256x116.jpg"
            class="card-img-top"
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#">Go somewhere</a>
          </div>
        </div>
        <div class="card col-sm col-md" style="width: 18rem;">
          <img
            src="https://www.spacex.com/sites/spacex/files/multiplanetary_thumbnail.jpg"
            class="card-img-top"
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style  scoped>
.cards {
  margin: 100px auto;
}
.card {
  margin: 10px;
}

.ournews {
  text-align: center;
  margin: 35px 0;
}
@media screen and (max-width: 768px) {
  .card {
    margin: 10px auto;
  }
}
</style>