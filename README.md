<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZLAND</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="./style.css">

</head>
<body>
    <nav class="flex justify-between items-center mt-[1vh] w-[90vw] ml-[5vw]">
        <div class="cont flex flex-col justify-center">
        <img src="./assets/image 1.svg" alt="logo" class="w-12">
        <div class="text-base font-normal">ZLAND</div>
        </div>
        <button class="flex bg-[#418FF4] gap-3 p-3 rounded-3xl justify-center items-center h-10 "><img src="./assets/Google Play logo.svg" alt="playstore" class="w-5"><span class="text-white">Download Now</span></button>
    </nav>
    <div class="md:ml-56 md:mt-10">
        <div class="home-text">
          <h1 class="home-title text-center">
            We Change the Way How You Find, Trust and Pay For Your New Lands with
            AI Technology
          </h1>
          <p class="home-subtitle text-center">
            Do All Your Land Buying Process From a Single App
          </p><a class="a flex items-center justify-center" href="https://play.google.com/store/apps/details?id=com.ambalooms.Zland">
            <button class="flex bg-[#418FF4] gap-3 p-3 rounded-3xl justify-center items-center h-10"><img src="./assets/Google Play logo.svg" alt="playstore" class="w-5"><span class="text-white">Download App Now</span></button>
        </a>
          <div class="flex items-center justify-center">
            <img class="home-rating" src="./assets/images 1.svg" alt="" />
          </div>
        </div>
      </div>
</body>
</html>
* {
  margin: 0px;
  box-sizing: border-box;
  padding: 0px;
}

body {
 width: 100%; 
}
.zland-font {
  font-feature-settings: "clig" off, "liga" off;
  font-family: "DM Sans";
  font-style: normal;
  font-weight: 700;
  line-height: 20px;
  word-spacing: 4px;
}
.a{margin:0;
padding:0;
text-decoration:none;
}

.navbar {
  height: 10vh;
  width: 100%;
}

.navbar-item {
  display: flex;
  list-style: none;
  align-items: center;

  box-shadow: 0px 9.261px 25.93px 0px rgba(20, 20, 43, 0.05);
}

.navbar-logo {
  margin: 5px 20px 5px 5px;
  margin-left: 2vw;
}
.navbar-logo > img {
  height: 6vh;
}
.navbar-logo > h1 {
  font-size: 1rem;
}

.navbar-cta {
  margin-left: 70vw;
}
.download-btn {
  padding: 0px 20px;
  display: inline-flex;
  border-radius: 25px;
  outline: none;
  border: none;
  color: #fff;
  align-items: center;
  text-align: center;
  font-size: 1rem;
  /* 100% */
  background: #418ff4;
margin-left:2vw;
}
.zland-font{
  margin-top: 1rem;
}
.google-play-logo {
  height: 25px;
  width: 25px;
}
@media (min-width: 320px) and (max-width: 480px) {
  .navbar-cta {
    display: none;
  }

  .navbar-logo > img {
    height: 5vh;
  }
}
.navbar-item {

  box-shadow: 0px 0px 0px 0px rgba(20, 20, 43, 0.05);
}
.home-page {
  width: 100%;
  display: flex;
  overflow: hidden;
}
.home-text {
  width: 50vw;
  margin-top: 10vh;
  margin-left: 10vw;
}

