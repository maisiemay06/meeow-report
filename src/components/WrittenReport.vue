<template>
  <div class="card">
      <p class="time">2 mins process</p>
        <img src="../assets/written-icon.png" alt="">
        <h2>post a written report to Linkedin</h2>
        <p>All you need to do is write a title and a brief description of the conversation, then tag your fellow Meeowists in the post. Easy!</p>
        <button>write a report now - it's easy</button>
        <div class="icons">
        <i class="fa-brands fa-linkedin"></i>
        </div>
  </div>
</template>

<script>
export default {
  name: 'WrittenReport',
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
    width: 254px;
    margin: auto;
    font-weight: 600;
    font-size: 1.75rem;
    margin-top: 28px;
}
p {
    width: 349px;
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
    width: 266px;
    height: 50px;
    font-size: 1rem;
    font-weight: 600;
    margin-top: 29px;
}

.icons {
    color: #EEEEEE;
    font-size: 1.5rem;
    margin-top: 29px;
}
</style>
