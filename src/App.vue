<template>
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    word-wrap: break-word;
    scroll-behavior: smooth;
}

h1, h2, h3, h5, h6 {
    font-family: 'Playfair Display', serif;
    text-align: center;
    padding-bottom: 20px;
    padding: 20px;
}
h4 {
    font-family: 'Playfair Display', serif;
    text-align: center;
    padding-bottom: 20px;
    padding-top: 20px;
}

p, button {
    font-family: 'Poppins', sans-serif;
}

#skills {
    padding-bottom: 30px;
    text-align: center;
}

.about-par{
    text-align: start;
}

#social-media a {
    padding: 0 5px;
}


#social-media {
    text-align: center;
    padding-bottom: 20px;
}

#socials {
    text-decoration: none;
    padding: 6px
}

.img {
    border-radius: 50%;
}

.photo {
    border-radius: 50%;
}

#picture {
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size:cover;
}

#M1I0B_ {
    padding: 0 5px;
    text-decoration: none;
}

#imo {
    display: block;
    padding-top: 10px;
}

.home_extra {
    text-align: center;
    padding-top: 30px;
}

.form-label {
    padding-top: 15px;
}

#cards_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 5px 10px;
}

#btn_ {
    border: 1px solid;
    padding: 10px;
    box-shadow: 1px 5px;
}

#about1_ {
    border: 1px solid;
    box-shadow: 5px 10px;
    padding: 20px;
    text-decoration: none;
    font-family: 'Poppins', sans-serif;
    margin: 5px;
}

@media screen and (max-width:300px) {
    body {
    width: 100%;
    }
}
</style>
