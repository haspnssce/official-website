<template>
  <div id="Navbar" class="Navbar">
    <div class="brand">
      <img src="@/assets/img/nav-logo.png" class="brand-image">
    </div>
    <nav class="menubar">
      <ul class="menu-wrapper">
        <li class="menu-items"><a href="/official-website">Home</a></li>
        <li class="menu-items"><a href="/official-website/about">About</a></li>
        <li class="menu-items"><a href="/official-website/gallery">Gallery</a></li>
        <li class="menu-items"><a href="/official-website/projects">Projects</a></li>
        <li class="menu-items"><a href="/official-website/achievements">Achievements</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
#Navbar {
  position: fixed;
  top:0;
  height: 6rem;
  font-family: 'Roboto', sans-serif;
  color: #507AE8;
  width: 100%;
  border-bottom: 3px solid #507AE8;
  background: #ffffff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #1c2036;
  overflow: hidden;
}

.brand {
  color: inherit;
  padding: 1.5rem;
  font-size: 3rem;
}

.brand-image {
  height: 3.5rem;
}

.menubar {
  padding: 0 1.5rem;
}

.menu-wrapper {
  list-style: none;
  display: flex;
}

.menu-items {
  font-size: 2rem;
  padding: 1rem 0;
}

.menu-items a {
  text-decoration: none;
  color: inherit;
  position: relative;
  padding: 0 1rem;
}
.menu-items a:hover::after {
  content: '';
  position: absolute;
  bottom: -0.5rem;
  left: 50%;
  width: 100%;
  transform: translateX(-50%);
  -moz-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  -webkit-transform: translateX(-50%);
  border-bottom: solid 2px #507AE8;
  animation: hovering 0.5s;
  -moz-animation: hovering 0.5s;
  -ms-animation: hovering 0.5s;
  -webkit-animation: hovering 0.5s;
}

@keyframes hovering {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

</style>
