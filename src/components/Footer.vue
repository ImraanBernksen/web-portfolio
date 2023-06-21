<template>
    <div id="footer">
        <footer>
            <div class="container text-center pt-3">
                <div class="row">
                    <div class="col-lg-3">
                        <a id="socials" target="_blank" href="https://instagram.com/imraanbernksen/"
                            class="fa-brands fa-instagram"></a>
                        <a id="socials" target="_blank" href="https://github.com/ImraanBernksen"
                            class="fa-brands fa-github"></a>
                        <a id="socials" target="_blank" href="https://www.linkedin.com/in/imraanbernksen/"
                            class="fa-brands fa-linkedin"></a>
                    </div>
                    <div class="col-lg-6">
                        <a class="quick" href="/">HOME</a>
                        <a class="quick" href="/about">ABOUT</a>
                        <a class="quick" href="/resume">RESUME</a>
                        <a class="quick" href="/projects">PROJECTS</a>
                        <a class="quick" href="/testimonials">TESTIMONIALS</a>
                        <a class="quick" href="/contact">CONTACT</a>
                    </div>
                    <div class="col-lg-3">
                        <p class="lead pt-2">Copyright &copy; 2023 <a href="/" class="footer-mib">MIB</a></p>
                    </div>
                </div>
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
    /*display: block;*/
    color: white;
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
}
</style>