<template>
     <div class="flex flex-col h-screen text-sm text-gray-400">
    <div class=" flex-1 flex overflow-y-hidden">
      <div class="slidbar  bg-gray-700-spotify w-48 flex flex-col ">
        <ul class="py-6 ml-3 font-semibold ">
          <li class="">
            <a href="#" class="flex py-2 group"> <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="hover:text-red feather feather-home"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg>
            <span class="ml-4 hover:text-red">Home</span></a>
          </li>
          <li class="group-hover:text-red">
            <a href="#" class="flex py-2"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-radio"><circle cx="12" cy="12" r="2"></circle><path d="M16.24 7.76a6 6 0 0 1 0 8.49m-8.48-.01a6 6 0 0 1 0-8.49m11.31-2.82a10 10 0 0 1 0 14.14m-14.14 0a10 10 0 0 1 0-14.14"></path></svg>
            <span class="ml-4">Radio</span></a>
          </li>
           <li class="group-hover:text-red">
             <a href="#" class="flex py-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-share-2"><circle cx="18" cy="5" r="3"></circle><circle cx="6" cy="12" r="3"></circle><circle cx="18" cy="19" r="3"></circle><line x1="8.59" y1="13.51" x2="15.42" y2="17.49"></line><line x1="15.41" y1="6.51" x2="8.59" y2="10.49"></line></svg>
             <span class="ml-4">Browes</span>
             </a>
          </li>
          </ul>
        <div class="overflow-y-auto sidebar-spotify px-5 mt-2">
          <h3 class="uppercase pt-3 tracking-widest text-gray-500 font-normal text-xs">Your Library</h3>
          <ul class="leading-extra-loose">
            <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Song</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
          </ul>
          <h3 class="uppercase pt-3 text-gray-500 font-normal text-xs">Your Library</h3>
          <ul class="leading-extra-loose">
            <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Song</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
          </ul>
           <h3 class="uppercase pt-3 text-gray-500 font-normal text-xs">Your Library</h3>
          <ul class="leading-extra-loose">
            <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Song</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
          </ul>
           <h3 class="uppercase pt-3 text-gray-500 font-normal text-xs">Your Library</h3>
          <ul class="leading-extra-loose">
            <li class="truncate"><a href="#" class="hover:text-white">Made For You</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Recently Played</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Liked Song</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Albums</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Artists</a></li>
            <li class="truncate"><a href="#" class="hover:text-white">Podcasts</a></li>
          </ul>
        </div>
      <div class="border-t border-gray-800 h-16 px-2 py-4 flex ">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-plus-circle"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="16"></line><line x1="8" y1="12" x2="16" y2="12"></line></svg>
        <span class="ml-2">New PlayList</span>
      </div>
      </div>
      <div class="content-spotify bg-gray-800-spotify flex-1 overflow-y-auto flex flex-col">
        <div class="top-bar flex justify-between items-center px-4 py-2">
          <div class="flex items-center">
             <button>
              <svg class="fill-current text-gray-400 hover:text-white h-10 w-10" viewBox="0 0 24 24" width="24" height="24"><path d="M14.7 15.3a1 1 0 01-1.4 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 011.4 1.4L11.42 12l3.3 3.3z"/></svg>
            </button>
            <button class="ml-1">
              <svg class="fill-current text-gray-400 hover:text-white h-10 w-10" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M9.3 8.7a1 1 0 011.4-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.4-1.4l3.29-3.3-3.3-3.3z"/></svg>
            </button>
            <div class="ml-4 relative">
              <input type="text" placeholder="Search" class="bg-white text-gray-800 placeholder-gray-800 rounded-full pl-8 py-1">
                <div class="absolute top-0">
              <svg class="fill-current text-gray-800 h-6 w-6 pt-1 pl-2" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M16.32 14.9l5.39 5.4a1 1 0 01-1.42 1.4l-5.38-5.38a8 8 0 111.41-1.41zM10 16a6 6 0 100-12 6 6 0 000 12z"/></svg>
            </div>
            </div>
          </div>
         <div class="flex items-center ">
            <button>
              <svg class="fill-current text-gray-400 hover:text-white w-6 h-6" viewBox="0 0 496 512"><path d="M248 104c-53 0-96 43-96 96s43 96 96 96 96-43 96-96-43-96-96-96zm0 144c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48zm0-240C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm0 448c-49.7 0-95.1-18.3-130.1-48.4 14.9-23 40.4-38.6 69.6-39.5 20.8 6.4 40.6 9.6 60.5 9.6s39.7-3.1 60.5-9.6c29.2 1 54.7 16.5 69.6 39.5-35 30.1-80.4 48.4-130.1 48.4zm162.7-84.1c-24.4-31.4-62.1-51.9-105.1-51.9-10.2 0-26 9.6-57.6 9.6-31.5 0-47.4-9.6-57.6-9.6-42.9 0-80.6 20.5-105.1 51.9C61.9 339.2 48 299.2 48 256c0-110.3 89.7-200 200-200s200 89.7 200 200c0 43.2-13.9 83.2-37.3 115.9z"/></svg>
            </button>
            <a href="#" class="ml-2 hover:underline hover:text-white">dredrehimself</a>
            <button class="ml-4">
              <svg class="fill-current text-gray-400 hover:text-white w-6 h-6" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M15.3 9.3a1 1 0 011.4 1.4l-4 4a1 1 0 01-1.4 0l-4-4a1 1 0 011.4-1.4l3.3 3.29 3.3-3.3z"/></svg>
            </button>
          </div>
        </div>
        <div class="second-section">
          <div class="container mx-auto px-4"><h2 class="mt-8 text-5xl font-semibold text-white">Home</h2>
          <h3 class="font-semibold text-xl border-b border-gray-900 pb-2 mb-4 mt-8">Recently Played</h3>
          <div class="flex items-center -mx-4">
          <div class="w-1/5 px-4">
          <div>
            <a href="#" class="mb-16"><img src="../assets/download.jpg" alt="Hmaza namira" ></a>
          </div>
          <div ><a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a></div>
          <div class=" text-gray-500 mt-2">Amazinf Acoustic Covers updata every week.</div>
          <div class="uppercase traking-widest text-xs text-gray-500 mt-2">6697 Followers</div>
          </div>
           <div class="w-1/5 px-4">
          <div>
            <a href="#" class="mb-16"><img src="../assets/adele.jpg" alt="Hmaza namira" ></a>
          </div>
          <div ><a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a></div>
          <div class=" text-gray-500 mt-2">Amazinf Acoustic Covers updata every week.</div>
          <div class="uppercase traking-widest text-xs text-gray-500 mt-2">6697 Followers</div>
          </div>
           <div class="w-1/5 px-4">
          <div>
            <a href="#" class="mb-16"><img src="../assets/mekky.jpg" alt="Hmaza namira" ></a>
          </div>
          <div ><a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a></div>
          <div class=" text-gray-500 mt-2">Amazinf Acoustic Covers updata every week.</div>
          <div class="uppercase traking-widest text-xs text-gray-500 mt-2">6697 Followers</div>
          </div>
           <div class="w-1/5 px-4">
          <div>
            <a href="#" class="mb-16"><img src="../assets/man.jpg" alt="Hmaza namira" ></a>
          </div>
          <div ><a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a></div>
          <div class=" text-gray-500 mt-2">Amazinf Acoustic Covers updata every week.</div>
          <div class="uppercase traking-widest text-xs text-gray-500 mt-2">6697 Followers</div>
          </div>
           <div class="w-1/5 px-4">
          <div>
            <a href="#" class="mb-16"><img src="../assets/lp.jpg" alt="Hmaza namira" ></a>
          </div>
          <div ><a href="#" class="font-semibold block hover:text-white mt-2">Acoustic Pop Covers 2019</a></div>
          <div class=" text-gray-500 mt-2">Amazinf Acoustic Covers updata every week.</div>
          <div class="uppercase traking-widest text-xs text-gray-500 mt-2">6697 Followers</div>
          </div>
          </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-gray-900-spotify h-22 flex py-6 px-6 items-center justify-between">
      <div class="flex items-center">
        <a href="#"><img src="../assets/download.jpg" class="w-12 h-12"></a>
        <div class="ml-3">
            <div class="text-white font-bold"><a href="#">Insan</a></div>
             <div class="text-gray-400 font-semibold"><a href="#">Hmaza Namira</a></div>
        </div>
      </div>
      <div class="player-controls flex flex-col justify-center">
        <div class="flex justify-center">
          <button>
            <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" viewBox="0 0 20 20"><path d="M6.59 12.83L4.4 15c-.58.58-1.59 1-2.4 1H0v-2h2c.29 0 .8-.2 1-.41l2.17-2.18 1.42 1.42zM16 4V1l4 4-4 4V6h-2c-.29 0-.8.2-1 .41l-2.17 2.18L9.4 7.17 11.6 5c.58-.58 1.59-1 2.41-1h2zm0 10v-3l4 4-4 4v-3h-2c-.82 0-1.83-.42-2.41-1l-8.6-8.59C2.8 6.21 2.3 6 2 6H0V4h2c.82 0 1.83.42 2.41 1l8.6 8.59c.2.2.7.41.99.41h2z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" viewBox="0 0 20 20"><path d="M4 5h3v10H4V5zm12 0v10l-9-5 9-5z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-8 w-8" viewBox="0 0 20 20"><path d="M2.93 17.07A10 10 0 1117.07 2.93 10 10 0 012.93 17.07zm12.73-1.41A8 8 0 104.34 4.34a8 8 0 0011.32 11.32zM7 6l8 4-8 4V6z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" viewBox="0 0 20 20"><path d="M13 5h3v10h-3V5zM4 5l9 5-9 5V5z"/></svg>
          </button>
          <button class="ml-8">
            <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" viewBox="0 0 24 24" width="24" height="24"><path d="M5.41 16H18a2 2 0 002-2 1 1 0 012 0 4 4 0 01-4 4H5.41l2.3 2.3a1 1 0 01-1.42 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 111.42 1.4L5.4 16zM6 8a2 2 0 00-2 2 1 1 0 01-2 0 4 4 0 014-4h12.59l-2.3-2.3a1 1 0 111.42-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.42-1.4L18.6 8H6z"/></svg>
          </button>
        </div>
        <div class="flex mt-3 items-center justify-center">
          <div>1:20</div>
          <div class="bg-gray-500 w-full rounded-lg xl:w-200 h-1 ml-3"></div>
          <div class="ml-3">3:25</div>
        </div>
      </div>
       <div class="volume-controls flex items-center">
        <button>
          <svg class="fill-current text-gray-400 hover:text-white h-6 w-6" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" fill="none"/><path d="M15 6H3v2h12V6zm0 4H3v2h12v-2zM3 16h8v-2H3v2zM17 6v8.18c-.31-.11-.65-.18-1-.18-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3V8h3V6h-5z"/></svg>
        </button>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-5 w-5" width="24" height="24" viewBox="0 0 24 24"><path fill="none" d="M0 0h24v24H0z"/><path d="M3 6h18V4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h4v-2H3V6zm10 6H9v1.78c-.61.55-1 1.33-1 2.22s.39 1.67 1 2.22V20h4v-1.78c.61-.55 1-1.34 1-2.22s-.39-1.67-1-2.22V12zm-2 5.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zM22 8h-6c-.5 0-1 .5-1 1v10c0 .5.5 1 1 1h6c.5 0 1-.5 1-1V9c0-.5-.5-1-1-1zm-1 10h-4v-8h4v8z"/></svg>
        </button>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-5 w-5" width="24" height="24" viewBox="0 0 24 24"><path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3A4.5 4.5 0 0014 7.97v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"/><path d="M0 0h24v24H0z" fill="none"/></svg>
        </button>
        <div class="bg-gray-500 rounded-lg w-20 h-1 ml-3"></div>
        <button class="ml-4">
          <svg class="fill-current text-gray-400 hover:text-white h-4 w-4" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7"/></svg>
        </button>
      </div>
    </div>
  </div>
</template>
<script>
// @ is an alias to /src
export default {
}
</script>
<style lang="scss" >
 .sidebar-spotify::-webkit-scrollbar
  {
    width: 8px;
    background-color: #121212;
  }
  .sidebar-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }
  .content-spotify::-webkit-scrollbar
  {
    width: 8px;
    background-color: #181818;
  }
  .content-spotify::-webkit-scrollbar-thumb {
    border-radius: 8px;
    background-color: #535353;
  }
</style>
