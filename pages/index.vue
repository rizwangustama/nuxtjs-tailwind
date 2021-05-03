<template>
  <section>
    <section class="img-bg" style="height: 681px;">
      <div class="containerku flex justify-between" style="height: 681px">
        <div class="wrapp flex items-center">
          <div class="content">
            <h1 class="text-5xl font-bold pb-2" style="color: #514035;">
              Rizwan Gustama
            </h1>
            <h2 class="text-3xl font-medium pb-2" style="color: #7B685F;">
              Front End Developer
            </h2>
            <h3 class="text-2xl font-medium" style="color: #7B685F;">
              UI/UX Design
            </h3>

            <p class="pt-3 font-light" style="color: #7B716B;">
              We appreciate your business and guarantee a <br />
              response within 24 Business hour
            </p>

            <button class="px-20 py-2 mt-10 rounded-full text-white">
              Portofolio
            </button>
          </div>
        </div>

        <div class="gambar pt-20">
          <img
            src="~/assets/img/Mask Group 1.svg"
            style="height: 600px"
            alt=""
          />
        </div>
      </div>
    </section>

    <section id="about" class="bg-gray-100">
      <div class="containerku py-32">
        <div class="griding">
          <div>
            <h1 class="text-4xl font-bold mb-2" style="color: #392D25">
              About Me
            </h1>
            <h2
              class="text-3xl font-medium mb-2 leading-9"
              style="color: #7B685F"
            >
              Front end Developer
            </h2>
            <p
              class="text-1x font-light mb-10 leading-7"
              style="color: #7B716B"
            >
              Trees Studio is a Front End Developer and UI/UX Design <br />
              Development Team based in Sukabumi, Indonesia.
            </p>
            <nuxt-link
              to=""
              class="px-20 py-2 rounded-full text-white"
              style="background: linear-gradient(90deg, rgba(255,39,5,1) 35%, rgba(254,141,62,1) 100%);"
              >Read More</nuxt-link
            >
          </div>

          <div
            class="flex justify-center items-center"
            style="background: linear-gradient(0deg, rgba(255,105,105,1) 35%, rgba(196,56,136,1) 100%);"
          >
            <div class="colom1 h-full w-full">
              <div class="text-center flex items-center justify-center h-full">
                <div>
                  <h1 class="text-6xl font-bold text-white">14</h1>
                  <h4 class="text-white">Client</h4>
                </div>
              </div>
            </div>
          </div>
          <div
            class="bg-blue-100 flex justify-center items-center"
            style="background: linear-gradient(0deg, rgba(179,127,203,1) 35%, rgba(196,72,142,1) 100%);"
          >
            <div class="colom2 h-full w-full">
              <div class="text-center flex items-center justify-center h-full">
                <div>
                  <h1 class="text-6xl font-bold text-white">120</h1>
                  <h4 class="text-white">Website Create</h4>
                </div>
              </div>
            </div>
          </div>
        </div>
        <logo class="my-20" />
      </div>
    </section>

    <section class="what bg-white">
      <div class="containerku py-32">
        <div class="head-content">
          <h1 class="text-center pb-20 text-3xl font-bold" style="color: #392D25;">What We Do ?</h1>
        </div>
        <div class="main">
          <div class="grid grid-flow-col grid-cols-3 gap-10">
            <div class="cl bg-gray-300">
              <div class="wrapper p-10">
                <div class="head">
                  <img src="~/assets/img/dev.svg" width="200px" alt="" />
                </div>
                <div class="text-center mt-8">
                  <h1 class="mb-3 text-lg font-medium" style="color: #4E4E4E;">
                    Development
                  </h1>
                  <p class="text-xs" style="color: #4E4E4E;">
                    HTML/CSS, JavaScript Animation, WordPress, Responsive
                    Website
                  </p>
                </div>
              </div>
            </div>
            <div class="cl bg-gray-300">
              <div class="wrapper p-10">
                <div class="head">
                  <img src="~/assets/img/dev2.svg" width="200px" alt="" />
                </div>
                <div class="text-center mt-8">
                  <h1 class="mb-3 text-lg font-medium" style="color: #4E4E4E;">
                    UI/UX Design
                  </h1>
                  <p class="text-xs" style="color: #4E4E4E;">
                    Landing Pages, User Flow, Wireframing, Prototyping, Mobile
                    App Design, Web App
                  </p>
                </div>
              </div>
            </div>
            <div class="cl bg-gray-300">
              <div class="wrapper p-10">
                <div class="head">
                  <img src="~/assets/img/dev3.svg" width="200px" alt="" />
                </div>
                <div class="text-center mt-8">
                  <h1 class="mb-3 text-lg font-medium" style="color: #4E4E4E;">
                    Branding
                  </h1>
                  <p class="text-xs" style="color: #4E4E4E;">
                    Visual Identity, Stationary Kit, Marketing Materials
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="ccontainerku ">
        <h1 class="text-center">I have my Best skills, </h1>
      </div>
      <div class="grid grid-flow-col grid-cols-3 gap-10">
        <div class="col">1</div>
        <div class="col">2</div>
        <div class="col">3</div>
      </div>
    </section>

  </section>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";
import logo from "~/components/logo.vue";

export default {
  components: {
    AppLogo,
    logo
  }
};
</script>

<style>
.colom1 {
  background-image: url("~/assets/img/bg-colums.svg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  transition: all ease 0.5s;
}
.colom2 {
  background-image: url("~/assets/img/Group 209.svg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  transition: all ease 0.5s;
}
.colom1:hover {
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}
.colom2:hover {
  box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
}
.p {
  font-family: "Montserrat", "Source Sans Pro", -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
}

.img-bg {
  background-image: url("~/assets/img/Group 208.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
button {
  background: linear-gradient(
    90deg,
    rgba(255, 39, 5, 1) 35%,
    rgba(254, 141, 62, 1) 100%
  );
}
.grid-logo {
  column-gap: 20px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}

.logo {
  background-color: white;
}

.griding {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;
  column-gap: 20px;
}
</style>
