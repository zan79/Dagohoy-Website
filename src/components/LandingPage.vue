<template>
  <div class="container xxl">
    <div class="row mt-5">
      <div class="col-md-7 text-center">
        <img class="title-img-1" src="../assets/TitleArt.png" alt="titles" />

        <div class="iframe-container">
          <iframe
            src="https://www.youtube.com/embed/tV3tXUW0xVE"
            title="YouTube video player"
            allowfullscreen
          ></iframe>
        </div>

        <div class="row mt-3">
          <div class="col">
            <img class="screenshots" src="../assets/ones.jpg" alt="" />
          </div>
          <div class="col">
            <img class="screenshots" src="../assets/ones.jpg" alt="" />
          </div>
          <div class="col">
            <img class="screenshots" src="../assets/ones.jpg" alt="" />
          </div>
        </div>
      </div>

      <div class="col-md-5 text-center">
        <img
          class="title-img-2"
          src="../assets/TitleArt.png"
          alt="Dagohoy's Revolt"
        />

        <div>
          <button type="button" class="btn btn-success form-control my-1">
            <img src="../assets/android.png" alt="logo-here" class="dl-logo"/>
            Download on PlayStore
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-success form-control my-1">
            <img src="../assets/android.png" alt="logo-here" class="dl-logo"/>
            Download For Androids(apk)
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-success form-control my-1">
            <img src="../assets/windows.png" alt="logo-here" class="dl-logo"/>
            Download For Windows
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-success form-control my-1">
            <img src="../assets/linux.png" alt="logo-here" class="dl-logo"/>
            Download For Linux
          </button>
        </div>

        <p class="text-white">
          Francisco Dagohoy led the longest revolt against the Spaniards in
          Philippine history. The revolt took the Spaniards 85 years (1744-1829)
          to quell. Forced labor was one of the causes of the revolt. But what
          triggered the decision to rise up in arms against the Spanish
          authorities in Bohol was the refusal of a Jesuit priest to give a
          Christian burial to Dagohoy's brother.
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {},
};
</script>
<style scoped>
.iframe-container {
  overflow: hidden;
  /* 16:9 aspect ratio */
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
}
.dl-logo {
  width: 30px;
}
button {
  font-size: 1.2rem;
  border-radius: 20px;
}
.screenshots {
  height: 110px;
  border-radius: 2px;
  box-shadow: 0px 7px 14px #303436;
  cursor: pointer;
  transition: all 0.3s ease-out;
}
.screenshots:hover {
  transform: scale(1.2);
}
p {
  font-family: Leelawadee UI;
  margin-top: 10%;
}

@media screen and (max-width: 900px) {
  .title-img-1 {
    width: 18rem;
	margin-top: -50px;
  }
  .title-img-2 {
    width: 0px;
  }

  button {
    font-size: 0.8rem;
    border-radius: 20px;
  }

.screenshots {
  height: 150px;
  border-radius: 2px;
  margin-bottom: 20px;
  box-shadow: 0px 7px 14px #303436;
  cursor: pointer;
  transition: all 0.3s ease-out;
}
}
</style>