<template>
  <div id="app" class="flex h-screen">
    <div class="profile bg-blue-200 p-10 rounded-xl shadow-2xl m-auto text-center w-80 animate-pulse">
      <img
        src="https://scontent.fcnx2-1.fna.fbcdn.net/v/t31.18172-8/12265944_982653401778485_3423967004235640155_o.jpg?_nc_cat=107&ccb=1-4&_nc_sid=cdbe9c&_nc_ohc=Zj0Xfk88dE0AX-dmkvl&_nc_ht=scontent.fcnx2-1.fna&oh=af7fb7a5b940013d1b287a1f0598b665&oe=61397361"
        alt=""
        class="w-40 h-40 object-cover rounded-full shadow-xl hover:shadow-2xl mx-auto mb-6"
      />
    <h1 class="text-xl">Hello Mustofa</h1>
    <p class="text-gray-500">I am Frontend Developer.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
body {
  background: #8e9eab; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #eef2f3,
    #8e9eab
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #eef2f3,
    #8e9eab
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>
