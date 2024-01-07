---
layout: "../../layouts/Layout.astro"
slug: 'multimedia'
category: 'Multimedia'
tags: ['multimedia']
title: 'Widget components with tailwind CSS'
---

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <img class="flex-none col-span-4 h-full object-cover" src="https://images.pexels.com/photos/343701/pexels-photo-343701.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" alt="avatar">
  <section class="col-span-8 flex justify-between flex-col p-3">
    <header class="flex flex-row justify-between items-start">
      <span class="font-medium text-base"> Pirates of the caribbean </span>
      <div class="flex justify-center items-center gap-2">
        <svg viewBox="0 0 24 24" class="-mt-0.5" width="18" height="18">
          <path fill="#ff00ea" d="M12,17.27L18.18,21L16.54,13.97L22,9.24L14.81,8.62L12,2L9.19,8.62L2,9.24L7.45,13.97L5.82,21L12,17.27Z"></path>
        </svg>
        <span class="font-medium">4.95</span>
      </div>
    </header>
    <p class="text-xs text-gray-600 dark:text-gray-400">2022 · Action · Runtime · 2h 5m</p>
  </section>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <figure class="col-span-5 relative">
    <div class="absolute left-4 bottom-4 rounded-sm text-xs py-1 px-2 text-white bg-black/60 backdrop-blur-sm">April, 2018</div>
    <img src="https://images.pexels.com/photos/5152572/pexels-photo-5152572.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" alt="Imagen" class="w-full min-h-[7rem] object-cover">
  </figure>
  <section class="col-span-7 flex flex-col justify-between p-3 flex-1">
    <h2 class="text-base font-medium leading-5">Comme un Boomerang</h2>
    <div class="flex flex-row justify-between items-center space-x-2">
      <p class="flex-1 text-xs leading-4">Justine Forever - feder and Therapie</p>
      <button class="flex flex-none items-center justify-center rounded-full w-8 h-8 bg-yellow-400 text-black">
        <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" fill="currentColor"></path>
        </svg>
      </button>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside relative flex items-center justify-between overflow-hidden rounded-t-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <div class="flex items-center justify-center w-12 h-12 rounded-full text-lg bg-blue-700 text-white">02</div>
  <header class="flex-auto flex flex-col">
    <span class="text-xs text-gray-600">Clubbed to death</span>
    <h2 class="font-bold block text-base">
      <a href="#">Robert D.</a>
    </h2>
  </header>
  <button class="w-9 h-9 flex flex-none justify-center items-center rounded-full transition-all duration-200 bg-white dark:bg-gray-900 border text-black dark:border-gray-800 dark:text-white hover:bg-gray-100 dark:hover:bg-gray-800">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="18" height="18">
      <path fill-rule="evenodd" d="M4.5 5.653c0-1.426 1.529-2.33 2.779-1.643l11.54 6.348c1.295.712 1.295 2.573 0 3.285L7.28 19.991c-1.25.687-2.779-.217-2.779-1.643V5.653z" clip-rule="evenodd"></path>
    </svg>
  </button>
  <div class="absolute bottom-0 left-0 w-full rounded-full overflow-hidden bg-gray-100 h-[3px] whitespace-nowrap dark:bg-gray-900">
    <div class="bg-blue-700 h-full w-4/6">
      <span class="sr-only">33%</span>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <div class="col-span-3">
    <img src="https://images.pexels.com/photos/462510/pexels-photo-462510.jpeg?auto=compress&cs=tinysrgb&w=1600" alt="Imagen" class="w-full h-full aspect-square object-cover">
  </div>
  <div class="col-span-9 flex items-center justify-between p-3 flex-1">
    <header class="flex flex-col gap-1">
      <h2 class="text-base font-semibold leading-5">The Weeknd</h2>
      <p>Take My Breath Offi...</p>
    </header>
    <button class="flex flex-none justify-center items-center rounded-full w-9 h-9 transition-color duration-200 bg-indigo-500 hover:bg-indigo-700 text-white">
      <svg width="18" height="18" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path d="M6.3 2.84A1.5 1.5 0 0 0 4 4.11v11.78a1.5 1.5 0 0 0 2.3 1.27l9.344-5.891a1.5 1.5 0 0 0 0-2.538L6.3 2.841Z"></path>
      </svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <div class="col-span-4">
    <img src="https://images.pexels.com/photos/7022370/pexels-photo-7022370.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Imagen" class="w-full h-full aspect-square object-cover">
  </div>
  <div class="col-span-8 flex items-center justify-between p-3 flex-1">
    <header class="flex flex-col gap-1">
      <h2 class="text-base font-semibold leading-5">Massive</h2>
      <p>Mat cipher, Freakpass and Nik...</p>
    </header>
    <button class="flex flex-none justify-center items-center rounded-full w-9 h-9 transition-color duration-200 bg-gray-800 hover:bg-gray-700 text-white">
      <svg width="18" height="18" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path d="M6.3 2.84A1.5 1.5 0 0 0 4 4.11v11.78a1.5 1.5 0 0 0 2.3 1.27l9.344-5.891a1.5 1.5 0 0 0 0-2.538L6.3 2.841Z"></path>
      </svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <figure class="col-span-3">
    <div class="flex items-center justify-center flex-col w-full h-full p-3 bg-gray-900 text-white dark:bg-gray-200 dark:text-black">
      <span>Ene</span>
      <span class="text-3xl font-semibold">12</span>
    </div>
  </figure>
  <section class="col-span-9 flex items-center justify-between p-3 flex-1">
    <header class="flex flex-col">
      <p class="text-xs text-gray-500">Concert in the park</p>
      <h2 class="text-sm font-semibold leading-5">Massive</h2>
      <p>Jueves 12 de enero de 2022</p>
    </header>
  </section>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <figure class="col-span-4">
    <img src="https://images.pexels.com/photos/733767/pexels-photo-733767.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Imagen" class="w-full h-full aspect-square object-cover">
  </figure>
  <section class="col-span-8 flex flex-col items-start p-3 flex-1 gap-2">
    <header class="flex items-start justify-between">
      <h2 class="text-base font-semibold leading-5">Deep house music</h2>
      <div class="flex justify-center items-center gap-2">
        <svg viewBox="0 0 24 24" class="-mt-0.5 text-rose-500" width="18" height="18">
          <path fill="currentColor" d="M12,17.27L18.18,21L16.54,13.97L22,9.24L14.81,8.62L12,2L9.19,8.62L2,9.24L7.45,13.97L5.82,21L12,17.27Z"></path>
        </svg>
        <span class="font-medium">4.95</span>
      </div>
    </header>
    <p class="text-xs text-gray-600">This song is a remix of the original song...</p>
    <div class="w-full rounded-full overflow-hidden bg-gray-100 h-[3px] whitespace-nowrap dark:bg-gray-900">
      <div class="bg-blue-700 h-full w-4/6">
        <span class="sr-only">33%</span>
      </div>
    </div>
  </section>
