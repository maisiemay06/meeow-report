<template>
<h1>tell the world about the brilliant people you just met!</h1>
<p>A Meeow Report gives everyone exposure and helps build your visibility.</p>
  <div class="reports">
  <WrittenReport />
<h1>OR</h1>
  <VideoReport />
  </div>
  <a href="">Return to calendar</a>
</template>

<script>
import WrittenReport from './components/WrittenReport.vue'
import VideoReport from './components/VideoReport.vue'

export default {
  name: 'App',
  components: {
    WrittenReport,
    VideoReport
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
}
a {
  font-size: 0.875rem;
  color: #fff;
  font-weight: 500;
}

</style>
