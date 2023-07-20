<template>
    <div id="project">
        <h1>Project</h1>
        <div class="lead" id="projectlinks">
          <div class="row g-0" style="width: 100%;">
          <div class="card h-100 m-auto mt-4" v-for="item in arr" :key="item" style="width: 28rem; margin: auto; background-color: transparent;">
            <img :src="item.imgSrc" loading="lazy" class="card-img-top mt-2">
            <div class="card-body">
              <h4 class="card-title">{{item.projectName}}</h4>
              <p class="card-text">{{item.projectText}}</p>
              <a :href="item.linkOne" target="_blank" class="btn btn-outline-dark" id="btn_">GitHub</a>
              <a :href="item.linkTwo" target="_blank" class="btn btn-outline-dark" id="btn_">Hosting</a>
            </div>
          </div>
        </div>
        </div>
        <div class="lead" id="viewprojects">
          <ul>
            <li>
              <a
                id="M1I0B_"
                target="_blank"
                href="https://github.com/ImraanBernksen"
                class="fa-brands fa-github"
              ></a>
            </li>
            <li>
              <a
                id="M1I0B_"
                target="_blank"
                href="https://app.netlify.com/teams/imraanbernksen/overview"
                class="fa-solid fa-n"
              ></a>
            </li>
            <li>
              <a
                id="M1I0B_"
                target="_blank"
                href="https://codepen.io/IMRAANBERNKSEN"
                class="fa-brands fa-codepen"
              ></a>
            </li>
          </ul>
        </div>
          </div>
</template>
<script>
export default {
    data() {
      return {
        arr: [
          {
            imgSrc: "https://i.postimg.cc/ZRj3M6zy/project2.png",
            projectName: "JS Calculator",
            projectText: "Calculator",
            linkOne: "https://github.com/ImraanBernksen/JS_Calculator",
            linkTwo: "https://imraanbernksen-jscalculator.netlify.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/Jng5HKgJ/Screenshot-8.png",
            projectName: "Nostalgic",
            linkOne: "https://github.com/Mu-een/Nostalgic_NodeEOMP",
            projectText: "Ecommerce Website",
            linkTwo: "https://nostalgic-nodejs-eomp.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/GmGX1PZm/Screenshot-1.png",
            projectName: "Mesmerize",
            linkOne: "https://github.com/ImraanBernksen/Mesmerize_Project",
            projectText: "Ecommerce Website",
            linkTwo: "https://mesmerize-project10.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/BvKdDY2w/tcn-bnry-test.png",
            projectName: "TCN",
            linkOne: "https://github.com/ImraanBernksen/bnry_test-CC.git",
            projectText: "BNRY Assessment",
            linkTwo: "https://bnrytest-tcn.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/90SWFPvF/pf-1.png",
            projectName: "Web Design Porfolio",
            linkOne: "https://github.com/ImraanBernksen/myportfolio-vue3.git",
            projectText: "Portfolio",
            linkTwo: "https://myportfolio-mib.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/nVBV4YVt/quickloc8-1.png",
            projectName: "QuickLoc8 App",
            linkOne: "https://github.com/ImraanBernksen/quickloc8-test",
            projectText: "Quickloc8 Assessment",
            linkTwo: "https://quickloc8-test.web.app/",
          },
          {
            imgSrc: "https://i.postimg.cc/PrQ8FvT4/spli-the-squad.png",
            projectName: "Split The Squad",
            linkOne: "https://github.com/ImraanBernksen/split_the_squad",
            projectText: "Random Team Generator",
            linkTwo: "https://split-the-squad-5920b.web.app/",
          }
        ]
      }
    }
}
</script>
<style scoped>
#project {
    min-height: 200vh;
    width: 100%;
    background-color: #00FFA2;
    text-align: center;
}

#btn_ {
  font-family: 'Poppins', sans-serif;
  margin: 5px;
}

#M1I0B_ {
  color: black;
  font-size: 30px;
}

#M1I0B_:hover {
  color: white;
}

#projects {
  text-align: center;
  padding-bottom: 20px;
}
#projectlinks li {
  list-style: none;
}
#viewprojects li {
  list-style: none;
  padding: 0 5px;
  display: inline;
}
#viewprojects {
  padding: 20px;
}

#projects a {
  padding: 0 5px;
}
.project-tile {
  text-shadow: 0 0 8px black;
}

img {
  border-radius: 8px;
}
.card { 
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px black;
}
.card:hover {
  border-radius: 20px;
  box-shadow: 3px -3px 3px 3px white;
}
</style>