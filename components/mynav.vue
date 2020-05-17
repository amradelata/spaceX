<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="/">
        <img src="https://www.spacex.com/sites/spacex/files/spacex_logo_white.png" />
      </a>
      <button
        @click="shownav()"
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent" ref="navbar-toggler">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a href="/Falcon9" class="nav-link">Falcon 9</a>
          </li>
          <li class="nav-item">
            <a href="/FalconHeavy" class="nav-link">Falcon Heavy</a>
          </li>
          <li class="nav-item">
            <a href="/Dragon" class="nav-link">Dragon</a>
          </li>
          <li class="nav-item">
            <a href="/Starship" class="nav-link">Starship</a>
          </li>
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a href="/lastMission" class="nav-link">last mission</a>
            </li>
            <li class="nav-item">
              <a href="/AboutSpaceX" class="nav-link">About SpaceX</a>
            </li>
            <li class="nav-item">
              <a href="/careers" class="nav-link">Careers</a>
            </li>
          </ul>
        </form>
      </div>
    </nav>
  </div>
</template>


<script>
export default {
  methods: {
    shownav() {
      this.$refs['navbar-toggler'].classList.toggle('collapse')
    }
  }
}
</script>

<style  scoped>
.right {
  position: absolute;
  right: 0 !;
}
</style>