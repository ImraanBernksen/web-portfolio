<template>
    <div id="testimonials">
        <h1>Testimonials</h1>
        <div class="container">
            <div class="row">
                <div class="card m-3" v-for="item in arr" :key="item">
                    <div class="row g-0" style="width: 100%;">
                        <div class="col-md-6 col-sm-6">
                            <img :src="item.imgSrc" loading="lazy" class="img-fluid rounded-start mt-4 m-auto">
                            <h4 class="card-title mt-3" style="color: white;">{{ item.personName }}</h4>
                        </div>
                        <div class="col-md-6 col-sm-6">
                            <div class="card-body">
                                <p class="card-text mt-2 ms-3" style="font-size: large;">{{ item.infoText }}</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            arr: [
                {
                    personName: 'Meezaan Davids',
                    infoText: 'Imraan seems like chill guy who likes to keep to himself. He is a smart person who likes to be challenged and very passionate about soccer. He is a good judge of character, determined and hardworking. Engage conversions and topics with an innovate mindset to things.',
                    imgSrc: 'https://i.postimg.cc/pTFspNgf/t1.jpg',
                },
                {
                    personName: 'Kauthar Brandt',
                    infoText: 'Imraan is a friendly individual and a pleasure to work with because of his supporting attributes. He encourages his peers to do their best, which allows him to work with any social group. His very knowledgeable on any topic, so its always lovely to engage in conversion with him.',
                    imgSrc: 'https://i.postimg.cc/9f6FFBY4/t5.jpg',
                },
                {
                    personName: 'Brogan Gys',
                    infoText: 'Imraan is a well rounded developer, having the skills to do both front end and backend with fantastic results. He can work well on his own and with a team, never cracks under pressure and always aims for perfection in his projects. He is a very punctual person, always on time, passionate person on the things he loves to do.',
                    imgSrc: 'https://i.postimg.cc/KjQBYJv7/t2.jpg',
                },
                {
                    personName: 'Joel Mukanya',
                    infoText: 'Imraan is the definition of a dedicated and professional young talent who has already proven to us that he is work-ready. He gained knowledge of web development, databases, APIs, and more. He volunteers as a lecturer assistant, and his duties are to assist students with their tasks and mark their assignments.',
                    imgSrc: 'https://i.postimg.cc/QdCvRYV6/Joel-Profile.jpg',
                },
                {
                    personName: 'Aliyah Du Toit',
                    infoText: 'He is a hard-working and compassionate individual. He never hesitates to assist others in need and is committed to achieving his goals. His determined attitude and welcoming personality allows him to prosper when collaborating with all types of personalities, making him an asset in group projects, as well as individual work.',
                    imgSrc: 'https://i.postimg.cc/mkwdYYVV/t6.jpg',
                },
                {
                    personName: 'Oslin Johnson',
                    infoText: 'Imraans diligence and adaptability makes him an invaluable asset to any team. His ability to foster collaboration and motivate others sets him apart, and his calm demeanor enables him to excel in any situation. His cool mind allows him to be an effective person.',
                    imgSrc: 'https://i.postimg.cc/2j00W7Qg/Oslin-Johnson.png',
                }
            ]
        }
    }
}
</script>
<style scoped>
#testimonials {
    min-height: 200vh;
    width: 100%;
    background-color: black;
    color: white;
}

img {
    border-radius: 50%;
    border-radius: 8px;
}

.card {
    box-shadow: 0 3px 10px white;
    background-color: #00FFA2;
    width: 18rem;
    margin: auto;
}
</style>