.home-title {
  color: var(--Neutral-800, #170f49);
  font-size: 50px;
  line-height: 65px;
  word-spacing: 6px;
}
.home-subtitle {
  margin: 3.5vh 0;
  color: var(--Neutral-600, #6f6c90);
  font-weight: 400;
}
.home-rating {
  height: 30px;
  margin: 3.5vh 0;
}
.home-btn {
  margin: 3.5vh 0;
}
.home-img {
  overflow: hidden;
}
.home-illustration {
  margin: 15vh;
  height: 400px;
  transform: rotate(40deg);
}
@media (min-width: 320px) and (max-width: 480px) {
  .home-text {
    width: 95%;
    margin-top: 5vh;
    margin-left: 5%;
  }
  .home-title {
    text-align: left;
    font-size: 30px;
    line-height: 40px;
  }
  .home-img {
    display: none;
  }
}
.problem-page {
  display: flex;
  background-color: #ededed;
}
.problem-video {
  margin: 30px;
}
.problem-container {
  margin: 60px;
  text-align: center;
  padding-bottom: 3vh;
}
.problem-title {
  color: #000;
  line-height: 30px;
  justify-content: center;
}
.problem-text {
  margin: 30px 0;
  font-weight: 300;
  font-size: 1.3rem;
  color: #6f6c90;
  font-family: "Tajawal", sans-serif;
  line-height: 1.5;
}
.problem-founder {
  position: relative;
  margin-top: 10%;
  font: 1em sans-serif;
  margin-left: 50%;
}
.designation {
  font-weight: 400;
}
.youtube-mobile {
  display: none;
}
.founder{
  font-size: 1rem;
}
.designation{
  font-size: 0.7rem;
}
@media (min-width: 320px) and (max-width: 480px) {
  .problem-page {
    display: block;
    margin-top: 20px;
    padding-top: 10px;
  }
  .problem-video {
    margin: 30px 10px;
  }
  .youtube-mobile {
    display: block;
margin-left:5%;
  }
  .youtube-desktop {
    display: none;
  }
  .problem-founder {
    margin-left: 30%;
  }
  .problem-container {
    margin: 30px;
  }
}
#benefits {
  height: fit-content;
  width: 100%;
  margin-bottom: 10vh;
}

.benifits-heading {
  text-align: center;
  margin-top: 5vh;
  margin-bottom: 5vh;
  text-align: center;
  font-family: "DM Sans";
  font-size: 3rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  color: #3c3c3c;

}

.benifits-content {
  justify-content: center;
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 100%;
}

.benifits-content>.center {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 4vh;
  width: 30vw;
  margin-top: 4vh;
}

.para {
  color: #3c3c3c;
  text-align: center;
  font-family: "DM Sans";
  font-size: 1rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  width: 30vw;
  margin-top: 2vh;
  margin-bottom: 5vh;

}

.text {
  color: #3c3c3c;
  font-family: "DM Sans";
  font-size: 2rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-align: center;
}

.para1 {
  display: flex;

  width:100%;
  justify-content: space-around;

}



.flex-features {
  margin-left: 5%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  width: 90%;
  margin-right: 5%;

}

.cont1 {
  margin-top: 3vh;
  margin-bottom: 3vh;
  color: #3c3c3c;
  font-family: "DM Sans";
  font-size: 1.5rem;
  text-align: left;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}

#testimonals {
  padding-top: 2vh;
padding-left:2vw;
  background-color: #EDEDED;
}

.testimonals-heading {
  text-align: center;

  color: #3c3c3c;
  font-family: "DM Sans";
  font-size: 3rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}

.features-heading {
  text-align: center;
  color: #3c3c3c;
  font-family: "DM Sans";
  font-size: 3rem;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
}

#features {
  height: fit-content;
  margin-bottom: 10vh;
  width: 100%;
}

#faq {
  height: fit-content;
  width: 100%;
  padding-top: 2vw;
  padding-bottom: 5vw;
  background-color: #EDEDED;
}

.faq-heading {
  font-family: "DM Sans";
  font-size: 3rem;
  color: #3c3c3c;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-align: center;
}

.faq-container {
  margin: 0 auto;
  max-width: 70vw;
}

.faq {
  background-color: transparent;
  border: 1px solid #9fa4a8;
  border-radius: 10px;
  margin: 20px 0;
  overflow: hidden;
  padding: 30px;
  position: relative;
  transition: 0.3s ease;
}

i {
  color: #418ff4;
}

.faq.active {
  background-color: #fff;
  border-radius: 14px;
  border: 2px solid #418ff4;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1), 0 3px 6px rgba(0, 0, 0, 0.1);
}

.faq.active::before {
  color: #3498db;
  left: -30px;
  top: -10px;
  transform: rotateY(180deg);
}

