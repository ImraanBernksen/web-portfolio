<template>
    <div id="footer">
        <footer>
            <div class="container text-center pt-3">
                <div class="row">
                    <!-- <div class="col-lg-4 lead">
                        <div class="lead about-par text-start">
                            <p><i id="icon" class="fa-sharp fa-solid fa-location-dot"></i> Address: Highlands Estate, Cape
                                Town, Western Cape</p>
                            <p><i id="icon" class="fa-solid fa-phone"></i> Cellphone: 0681278921</p>
                            <p><i id="icon" class="fa-solid fa-envelope"></i> Gmail: imraanbernksen@gmail.com</p>
                        </div>
                    </div> -->
                    <div class="col-lg-8">
                        <a class="quick" href="/">HOME</a>
                        <a class="quick" href="/about">ABOUT</a>
                        <a class="quick" href="/resume">RESUME</a>
                        <a class="quick" href="/projects">PROJECTS</a>
                        <a class="quick" href="/testimonials">TESTIMONIALS</a>
                        <a class="quick" href="/contact">CONTACT</a>
                    </div>
                    <div class="col-lg-4 lead m-auto">
                        <a id="socials" target="_blank" href="https://instagram.com/imraanbernksen/"
                            class="fa-brands fa-instagram"></a>
                        <a id="socials" target="_blank" href="https://github.com/ImraanBernksen"
                            class="fa-brands fa-github"></a>
                        <a id="socials" target="_blank" href="https://www.linkedin.com/in/imraanbernksen/"
                            class="fa-brands fa-linkedin"></a>
                        <p class="lead pt-2">Copyright &copy; 2023 <a href="/" class="footer-mib">MIB</a></p>
                    </div>
                </div>
                <!-- <br>
                <div class="line"></div>
                <br>
                <p class="lead" style="margin-bottom: 0;">MIB &copy; COPYRIGHT 2023</p> -->
            </div>
        </footer>
    </div>
</template>
<script>
export default {
    name: 'FooterComponent'
}
</script>
<style scoped>
#footer {
    background-color: black;
    color: white;
}

/*
a#socials {
    display: inline;
}
*/

.footer-mib {
    text-decoration: none;
    color: #00FFA2;
}

.footer-mib:hover {
    color: white;
}

#socials {
    text-decoration: none;
    padding: 10px;
    display: block;
    color: black;
    font-size: 30px;
}

#socials:hover {
    color: #00FFA2;
}

#icon {
    margin: auto;
    color: #00FFA2;
    padding: 10px;
}

footer {
    padding: 10px;
    box-shadow: 0px 0 19px rgba(1, 0, 0, 0.9);
    width: 100%;
}

.quick:hover {
    color: #00FFA2;
}

.quick {
    display: inline-block;
    padding: 5px;
    color: white;
    /*text-align: start; */
    font-size: 18px;
    text-decoration: none;
    font-family: 'Poppins', sans-serif;
}

.line {
    height: 2px;
    width: 85vw;
    background-color: black;
    justify-content: center;
    margin: auto;
}

a:hover {
    color: blue;
}</style>