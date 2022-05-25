<template>
  <div class="card">
    <p class="time">3 mins process</p>
        <img src="../assets/video-icon.png" alt="">
        <h2>give your new connections
a video ShoutOut</h2>
        <p>We’ll walk you through a few short steps to create a video testimonial and post it to your preferred social channel.</p>
        <button>record a ShoutOut video now <i class="fa-solid fa-arrow-up-right-from-square"></i></button>
        <div class="icons">
        <i class="fa-brands fa-linkedin"></i>
        <i class="fa-brands fa-facebook-square"></i>
        <i class="fa-brands fa-twitter-square"></i>
        <i class="fa-brands fa-instagram"></i>
        </div>
  </div>
</template>

<script>
export default {
  name: 'VideoReport',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.time {
    background-color: #2EDCDC;
    width: 122px;
    height: 24px;
    margin: auto;
    font-size: 0.875rem;
    font-weight: 600;
}
img {
    margin-top: 33px;
}
h2 {
    width: 326px;
    margin: auto;
    font-weight: 600;
    font-size: 1.75rem;
    margin-top: 35px;
}
p {
    width: 332px;
    margin: auto;
    font-weight: 400;
    font-size: 1rem;
    margin-top: 23px;
}
button {
    background-color: #3C47F1;
    color: #fff;
    border: none;
    border-radius: 25px;
    width: 298px;
    height: 50px;
    font-size: 1rem;
    font-weight: 600;
    margin-top: 32px;
    transition: 0.1s ease-in;
}
button:hover {
    background-color: #182AC6;
    cursor: pointer;
}
.fa-arrow-up-right-from-square {
    margin-left: 10px;
}
.icons {
    color: #EEEEEE;
    font-size: 1.5rem;
    width: 120px;
    margin: auto;
    margin-top: 36px;
    display: flex;
    justify-content: space-between;
}

</style>