.faq-title {
  margin: 0 35px 0 0;
  color: var(--Neutral-800, #170f49);
  font-feature-settings: "clig" off, "liga" off;

  /* Headings/Typography Size 4 */
  font-family: "DM Sans";
  font-size: clamp(14px, 22px, 24px);
  font-style: normal;
  font-weight: 500;
  line-height: 28px;
  /* 127.273% */
}

.faq-text {
  display: none;
  color: var(--Neutral-600, #6f6c90);
  font-feature-settings: "clig" off, "liga" off;

  /* Paragraph/Default */
  font-family: "DM Sans";
  font-size: 18px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px;
  /* 166.667% */
  margin: 30px 0 0;
}

.faq.active .faq-text {
  display: block;
}

.faq-toggle {
  align-items: center;
  background-color: transparent;
  border: 0;
  border-radius: 50%;
  cursor: pointer;
  display: flex;
  font-size: 1rem;
  height: 30px;
  justify-content: center;
  padding: 0;
  position: absolute;
  right: 30px;
  top: 30px;
  width: 30px;
}

.faq-toggle .fa-times,
.faq.active .faq-toggle .fa-chevron-down {
  display: none;
}

.faq.active .faq-toggle .fa-times {
  color: #fff;
  display: block;
}

.faq-toggle .fa-chevron-down {
  display: block;
}

.faq.active .faq-toggle {
  background-color: #9fa4a8;
}

.faq-toggle>img {
  width: 50px;
  height: 50px;
}

.download {
  display: flex;
  justify-content: space-around;
  margin-top: 5vh;
  margin-bottom: 5vh;
  width:100%;
}

.footer {
  background: #62b7fd;
  width: 100%;
  height: 272px;
}

.logotext {
  color: #fff;
  text-align: center;
  font-family: "DM Sans";
  font-size: 16.769px;
  font-style: normal;
  font-weight: 500;
  margin-top: -1px;
  line-height: normal;
  margin-left: 0px;
}

.flexfoot {
  padding-top: 20px;
  display: flex;
  justify-content:space-around;
  align-items: center;
}

.flexfoot>ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
 
}

.ul {
  list-style: none;
  display: flex;
  justify-content:space-evenly;
  margin-top: 5vh;
  color: #fff;
  text-align: center;
  font-family: "DM Sans";
  font-size: 10.769px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

.copyright {
  text-align: center;
  margin-top: 10vh;
  color: #fff;
  font-family: "DM Sans";
  font-size: 13px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}

.margin {
  margin-left: 5vw;
  margin-bottom: 5vh;
}

.width {
  width: 90%;
}

@media (min-width: 320px) and (max-width: 480px) {
  * {
    margin: 0;
    padding: 0;
  }

.flexfoot>ul {
  list-style: none;
  display: flex;
gap:5vw;
margin-top:1rem;
  align-items: center;
 
}
  .block {
    display: none;
  }

  .beneflex {
    display: flex;
    justify-content: space-between;
    width: 100%;
  }

  .flex-features {
    margin-left: 5%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 90%;
    margin-right: 5%;

  }

  .para1 {
    display: flex;
    width: 50vw;
    justify-content: space-around;
    flex-direction: column;

  }

  .benifits-content {
    justify-content: center;
    flex-direction: column;
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 80%;
  }

  .benifits-heading {
    font-size: 1.5rem;
  }

  .text {
    font-size: 1rem;
  }

  .para {
    margin-top: -1vh;
    font-size: 1rem;
    text-align: left;
    width: 50vw;
  }



  .faq-heading {
    color: #6f6c90;
    font-family: "DM Sans";
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    text-align: center;
    margin-left: 8%;
  }

  .faq-container {
    margin-left: 5vw;
    max-width: 90%;
  }

  .faq {
    background-color: transparent;
    border: 1px solid #9fa4a8;
    border-radius: 10px;
    margin: 20px 0;
    overflow: hidden;
    padding: 30px;
    position: relative;
    transition: 0.3s ease;
  }

  #features {
    height: fit-content;
    width:100%;
    margin-bottom: 7vh;
  }

  i {
    color: #418ff4;
  }

  .faq.active {
    background-color: #fff;
    border-radius: 14px;
    border: 2px solid #418ff4;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1), 0 3px 6px rgba(0, 0, 0, 0.1);
  }

  .faq.active::before {
    color: #3498db;
    left: -30px;
    top: -10px;
    transform: rotateY(180deg);
  }

  .faq-title {
    margin: 0 35px 0 0;
    color: var(--Neutral-800, #170f49);
    font-feature-settings: "clig" off, "liga" off;

    /* Headings/Typography Size 4 */
    font-family: "DM Sans";
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 28px;
    /* 127.273% */
  }

  .faq-text {
    display: none;
    color: var(--Neutral-600, #6f6c90);
    font-feature-settings: "clig" off, "liga" off;

    /* Paragraph/Default */
    font-family: "DM Sans";
    font-size: 13px;
    font-style: normal;
    font-weight: 400;
    line-height: 30px;
    /* 166.667% */
    margin: 30px 0 0;
  }

  .faq.active .faq-text {
    display: block;
  }

  .faq-toggle {
    align-items: center;
    background-color: transparent;
    border: 0;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    font-size: 1rem;
    height: 30px;
    justify-content: center;
    padding: 0;
    position: absolute;
    right: 30px;
    top: 30px;
    width: 30px;
  }

  .faq-toggle .fa-times,
  .faq.active .faq-toggle .fa-chevron-down {
    display: none;
  }

  .faq.active .faq-toggle .fa-times {
    color: #fff;
    display: block;
  }

  .faq-toggle .fa-chevron-down {
    display: block;
  }

  .faq.active .faq-toggle {
    background-color: #9fa4a8;
  }

  .faq-toggle>img {
    width: 50px;
    height: 50px;
  }

  .download {
    display: flex;
    justify-content: space-around;
    width:100%;
    margin-top: 5vh;
    margin-bottom: 5vh;
  }

  styles.css .testimonals-heading {
    text-align: center;
    color: #6f6c90;
    margin-left: 8%;
    font-family: "DM Sans";
    font-size: 30px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
  }

  .features-heading {
    text-align: center;
    color: #6f6c90;
    margin-left: 8%;
    font-family: "DM Sans";
    font-size: 30px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
  }

  body {
    overflow-x: hidden;
  }

  .flex-features {
    margin-left: 7vw;
    display: grid;
    grid-template-columns: 1fr 1fr;
    width: 93vw;

  }

  .cont1 {
    margin-top: 3vh;
    margin-bottom: 3vh;
    color: #4a4e54;
    font-family: "DM Sans";
    font-size: 20px;
  }
}
@media only screen and (max-width: 600px) {
    
    html{
        font-size: 6px;
    }
}