</article>

<section class="grid grid-cols-2 gap-3" data-filter="multimedia">
  <article class="border shadow-sm break-inside flex items-center flex-col justify-between rounded-xl mb-3 text-sm gap-4 p-4 bg-gradient-to-t from-rose-500 to-pink-600 text-white dark:border-gray-900">
    <svg width="45" height="45" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="m9 9 10.5-3m0 6.553v3.75a2.25 2.25 0 0 1-1.632 2.163l-1.32.377a1.803 1.803 0 1 1-.99-3.467l2.31-.66a2.25 2.25 0 0 0 1.632-2.163Zm0 0V2.25L9 5.25v10.303m0 0v3.75a2.25 2.25 0 0 1-1.632 2.163l-1.32.377a1.803 1.803 0 0 1-.99-3.467l2.31-.66A2.25 2.25 0 0 0 9 15.553Z"></path>
    </svg>
    <h2 class="text-base text-center">Play your favorite songs</h2>
    <button class="px-2 w-full h-8 rounded-full font-medium transition-colors duration-200 bg-white text-black hover:bg-gray-200">Try now</button>
  </article>
  <article class="border shadow-sm break-inside flex items-center flex-col justify-between rounded-xl overflow-hidden mb-3 text-sm bg-gradient-to-r from-purple-600 to-indigo-600 text-white dark:border-gray-900">
    <img src="https://images.pexels.com/photos/9008803/pexels-photo-9008803.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" class="object-cover w-full h-full" alt="cover">
    <div class="flex flex-col items-start w-full p-4 gap-1">
      <h2>Sultans Of Swing</h2>
      <span class="text-xs">Dire Straits</span>
    </div>
  </article>
