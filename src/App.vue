<template>
<h1>tell the world about the brilliant people you just met!</h1>
<p>A Meeow Report gives everyone exposure and helps build your visibility.</p>
  <div class="reports">
  <WrittenReport />
<h1>OR</h1>
  <VideoReport />
  </div>
  <div class="footer">
  <a href="">Return to calendar</a>
  </div>
</template>

<script>
import WrittenReport from './components/WrittenReport.vue'
import VideoReport from './components/VideoReport.vue'

export default {
  name: 'App',
  components: {
    WrittenReport,
    VideoReport,
  }
}
</script>

<style>
body {
  background-color: #3C47F1;
}
#app {
  font-family: sofia-pro, sans-serif;
  font-weight: 400;
  font-style: normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
  font-size: 16px;
  letter-spacing: -0.8px;

}
h1 {
font-size: 2.5rem;
font-weight: 600;
}
p {
  font-size: 1rem;
  margin-top: 36px;
}
.reports {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  margin-top: 53px;
}
.footer {
  margin-top: 43px;
}
a {
  font-size: 0.875rem;
  color: #fff;
  font-weight: 500;
}
.card {
    background-color: #fff;
    width: 490px;
    height: 500px;
    border-radius: 8px;
    color: #3C47F1;
}
@media only screen and (max-width: 1400px) {
  .card {
    width: 40%;
  }
}

</style>
