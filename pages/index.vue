
<template>
  <div :style="{'background-image':'url(https://wallpapercave.com/wp/wp2379097.jpg)'}">

<!---->

<div class="navbar">
<div class="flex-1 text-3xl text-white ">
    <div class="avatar">
  <div class="w-20 rounded-full m-1 hover:ring ring-primary ">
    <img src="https://i.imgur.com/it1lDhd.png" />
     
  </div>
</div>
<p>{{ gamertag }} <br>  <kbd class="kbd text-xl bg-white text-black rounded-full">G</kbd> {{randomNumber()}}</p>
</div>
 <div class="flex-none text-white text-2xl">
  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-mic-mute" viewBox="0 0 16 16">
  <path d="M13 8c0 .564-.094 1.107-.266 1.613l-.814-.814A4.02 4.02 0 0 0 12 8V7a.5.5 0 0 1 1 0v1zm-5 4c.818 0 1.578-.245 2.212-.667l.718.719a4.973 4.973 0 0 1-2.43.923V15h3a.5.5 0 0 1 0 1h-7a.5.5 0 0 1 0-1h3v-2.025A5 5 0 0 1 3 8V7a.5.5 0 0 1 1 0v1a4 4 0 0 0 4 4zm3-9v4.879l-1-1V3a2 2 0 0 0-3.997-.118l-.845-.845A3.001 3.001 0 0 1 11 3z"/>
  <path d="m9.486 10.607-.748-.748A2 2 0 0 1 6 8v-.878l-1-1V8a3 3 0 0 0 4.486 2.607zm-7.84-9.253 12 12 .708-.708-12-12-.708.708z"/>
</svg>
&nbsp
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-battery-full" viewBox="0 0 16 16">
  <path d="M2 6h10v4H2V6z"/>
  <path d="M2 4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H2zm10 1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h10zm4 3a1.5 1.5 0 0 1-1.5 1.5v-3A1.5 1.5 0 0 1 16 8z"/>
</svg>
&nbsp
 <span id="time"></span>
  </div>
</div>
<br>
<br>
<!---->
<div class="flex flex-wrap gap-4 m-10">
  <div><NuxtLink to="./temp"><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://venturebeat.com/wp-content/uploads/2016/06/netflix-logo.png?fit=2048%2C2048&strip=all"></NuxtLink></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://pbs.twimg.com/media/FKVoOYOXoAABU4E?format=jpg&name=medium"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://cdn.vox-cdn.com/thumbor/lZYVMlOfLbZsA6GqBPWmXpsdlPc=/1400x1400/filters:format(jpeg)/cdn.vox-cdn.com/uploads/chorus_asset/file/10692939/687474703a2f2f692e696d6775722e636f6d2f476c537665734d2e6a7067.jpg"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://image.api.playstation.com/vulcan/ap/rnd/202211/0711/kh4MUIuMmHlktOHar3lVl6rY.png"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://images.nintendolife.com/759b714170cf4/ori-and-the-will-of-the-wisps-cover.cover_large.jpg"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://www.mobygames.com/images/covers/l/601919-call-of-duty-modern-warfare-playstation-4-front-cover.png"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-60 h-60" src="https://www.mobygames.com/images/covers/l/672322-minecraft-playstation-4-front-cover.jpg"></div>
</div>
<!---->
<div class="flex flex-wrap gap-8 m-10">
  <div class="w-120 h-30">
   <img class="rounded-lg border-4 border-transparent hover:border-primary w-120 h-60" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZd6ZxEHWXQxQIii7CFXoNEhd_xge5LrwJ_tQJciTXMUj0MhiEWNMtC496yTR-5wpZMAo&usqp=CAU">
  </div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-120 h-60" src="https://images3.alphacoders.com/581/thumb-1920-581580.jpg"></div>
  <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-120 h-60" src="https://cdn.wallpapersafari.com/29/47/s6ubyJ.jpg"></div>
   <div><img class="rounded-lg border-4 border-transparent hover:border-primary w-120 h-60" src="https://i.ytimg.com/vi/nouhpfSGcxE/maxresdefault.jpg"></div>
</div>
<br>
<!----->
<div class="m-4 text-4xl text-white-100">
<p>{{hone}}</p>
<p>{{htwo}}</p>
<p>{{hthree}}</p>
</div>
<br>
<br>
 


</div>
</template>
<script>
export default {
  data() {
    return {
      gamertag: 'pohadkove',
      hone: 'Store',
      htwo: 'Game Pass',
      hthree: 'Community',
    }
  },
  methods : {
    randomNumber : function(){
      return Math.floor(Math.random() * (50000 - 1 + 1)) + 1;
    }
  }
}


let date = new Date();
	date = date.toLocaleTimeString([], { timeStyle: 'short' });
	setInterval(() => {
		date = new Date();
    document.getElementById("time").innerHTML = date
	}, 1000);

</script>