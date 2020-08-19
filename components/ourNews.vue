<template>
  <div>
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
            <a href="#">Go somewhere</a>
          </div>
        </div>
        <div class="card col-sm col-md" style="width: 18rem;">
          <img src="~/assets/img/news/prototype.jpg" class="card-img-top" />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p
              class="card-text"
            >Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#">Go somewhere</a>
          </div>
        </div>
        <div class="card col-sm col-md" style="width: 18rem;">
          <img src="~/assets/img/news/NHQ.jpg" class="card-img-top" />
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
  padding: 0;
}

.ournews {
  text-align: center;
  margin: 35px 0;
}
.card-img-top {
  /* height: 250px; */
  /* width: 100%; */
}
@media screen and (max-width: 768px) {
  .card {
    margin: 10px auto;
  }
}
</style>