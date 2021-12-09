<template>
  <div class="container xxl">
    <div class="row mt-2">
      <div class="col-md-7 text-center">
        <img class="title-img-1" src="../assets/TitleArt.png" alt="titles" />

        <div class="iframe-container">
          <iframe
            src="https://www.youtube.com/embed/uly5n5hrwms"
            title="YouTube video player"
            allowfullscreen
          ></iframe>
        </div>

        <div class="row mt-3">
          <div class="col">
            <img class="screenshots" src="@/assets/ss1.png" alt="" />
          </div>
          <div class="col">
            <img class="screenshots" src="@/assets/ss2.png" alt="" />
          </div>
          <div class="col">
            <img class="screenshots" src="@/assets/ss3.png" alt="" />
          </div>
        </div>
      </div>

      <div class="col-md-5 text-center">
        <img
          class="title-img-2"
          src="../assets/TitleArt.png"
          alt="Dagohoy's Revolt"
        />

        <div class="buttons-up">
          <!--<div>
            <button
              type="button"
              class="btn btn-success btn-sm form-control my-1"
            >
              Download on PlayStore
              <img
                src="../assets/android.png"
                alt="logo-here"
                class="dl-logo"
              />
            </button>
          </div> -->
          <div>
            <!-- href="https://drive.google.com/uc?export=download&id=1JIAoJmbQWb3v95E3EdX2fMLNCOMgwmME" -->
            <!-- href="https://download940.mediafire.com/cwop3zdh65kg/bim2hzjp374wqqa/Dagohoy%5C%27sRevolt+v0.2.apk" -->
            <!-- href="https://www.googleapis.com/drive/v3/files/1JIAoJmbQWb3v95E3EdX2fMLNCOMgwmME?alt=media&key=AIzaSyD-AkvKHTa2GbknEib4yi3ovIQEokbn3KE" -->
            <a
              class="btn btn-sm form-control my-1"
              href="https://drive.google.com/u/0/uc?export=download&confirm=WyKC&id=1JIAoJmbQWb3v95E3EdX2fMLNCOMgwmME"
              target="_blank"
            >
              Download For Android
              <img
                src="../assets/android.png"
                alt="logo-here"
                class="dl-logo"
              />
            </a>
          </div>
          <div>
            <!-- href="https://drive.google.com/uc?export=download&id=1aJoCzor-lsmTSuOYFH98uNQJ8-51vbgh" -->
            <!-- href="https://download1084.mediafire.com/kamt65brhisg/arqpwey7m4252q7/Dagohoy%5C%27sRevoltSetup+v0.2.exe" -->
            <!-- href="https://www.googleapis.com/drive/v3/files/1aJoCzor-lsmTSuOYFH98uNQJ8-51vbgh?alt=media&key=AIzaSyD-AkvKHTa2GbknEib4yi3ovIQEokbn3KE" -->
            <a
              class="btn btn-sm form-control my-1"
              href="https://drive.google.com/u/0/uc?export=download&confirm=J-Ue&id=1aJoCzor-lsmTSuOYFH98uNQJ8-51vbgh"
              target="_blank"
            >
              Download For Windows
              <img
                src="../assets/windows.png"
                alt="logo-here"
                class="dl-logo"
              />
            </a>
          </div>
         <!--- <div>
            <button
              type="button"
              class="btn btn-success btn-sm form-control my-1"
            >
              Download For Linux
              <img src="../assets/linux.png" alt="logo-here" class="dl-logo" />
            </button>
          </div> --> 
        </div> 

        <table class="table table-sm  mx-auto mt-3">
          <tbody class="text-center text-white">
            <tr>
              <td class="text-start fw-bold">Status</td>
              <td class="text-start"><span href="#">Prototype</span></td>
            </tr>
            <tr>
              <td class="text-start fw-bold">Platforms</td>
              <td class="text-start"><span>Android, Windows</span></td>
            </tr>
            <tr>
              <td class="text-start fw-bold">Genre</td>
              <td class="text-start">
                <span>Educational, Adventure, RPG</span>
              </td>
            </tr>
            <tr>
              <td class="text-start fw-bold">Tags</td>
              <td class="text-start"><span>3D, Single Player</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
    <div class="footer-dark">
          <footer>
              <div>
                    <div class="item text">
                        <h3 class="container" style="font-size:15px;"><strong>About</strong></h3>
                        <div>
                          <p class="text-center container">The game entitle "Dagohoy's Revolt" is a Capstone Project. This game is made to promote and Distribute knowledge about a Boholano hero Francisco Sendrijas also known as "Dagohoy" </p></div><hr>
                    </div>
                      <p class="copyright"><strong>All rights reserved © 2021</strong></p>
              </div>
          </footer>
      </div>
