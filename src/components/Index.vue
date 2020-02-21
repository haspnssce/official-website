<template>
  <div id="Index" class="Index">
    <div class="index-wrapper">
      <div class="title-text">
          <img class="title-text-logo" src="@/assets/img/title-logo.png" alt="title-logo">
          <h1 class="title-text-text">Hacker Space NSSCE</h1>
          <a href="/about" class="title-text-btn">Know More</a>
      </div>
      <div class="title-image">
        <img class="title-image-image" src="@/assets/img/title-image.png" alt="title-image">
      </div>
    </div>
    <div class="motto">
        <div>
          Hack for life.
          <br>
          Hack for change.
          <br>
          Hack for better future.
          <br>
          <br>
          <br>
          <big>Let the coding culture prosper......</big>
        </div>
        <a href="/join" class="join-now">Join Now</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Index'
}
</script>

<style>
#Index {
  font-family: 'Roboto', sans-serif;
  background: #1c2036;
}
.index-wrapper {
  display: flex;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  -ms-box-sizing: border-box;
}
.title-text {
  width: 50%;
  height: 100vh;
  padding: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.title-text-text {
  color: #507AE8;
  text-transform: capitalize;
  font-size: 3rem;
  font-weight: 500;
}

.title-text-btn {
  text-align: center;
  text-decoration: none;
  color: #507AE8;
  font-size: 2rem;
  font-weight: 400;
  padding: 1rem;
  border-radius: 5rem;
  width: 20rem;
  border: 4px solid #507AE8;
  transition: all 0.3s;
}
.title-text-btn:hover {
  color: #ffffff;
  background: #507AE8;
}

.title-text-logo {
  height: 9rem;
}

.title-image {
  display: flex;
  flex-direction: column;
  width: 50%;
  padding: 3rem;
  justify-content: center;
  align-items: center;
}

.title-image-image {
  width: 80%;
}

.motto {
  max-width: 100%;
  font-size: 3rem;
  margin: 0;
  height: 70vh;
  padding-bottom: 5rem;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  color: #507AE8;
}

.join-now {
  text-align: center;
  text-decoration: none;
  color: #ffffff;
  background: #507AE8;
  font-size: 2rem;
  font-weight: 400;
  padding: 1rem;
  border-radius: 5rem;
  width: 300px  ;
  border: 4px solid #507AE8;
  transition: all 0.3s;
}

.join-now:hover {
  color: #507AE8;
  background: #1c2036;
}
</style>
