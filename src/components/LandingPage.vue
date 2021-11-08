<template>
  <div class="container xxl">
    <div class="row mt-5">
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

        <div class="buttons-up">
           <div>
          <button type="button" class="btn btn-outline-success btn-sm form-control my-1"> 
            Download on PlayStore <img src="../assets/android.png" alt="logo-here" class="dl-logo"/>
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-outline-success btn-sm form-control my-1">
            Download For Android <img src="../assets/android.png" alt="logo-here" class="dl-logo"/>
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-outline-success btn-sm form-control my-1">
            Download For Windows <img src="../assets/windows.png" alt="logo-here" class="dl-logo"/>
          </button>
        </div>
        <div>
          <button type="button" class="btn btn-outline-success btn-sm form-control my-1">
            Download For Linux <img src="../assets/linux.png" alt="logo-here" class="dl-logo"/>
          </button>
        </div>
        </div>

        <p>
          <b>Francisco Dagohoy</b> led the longest revolt against the Spaniards in
          Philippine history. The revolt took the Spaniards 85 years (1744-1829)
          to quell. Forced labor was one of the causes of the revolt. But what
          triggered the decision to rise up in arms against the Spanish
          authorities in Bohol was the refusal of a Jesuit priest to give a
          Christian burial to Dagohoy's brother.
        </p>
      </div>
    </div>
  </div>
  <footer>
    <p class="text-center text-muted">Alrights reserve @2021 </p>
  </footer>
</template>
<script>
export default {
  data() {},
};
</script>
<style scoped>
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
.buttons-up{
  font-family:Arial;
}
button {
  box-shadow: 0px 0px 5px 2px rgba(0, 0, 0, 0.5);
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
  font-family: Garamond;
  margin-top: 3%;
}
footer{
  height: 2rem;
  margin-top: 2rem;
  background-color: #948f8f;
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