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
          <!-- <div>
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
              <!-- href="https://drive.google.com/u/0/uc?export=download&confirm=WyKC&id=1JIAoJmbQWb3v95E3EdX2fMLNCOMgwmME" -->
            <a
              class="btn btn-outline-success btn-sm form-control my-1"
              href="https://download940.mediafire.com/cwop3zdh65kg/bim2hzjp374wqqa/Dagohoy%5C%27sRevolt+v0.2.apk"

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
              <!-- href="https://drive.google.com/u/0/uc?export=download&confirm=J-Ue&id=1aJoCzor-lsmTSuOYFH98uNQJ8-51vbgh" -->
            <a
              class="btn btn-outline-success btn-sm form-control my-1"
              href="https://download1084.mediafire.com/kamt65brhisg/arqpwey7m4252q7/Dagohoy%5C%27sRevoltSetup+v0.2.exe"

            >
              Download For Windows
              <img
                src="../assets/windows.png"
                alt="logo-here"
                class="dl-logo"
              />
            </a>
          </div>
          <!-- <div>
            <button
              type="button"
              class="btn btn-success btn-sm form-control my-1"
            >
              Download For Linux
              <img src="../assets/linux.png" alt="logo-here" class="dl-logo" />
            </button>
          </div> -->
        </div>

        <table class="table table-sm table-bordered mx-auto mt-3">
          <tbody class="text-center">
            <tr>
              <td class="text-end fw-bold">Status</td>
              <td class="text-start"><span href="#">Prototype</span></td>
            </tr>
            <tr>
              <td class="text-end fw-bold">Platforms</td>
              <td class="text-start"><span>Android, Windows</span></td>
            </tr>
            <tr>
              <td class="text-end fw-bold">Genre</td>
              <td class="text-start">
                <span>Educational, Adventure, RPG</span>
              </td>
            </tr>
            <tr>
              <td class="text-end fw-bold">Tags</td>
              <td class="text-start"><span>3D, Single Player</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <!-- <footer class="page-footer font-small mt-4">
    <div class="footer-copyright text-center py-1 text-light">
      All rights reserve &copy; 2021
    </div>
  </footer> -->
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
}
.btn {
  /* box-shadow: 0px 0px 5px 2px rgba(0, 0, 0, 0.5); */
  box-shadow: 0px 3px 6px #303436;
  width: 16rem;
  font-size: 1rem;
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
/* footer {
  height: 2rem;
  background-color: #000000;
} */
footer {
  background-color: #000;
}

@media screen and (max-width: 900px) {
  .title-img-1 {
    width: 18rem;
  }
  .title-img-2 {
    width: 0px;
  }

  button {
    box-shadow: 0px 0px 5px 2px rgba(0, 0, 0, 0.5);
    width: 14rem;
    font-size: 0.8rem;
    border-radius: 10px;
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
</style>