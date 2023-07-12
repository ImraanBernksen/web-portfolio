<template>
      <nav class="navbar navbar-expand-lg navbar navbar-light static-top">
        <div class="container-fluid">
          <a href="#landing"><img class="logo" src="https://i.postimg.cc/L40McznY/logo.png" alt="logo"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse text-center" id="navbarSupportedContent">
            <ul class="navbar-nav mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" href="#landing">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#resume">Resume</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#techskills">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link"  href="#project">Project</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#testimonials">Testimonials</a>
              </li>
              <li class="nav-item">
                <a class="nav-link"  href="#contact">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

.navbar-collapse {
  justify-content: center;
  align-items: center;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin: 0 10px;
  padding: 0 5px;
}

.logo {
  width: 2em;
  border-radius: 50%;
}

nav {
  background-color: #00FFA2;
  box-shadow: 0px 0 10px rgba(1, 0, 0, 0.9);
  width: 100%;
  font-family: 'Playfair Display', serif;
  list-style: none;
  font-size: 25px;
  height: auto;
}

a:hover {
  color: white;
  border-radius: 5px;
}

a.a-active {
  color: gold;
  border-radius: 5px;
}

.nav-link {
  text-decoration: none;
  color: black;
}
</style>