<template>
  <div class="hello">
    <div class="mini-profile">
      <div class="row">
        <div class="col-md-4">
            <img src="../assets/alexandru-zdrobau-195418.jpg" alt="Vue.js PWA" class="img-responsive" style="margin-top: 10px">
        </div>
        <div class="col-md-6">
          <h2>
            Jane Doe
            <br>
            <small class="text-muted">Gem Sorceress</small>
            <br>
          </h2>
          <br>
          <br>
          <h2>Progress</h2>
          Meditation
          <div class="progress">
            <div class="progress-bar bg-awareness" role="progressbar" style="width: 25%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          Yoga
          <div class="progress">
            <div class="progress-bar bg-info" role="progressbar" style="width: 50%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          Prana
          <div class="progress">
            <div class="progress-bar bg-yoga" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          Awareness
          <div class="progress">
            <div class="progress-bar bg-meditation" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
        </div>
      </div>
      <br>
      <h2>Exercises</h2>
      <br>
      <div class="row container">
        <div class="col-md-3">
          <div class="card text-white bg-charcoal mb-3" style="max-width: 20rem;">
            <div class="card-header">Mindfulness</div>
            <div class="card-body">
              <h4 class="card-title">Chapter 1</h4>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card text-white bg-black mb-3" style="max-width: 20rem;">
            <div class="card-header">Meditation</div>
            <div class="card-body">
              <h4 class="card-title">Chapter 2</h4>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card text-white bg-gold mb-3" style="max-width: 20rem;">
            <div class="card-header">Yoga</div>
            <div class="card-body">
              <h4 class="card-title">chapter 3</h4>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
        <div class="col-md-3">
          <div class="card bg-offwhite mb-3" style="max-width: 20rem;">
            <div class="card-header">Explore</div>
            <div class="card-body">
              <h4 class="card-title">Chapter 4</h4>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js PWA'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.row{
  display: flex;
  align-items: center;
}
.card{
  border-radius: 50%;
  width: auto;
  height: 350px;
}
.col{
  margin: 10px;
}
.container {
  margin: auto;
}
.bg-meditation {
  background-color:#F7B32B; 
}
.bg-yoga {
  background-color: #AE9062;
}
.bg-awareness {
  background-color: #A9E5BB;
}
.bg-charcoal{
  background-color: #4D4D4D
}
.bg-black{
  background-color: #292C31
}
.bg-gold{
  background-color: #AE9062
}
.bg-offwhite{
  background-color: #F7F7F7
}
.bg-cream{
  background-color: #E7D5B4
}
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}

img {
  border-radius: 50%;
  width: 350px;
  height: 350px;
  
}
</style>