</section>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  a
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  a
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  a
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="multimedia">
  <div class="flex items-center justify-between w-full">
    <div class="flex items-center space-x-3">
      <div class="relative overflow-hidden rounded-md">
        <div class="absolute left-0 top-0 w-full h-full flex items-center justify-center text-white bg-black/40">
          <button class="w-8 h-8 flex items-center justify-center">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" width="20" height="20">
              <path fill-rule="evenodd" d="M6.75 5.25a.75.75 0 01.75-.75H9a.75.75 0 01.75.75v13.5a.75.75 0 01-.75.75H7.5a.75.75 0 01-.75-.75V5.25zm7.5 0A.75.75 0 0115 4.5h1.5a.75.75 0 01.75.75v13.5a.75.75 0 01-.75.75H15a.75.75 0 01-.75-.75V5.25z" clip-rule="evenodd"></path>
            </svg>
          </button>
        </div>
        <img src="https://images.pexels.com/photos/9980327/pexels-photo-9980327.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" alt="Cover" class="object-cover w-11 h-11">
      </div>
      <div class="flex flex-col">
        <h5 class="text-base font-medium">You Don't Know</h5>
        <p class="text-slate-500 dark:text-slate-400">Sonique</p>
      </div>
    </div>
    <div class="flex items-center space-x-1">
      <button class="flex flex-none items-center justify-center rounded-full p-1 text-rose-500">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" stroke-width="2" width="20" height="20">
          <path d="M11.645 20.91l-.007-.003-.022-.012a15.247 15.247 0 01-.383-.218 25.18 25.18 0 01-4.244-3.17C4.688 15.36 2.25 12.174 2.25 8.25 2.25 5.322 4.714 3 7.688 3A5.5 5.5 0 0112 5.052 5.5 5.5 0 0116.313 3c2.973 0 5.437 2.322 5.437 5.25 0 3.925-2.438 7.111-4.739 9.256a25.175 25.175 0 01-4.244 3.17 15.247 15.247 0 01-.383.219l-.022.012-.007.004-.003.001a.752.752 0 01-.704 0l-.003-.001z"></path>
        </svg>
      </button>
      <button class="flex flex-none items-center justify-center rounded-full w-8 h-8 transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="1"></circle>
          <circle cx="12" cy="5" r="1"></circle>
          <circle cx="12" cy="19" r="1"></circle>
        </svg>
      </button>
    </div>
  </div>
</article>

