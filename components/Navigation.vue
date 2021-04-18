<template>
    <section>
        <div class="fixed bg-white shadow md:shadow-lg" style="width:100%;">
            <div class="containerku">
                <nav class="flex justify-between h-12">
                    <div class="left">
                        <img class="h-full" src="~/assets/img/Logo Tress Studio Baru.svg" alt="">
                    </div>
                    <div class="right">
                        <ul class="flex h-full">
                            <li class="px-4"><nuxt-link class="flex items-center h-full text-sm" to="/">Home</nuxt-link></li>
                            <li class="px-4"><nuxt-link class="flex items-center h-full text-sm" to="about">About US</nuxt-link></li>
                            <li class="px-4"><nuxt-link class="flex items-center h-full text-sm" to="">Project</nuxt-link></li>
                            <li class="px-4"><nuxt-link class="flex items-center h-full text-sm" to="">Contact</nuxt-link></li>
                        </ul>
                    </div>
                </nav>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
 .containerku {
     margin:  auto;
     max-width: 80%;
 }
 li{
     border-bottom: 2px solid transparent;
 }
 li:hover {
     border-bottom: 2px solid #FE8D3E;
  }
  a {
      color: #4E4E4E;
  }
</style>