

<template>
  <div class="main-container">
    <div class="container">
      <span>
        <img class="img-sec" src="../assets/logo.png" alt="facebook" width="40px" height="35px" style="cursor: pointer;">
      </span>
      <span> <a href="https://acharyaprashant.org/" target="_blank">Home</a></span>
      <span class="down-arrow">
        <span class="live-session">Live Sessions</span>
        <img class="img-sec" src="../assets/inverted-arrow.png" alt="facebook" width="15px" height="15px"
          style="cursor: pointer;">
      </span>
      <span>Video Series</span>
      <span> <a href="https://acharyaprashant.org/en/books" target="_blank">AP books</a> </span>
      <span> <a href="https://acharyaprashant.org/en/articles" target="_blank">AP articles</a> </span>
      <span class="down-arrow">
        <span class="live-session">Invite</span>
        <img class="img-sec" src="../assets/inverted-arrow.png" alt="facebook" width="15px" height="15px"
          style="cursor: pointer;">
      </span>
      <span> <a href="https://acharyaprashant.org/en/media" target="_blank" >In Media</a> </span>
      <span> <a href="https://acharyaprashant.org/en/contribute" target="_blank" >Donate</a> </span>
    </div>
    <div class="right-container">
      <img src="../assets/right-header.png" alt="contact" style="cursor: pointer;">
    </div>
  </div>
  <div class="second-container">
    <div class="access-text">Get access to all 350+ video series at once!</div>
    <div class="access-btn"><a
        href="https://acharyaprashant.org/en/login?page=https%3A%2F%2Facharyaprashant.org%2Fen%2Fpacks%2Fall-video-series"
        target="_blank">Click Here</a></div>
  </div>
</template>

<style scoped>
.main-container {
  height: 7.3vh;
  display: flex;
  justify-content: space-between;
  background-color: #d24115;
}

.container {
  align-items: center;
  width: 57%;
  display: flex;
  justify-content: space-around;
  color: rgb(233, 228, 228);
}

span , a {
  font-weight: 600;
  font-size: 15px;
  cursor: pointer;
}

.down-arrow {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.img-sec {
  margin-top: 6px;
}

.second-container {
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  background-color: black;
  height: 8vh;
}

.access-text {
  font-size: 20px;
  margin: 10px;
}

.access-btn {
  font-size: 15px;
  padding: 0 10px;
  border: 1px solid white;
  border-radius: 8px;
  margin: 10px;
}

.access-btn:hover {
  color: white;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
