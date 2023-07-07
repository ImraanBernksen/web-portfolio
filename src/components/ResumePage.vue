<template>
    <div id="resume">
        <h1>Resume</h1>
        <div id="edu_exp">
            <div class="container">
                <div class="row">
                    <div class="col-lg-6 p-4 animate__animated animate__fadeInLeft">
                        <h4><ins>EDUCATION</ins></h4>
                        <div class="row pt-4 pb-4" id="border-edu">
                            <div class="col-sm-6 m-auto">
                                <div class="border-img">
                                    <img src="https://i.postimg.cc/RZRJCf0B/cropped-oaklands-badge-small-2.png"
                                        style="width: 10rem;">
                                </div>
                            </div>
                            <div class="col-sm-6 m-auto pt-3">
                                <p class="lead about-par">Oaklands High School, Chukker Rd, Lansdowne <br> - Matriculated
                                    (2016
                                    - 2020)</p>
                            </div>
                        </div>
                        <div class="row pt-2 pb-1 mt-4" id="border-edu">
                            <div class="col-sm-6 m-auto">
                                <div class="border-img">
                                    <img src="https://i.postimg.cc/FHmJQGNp/LIFE-CHOICES-ICON-ON-GREEN.jpg"
                                        style="width: 10rem;">
                                </div>
                            </div>
                            <div class="col-sm-6 m-auto pt-3">
                                <p class="lead about-par">Life Choices Academy, 314 Imam Harom Rd, Lansdowne <br> - LC
                                    Studio
                                    Intern (2023 - Currently) <br> - Lecturer Assistant (2023 - Currently)</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6 p-4 animate__animated animate__fadeInRight">
                        <h4><ins>EXPERIENCE</ins></h4>
                        <ul class="border-expert py-2">
                            <li>
                                <p class="lead about-par" id="expert">Grasshopper Coding Fundamentals I &amp; II
                                    Certifications
                                    - 2022 (Completed)</p>
                            </li>
                            <li>
                                <p class="lead about-par" id="expert">Responsive Web Design Developer Certification - 2022
                                    (Completed)</p>
                            </li>
                            <li>
                                <p class="lead about-par" id="expert">JavaScript Algorithms and Data Structures
                                    Certification -
                                    2022 (Completed)</p>
                            </li>
                            <li>
                                <p class="lead about-par" id="expert">Life Choices Coding Academy: <br> Full Stack Developer
                                    Course - 2022/23 (Completed)</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div id="techskills">
            <div class="container">
                <h4><ins>TECHNICAL SKILLS</ins></h4>
                <div class="row">
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-github fa-9x pt-4"></i><p>GIT</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-figma fa-9x pt-4"></i><p>FIGMA</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-html5 fa-9x"></i><p>HTML</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-css3 fa-9x"></i><p>CSS</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-bootstrap fa-9x"></i><p>BOOTSTRAP</p></div>
                </div>
                <div class="row">
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-square-js fa-9x"></i><p>JAVASCRIPT</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-vuejs fa-9x"></i><p>VUEJS</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-solid fa-database fa-9x pt-4"></i><p>MYSQL</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-node fa-9x pt-3"></i><p>NODE</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-solid fa-laptop fa-9x pt-4"></i><p>UI/UX</p></div>
                    <!-- <div class="col"><img class="pt-5 m-auto" style="width: 10rem;" id="imo"
                        src="https://i.postimg.cc/xCPgXnv3/ui.png"></div> -->
                </div>
                <div class="row">
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-wordpress fa-9x pt-4"></i><p>WORDPRESS</p>
                    </div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-sass fa-9x pt-4"></i><p>SASS</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-php fa-9x pt-4"></i><p>PHP</p></div>
                    <div class="col" id="skill_name"><i id="imo" class="fa-brands fa-searchengin fa-9x pt-4"></i><p>SEO</p></div>

                    <!-- <div class="col"><img class="pt-5 m-auto" style="width: 10rem; color: white" id="imo"
                            src="https://i.postimg.cc/050WXdJH/seo-2.png"></div> -->
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
#resume {
    background-color: black;
    color: white;
}

#skill_name {
    text-align: center;
}

#edu_exp {
    min-height: 100vh;
    width: 100%;
}

#techskills {
    min-height: 100vh;
    width: 100%;
}

#border-edu {
    box-shadow: 0 3px 10px white;
}

.border-expert {
    box-shadow: 0 3px 10px white;
}

.border-expert:hover {
    background-color: #00FFA2;
    color: black;
}

#border-edu:hover {
    background-color: #00FFA2;
    color: black;
}

#expert {
    padding: 18.6px;
}

#expert:hover {
    color: black;
}

.border-img {
    border: 1px solid;
    box-shadow: 5px 10px;
    width: 10rem;
    margin: auto;
}

.border-img:hover {
    border: 1px solid white;
    box-shadow: 5px 10px white;
}


.row>.col>i:hover {
    color: #00FFA2;
}

i.imo:hover {
    color: white;
}

.img-border {
    border: 5px solid #00334C;
    margin-left: 140px;
    margin-right: 140px;
}

i#mo:hover {
    color: #00FFA2;
}
</style>