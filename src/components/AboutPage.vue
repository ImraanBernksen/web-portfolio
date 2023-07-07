<template>
    <div id="about">
      <h1>About</h1>
      <div class="container pt-4">
        <div class="row">
          <div class="col-12 col-lg-6">
            <div id="border-about" class="border-img animate__animated animate__fadeInLeft" style="padding: 42px;">
              <img class="img-fluid" src="https://i.postimg.cc/8PP9yW3X/undraw-Profile-re-4a55.png"
                style="width: 100%;">
            </div>
          </div>
          <div class="col-12 col-lg-6">
            <div id="border-about" class="border-img animate__animated animate__fadeInRight">
              <h4 class="about-par"><ins>ABOUT ME</ins></h4>
              <p class="lead about-par">
                I'm 20 years old and born in Cape Town, South Africa. I'm a IT Intern for LC Studio
                at Life Choices Academy and i would like to have a job in web development.
                Graduated from Oaklands Highschool in 2020 then, after I did some online courses.
                I'm very mature for my age, friendly and hardworking. I've
                always been interested in technology, web design and software development.
                I enjoy interacting and work with people. One of my most important attributes is
                responsibility, I appreciate being depended on and trustworthy. I will always go the
                extra mile and be helpful where I can.
              </p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-lg-6">
            <div id="border-about" class="border-img mt-3 animate__animated animate__fadeInLeft">
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
            <div id="border-about" class="border-img mt-3 animate__animated animate__fadeInRight" style="padding-bottom: 134px;">
              <h4 class="about-par"><ins>PERSONAL DETAILS</ins></h4>
              <p class="lead about-par">
                Name: Mogamad Imraan<br>
                Surname: Bernksen<br>
                Gender: Male<br>
                Birth: 04/07/2002<br>
                Cellphone: 0681278921<br>
                Email: imraanbernksen@gmail.com<br>
                Location: Highlands Estate, Cape Town, Western Cape<br>
              </p>
            </div>
          </div>
        </div>
    </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
#about {
    min-height: 200vh;
    width: 100%;
    background-color: #00FFA2;
}

#border-about {
    box-shadow: 0 3px 10px black;
    padding-right: 20px;
    padding-left: 20px;
}

#border-about:hover {
    background-color: white;
}

#border-img {
    box-shadow: 0 3px 10px black;
    padding: 20px;
}

#border-img:hover {
    background-color: white;
}

</style>