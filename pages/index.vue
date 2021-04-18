<template>
  <section class="img-bg" style="height: 681px;">
    <div class="containerku flex justify-between" style="height: 681px">
      <div class="wrapp flex items-center">
        <div class="content">
          <h1 class="text-5xl font-bold pb-2" style="color: #514035;">Rizwan Gustama</h1>
          <h2 class="text-3xl font-medium pb-2" style="color: #7B685F;">Front End Developer</h2>
          <h3 class="text-2xl font-medium" style="color: #7B685F;">UI/UX Design</h3>

          <button class="px-20 py-2 mt-10 rounded-full text-white">Portofolio</button>
        </div>
      </div>

      <div class="gambar pt-20">
        <img src="~/assets/img/Mask Group 1.svg" style="height: 600px" alt="">
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
.img-bg {
  background-image: url('~/assets/img/Group 208.svg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
button{
  background: linear-gradient(90deg, rgba(254,141,62,1) 35%, rgba(234,90,67,1) 100%);
}
</style>