<section class="grid grid-cols-2 gap-3" data-filter="multimedia">
  <article class="border flex flex-col items-center justify-between overflow-hidden text-sm bg-white text-black dark:bg-gray-900 dark:text-white rounded-xl mb-4 dark:border-gray-900">
    <div class="relative">
      <button class="absolute right-2 top-2 flex items-center justify-center rounded-full p-1 transition-colors duration-200 bg-white text-black">
        <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path>
        </svg>
      </button>
      <button class="flex items-center justify-center absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 rounded-full w-10 h-10 transition-colors duration-200 bg-[#000000c1] hover:bg-black">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <polygon points="5 3 19 12 5 21 5 3"></polygon>
        </svg>
      </button>
      <img src="https://images.pexels.com/photos/185030/pexels-photo-185030.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" class="object-cover" alt="cover">
    </div>
    <div class="flex flex-col items-start w-full p-4 space-y-2">
      <header>
        <h2 class="font-medium">You Don't Know</h2>
        <span class="text-xs">Smoove &amp; Turell</span>
      </header>
      <button class="flex items-center justify-center text-xs rounded-full px-2 py-1 space-x-1 bg-black text-white dark:bg-white dark:text-black">
        <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="14" height="14"><path fill="currentColor" d="M12.152 6.896c-.948 0-2.415-1.078-3.96-1.04-2.04.027-3.91 1.183-4.961 3.014-2.117 3.675-.546 9.103 1.519 12.09 1.013 1.454 2.208 3.09 3.792 3.039 1.52-.065 2.09-.987 3.935-.987 1.831 0 2.35.987 3.96.948 1.637-.026 2.676-1.48 3.676-2.948 1.156-1.688 1.636-3.325 1.662-3.415-.039-.013-3.182-1.221-3.22-4.857-.026-3.04 2.48-4.494 2.597-4.559-1.429-2.09-3.623-2.324-4.39-2.376-2-.156-3.675 1.09-4.61 1.09zM15.53 3.83c.843-1.012 1.4-2.427 1.245-3.83-1.207.052-2.662.805-3.532 1.818-.78.896-1.454 2.338-1.273 3.714 1.338.104 2.715-.688 3.559-1.701"></path>
        </svg>
        <span>Music</span>
      </button>
    </div>
  </article>
  <article class="border flex flex-col items-center justify-between overflow-hidden text-sm bg-emerald-600 text-white rounded-xl mb-4 dark:border-gray-900">
    <div class="relative">
      <button class="absolute right-2 top-2 flex items-center justify-center hover:bg-white hover:text-black rounded-full p-1 transition-colors duration-200">
        <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path>
        </svg>
      </button>
      <button class="flex items-center justify-center absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 rounded-full w-10 h-10 transition-colors duration-200 bg-[#000000c1] hover:bg-black">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#ffffff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <polygon points="5 3 19 12 5 21 5 3"></polygon>
        </svg>
      </button>
      <img src="https://images.pexels.com/photos/144428/pexels-photo-144428.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1260&amp;h=750&amp;dpr=2" class="object-cover" alt="cover">
    </div>
    <div class="flex flex-col items-start w-full p-4 space-y-2">
      <header>
        <h2 class="font-medium">Why did you do it</h2>
        <span class="text-xs">Stretch</span>
      </header>
      <button class="flex items-center justify-center text-xs rounded-full px-2 py-1 space-x-1 bg-white text-black">
        <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="14" height="14">
          <path fill="currentColor" d="M12.152 6.896c-.948 0-2.415-1.078-3.96-1.04-2.04.027-3.91 1.183-4.961 3.014-2.117 3.675-.546 9.103 1.519 12.09 1.013 1.454 2.208 3.09 3.792 3.039 1.52-.065 2.09-.987 3.935-.987 1.831 0 2.35.987 3.96.948 1.637-.026 2.676-1.48 3.676-2.948 1.156-1.688 1.636-3.325 1.662-3.415-.039-.013-3.182-1.221-3.22-4.857-.026-3.04 2.48-4.494 2.597-4.559-1.429-2.09-3.623-2.324-4.39-2.376-2-.156-3.675 1.09-4.61 1.09zM15.53 3.83c.843-1.012 1.4-2.427 1.245-3.83-1.207.052-2.662.805-3.532 1.818-.78.896-1.454 2.338-1.273 3.714 1.338.104 2.715-.688 3.559-1.701"></path>
        </svg>
        <span>Music</span>
      </button>
    </div>
  </article>
</section>