</template>
<script>
export default {
  data() {},
};
</script>
<style scoped>
table {
  width: 20rem;
}

* {
  font-family: sans-serif, "Times New Roman", Times, serif;
}
.iframe-container {
  box-shadow: 0px 0px 5px 2px rgba(0, 0, 0, 0.5);
  overflow: hidden;
  padding-top: 56.25%;
  position: relative;
}

.iframe-container iframe {
  border: 0;
  height: 100%;
  left: 0;
  position: absolute;
  top: 0;
  width: 100%;
}
.title-img-1 {
  width: 0px;
}
.title-img-2 {
  width: 25rem;
  margin-top: -2rem;
  margin: -2rem;
}
.dl-logo {
  width: 30px;
  height: 2rem;
  filter: invert(1%) sepia(1%) saturate(1%) hue-rotate(1deg) brightness(1000%) contrast(80%);
}
.buttons-up{
  margin-top: 25px;
  margin-bottom: 9rem;
}
.btn {
  /* box-shadow: 0px 0px 5px 2px rgba(0, 0, 0, 0.5); */
  box-shadow: 0px 3px 6px #303436;
  background: #187401;
  color: #f0f9ff;
  width: 16rem;
  font-size: 18px;
  border-radius: 10px;
}
.screenshots {
  height: 110px;
  border-radius: 2px;
  box-shadow: 0px 3px 6px #303436;
  cursor: pointer;
  transition: all 0.3s ease-out;
}
.screenshots:hover {
  transform: scale(1.2);
}
p {
  text-align: justify;
  text-justify: inter-word;
  text-indent: 50px;
}
@media screen and (max-width: 900px) {
  .title-img-1 {
    width: 18rem;
  }
  .title-img-2 {
    width: 0px;
  }

  .screenshots {
    height: 110px;
    border-radius: 2px;
    margin-bottom: 20px;
    box-shadow: 0px 7px 14px #303436;
    cursor: pointer;
    transition: all 0.3s ease-out;
  }
  .dl-logo {
    width: 30px;
    height: 2rem;
  }
  
}



.footer-dark {
  position:absolute;
  bottom: 0px;
  padding-top: 19px;
  width:100%;
  height: 150px;
  color:#f0f9ff;
  background: #7e1e04;
}

.footer-dark h3 {
  margin-top:0;
  font-weight:bold;
  font-size:14px;
}

.footer-dark ul {
  padding:0;
  list-style:none;
  line-height:1.6;
  font-size:14px;
  margin-bottom:0;
}

.footer-dark ul a {
  color:inherit;
  text-decoration:none;
  opacity:0.6;
}

.footer-dark ul a:hover {
  opacity:0.8;
}


@media (max-width:767px) {
  .footer-dark .item text {
    margin-bottom:0;
  }
}

.footer-dark .item.text p {
  opacity:0.6;
  margin-bottom:0;
}

@media (max-width:991px) {
  .footer-dark {
  position:relative;
  bottom: 0px;
  line-height: 15px;
  padding-top: 19px;
  width:100%;
  height: 200px;
  color:#f0f9ff;
  background: #7e1e04;
}
}

.footer-dark .item.social > a {
  font-size:20px;
  width:36px;
  height:36px;
  line-height:36px;
  display:inline-block;
  text-align:center;
  border-radius:50%;
  box-shadow:0 0 0 1px rgba(255,255,255,0.4);
  margin:0 8px;
  color:#fff;
  opacity:0.75;
}

.footer-dark .item.social > a:hover {
  opacity:0.9;
}

.footer-dark .copyright {
  text-align:center;
  font-size:13px;
  margin-bottom:0;
}
@media (max-width: 1366px) and (min-width: 768px) {
  .footer-dark {
  position:relative;
  bottom: 0px;
  line-height: 15px;
  padding-top: 19px;
  width:100%;
  height: 132px;
  color:#f0f9ff;
  background: #7e1e04;
}
.buttons-up{
  margin-top: 5px;
  margin-bottom: 7rem;
}

}

</style>