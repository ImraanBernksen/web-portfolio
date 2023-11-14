<template>
  <div id="about">
    <h1>About</h1>
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-6">
          <div id="border-about" class="mt-4 animate__animated animate__fadeInLeft"
            style="padding: 20px; align-items: center; justify-content: center; display: flex;">
            <!-- <img class="img-fluid" src="https://i.postimg.cc/8PP9yW3X/undraw-Profile-re-4a55.png" -->
            <img class="img-fluid" src="https://i.postimg.cc/cJCMphbB/pp-img.jpg" style="width: 72%; border-radius: 1%;">
          </div>
        </div>
        <div class="col-12 col-lg-6">
          <div id="border-about" class="mt-4 animate__animated animate__fadeInRight">
            <h4 class="about-par"><ins>ABOUT ME</ins></h4>
            <p class="lead about-par">
              At the age of 21, I was born in Cape Town, South Africa, and currently hold the position of Web Development Intern at YDMA Group. Demonstrating a maturity beyond my years, I am known for being friendly and diligent. My enduring interest lies in technology, encompassing web design and software development. Collaborating and engaging with people bring me immense satisfaction. Central to my character is a sense of responsibility, as I find fulfillment in being relied upon and deemed trustworthy. I am consistently prepared to exceed expectations and provide assistance wherever needed.
            </p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12 col-lg-6">
          <div id="border-about" class="mt-4 animate__animated animate__fadeInLeft">
            <h4 class="about-par"><ins>INTERESTS</ins></h4>
            <p class="lead about-par">
              My interests are working out, playing soccer, web design and designing clothing. Coding involves a lot of
              problem-solving skills. Web design allows me to showcase my creativity by designing visually appealing
              websites. Similarly, coding allows me to develop innovative solutions to real-world problems. The reason
              why so interested in soccer because it keeps me going and participating in team sports can provide a sense
              of community and social connection, which can improve my overall well-being. Exercise has improved my
              mental health by reducing stress, anxiety, and depression, and boosting self-esteem and cognitive
              function.
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-6">
          <div id="border-about" class="mt-4 animate__animated animate__fadeInRight" style="padding-bottom: 63px;">
            <h4 class="about-par"><ins>PERSONAL DETAILS</ins></h4>
            <p class="lead about-par">
              Name: Mogamad Imraan<br>
            </p>
            <p class="lead about-par">Surname: Bernksen<br>
            </p>
            <p class="lead about-par">
              Gender: Male<br>
            </p>
            <p class="lead about-par">
              Birth: 04/07/2002<br>
            </p>
            <p class="lead about-par">
              Cellphone: 0681278921<br>
            </p>
            <p class="lead about-par">
              Email: imraanbernksen@gmail.com<br>
            </p>
            <p class="lead about-par">
              Location: Highlands Estate, Cape Town, Western Cape<br>
            </p>
          </div>
        </div>
      </div>
      <!-- <a href="#landing"><button id="mybuttonup" class="btn btn-outline-dark"><i
            class="fa-solid fa-arrow-up fa-2x"></i></button></a>
      <a href="#resume"><button id="mybuttondown" class="btn btn-outline-dark"><i
            class="fa-solid fa-arrow-down fa-2x"></i></button></a> -->
    </div>
  </div>
</template>
<script>
export default {

}
</script>
<style scoped>
#about {
  min-height: 155vh;
  width: 100%;
  background-color: #00FFA2;
  padding-bottom: 60px;
}

#border-about {
  box-shadow: 0 3px 10px black;
  padding: 0px 20px 10px 20px;
}

#border-about:hover {
  background-color: white;
}

#mybuttonup {
  margin-left: 10px;
  margin-top: 10px;
  position: absolute;
  left: 0;
}

#mybuttondown {
  margin-right: 10px;
  margin-top: 10px;
  position: absolute;
  right: 0;
}
</style>

