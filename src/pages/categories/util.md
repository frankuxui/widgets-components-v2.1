---
layout: "../../layouts/ExpoLayout.astro"
slug: 'util'
category: 'Util'
tags: ['util']
title: 'Widget components with tailwind CSS - Social'
visible: false
---

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-start justify-between">
		<div class="flex flex-col gap-1">
			<h2 class="font-medium text-lg leading-6"> Summary of financials </h2>
			<p>The best solution for your online payments</p>
		</div>
		<button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
			<svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
			</svg>
		</button>
	</header>
  <div class="relative w-full border-x flex items-start justify-start h-36 dark:border-gray-800 text-gray-500">
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-12 bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs text-black dark:text-white">Jan</span>
        <span class="text-xs text-green-500">2024</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-24 bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Feb</span>
        <span class="text-xs">2023</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[4rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Mar</span>
        <span class="text-xs">2022</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[3rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Apr</span>
        <span class="text-xs">2021</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full flex flex-col justify-center">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[2.5rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">May</span>
        <span class="text-xs">2020</span>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <svg data-icon="heart" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2" width="30" height="30" class="text-rose-600">
    <path fill="none" stroke="currentColor" d="M16.77,3.41A5.73,5.73,0,0,0,12,6,5.73,5.73,0,0,0,1.5,9.14C1.5,17.73,12,20.59,12,20.59S22.5,17.73,22.5,9.14A5.72,5.72,0,0,0,16.77,3.41Z"></path>
    <path fill="none" stroke="currentColor" d="M16.77,7.23a1.9,1.9,0,0,1,1.91,1.91,6.25,6.25,0,0,1-1.95,4.43"></path>
  </svg>
  <h2 class="text-xl leading-6 font-bold bg-gradient-to-r from-rose-500 to-indigo-500 inline-block text-transparent bg-clip-text">Designers convention in Barcelona </h2>
</article>



<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    a
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    a
  </article>
</section>

<article class="border group shadow-sm break-inside rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="grid grid-cols-12 gap-3 p-3">
    <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/women/24.jpg" alt="Avatar">
      </a>
    </div>
    <div class="col-span-10">
      <div class="flex-1 relative">
        <button class="hidden absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full p-1 transition-all hover:bg-gray-200 dark:hover:bg-white/10">
          <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path></svg>
        </button>
        <div class="flex items-center">
          <a class="inline-block font-bold mr-2" href="#">Carmen Ramsey</a>
          <span class="text-xs text-gray-400">3 min ago</span>
        </div>
        <p class="text-xs">
          Dolor sit 😂😂😂 smod
          <br />
          olor sit ame tetur.
        </p>
        <div class="flex items-center">
          <a class="inline-flex items-center py-2 mr-3" href="#">
            <span class="mr-2">
              <svg class="fill-rose-600" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 512 512"><path d="M256 448a32 32 0 01-18-5.57c-78.59-53.35-112.62-89.93-131.39-112.8-40-48.75-59.15-98.8-58.61-153C48.63 114.52 98.46 64 159.08 64c44.08 0 74.61 24.83 92.39 45.51a6 6 0 009.06 0C278.31 88.81 308.84 64 352.92 64c60.62 0 110.45 50.52 111.08 112.64.54 54.21-18.63 104.26-58.61 153-18.77 22.87-52.8 59.45-131.39 112.8a32 32 0 01-18 5.56z"/></svg>
            </span>
            <span class="font-bold">2</span>
          </a>
          <button class="py-1 px-4 font-medium transition-colors duration-300 hover:bg-gray-50 dark:hover:bg-white/10 rounded-md">Repply</button>
        </div>
      </div>
    </div>
  </div>
  <div class="p-2">
    <div class="relative h-[76px] border-2 border-dashed rounded-lg border-rose-200 bg-rose-50 dark:bg-rose-500/15 dark:border-rose-600/30">
      <div class="absolute -left-6 -top-4 rotate-2 grid grid-cols-12 gap-3 p-3 rounded-lg w-full max-w-[290px] shadow-[2px_5px_43px_-4px_#c3005961_,_1px_-1px_3px_-1px_#04000024] bg-white dark:bg-gray-900">
        <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
          <a class="inline-block" href="#">
            <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/men/47.jpg" alt="Avatar">
          </a>
        </div>
        <div class="col-span-10">
          <div class="flex-1 relative">
            <button class="flex absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full w-9 h-9 transition-all bg-rose-200 text-rose-700 hover:bg-rose-300 dark:bg-rose-500/20 dark:text-rose-400 dark:hover:bg-rose-500/30">
              <svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="1.5" width="20" height="20" class="text-current">
                <path class="stroke-current fill-none" d="M16.88,22.5H7.12a1.9,1.9,0,0,1-1.9-1.8L4.36,5.32H19.64L18.78,20.7A1.9,1.9,0,0,1,16.88,22.5Z"></path>
                <line class="stroke-current fill-none" x1="2.45" y1="5.32" x2="21.55" y2="5.32"></line>
                <path class="stroke-current fill-none" d="M10.09,1.5h3.82a1.91,1.91,0,0,1,1.91,1.91V5.32a0,0,0,0,1,0,0H8.18a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,10.09,1.5Z"></path>
                <line class="stroke-current fill-none" x1="12" y1="8.18" x2="12" y2="19.64"></line>
                <line class="stroke-current fill-none" x1="15.82" y1="8.18" x2="15.82" y2="19.64"></line>
                <line class="stroke-current fill-none" x1="8.18" y1="8.18" x2="8.18" y2="19.64"></line>
              </svg>
            </button>
            <div class="flex items-center">
              <a class="inline-block font-bold mr-2" href="#">Stephan Mills</a>
              <span class="text-xs text-gray-400">3 min ago</span>
            </div>
            <p class="text-xs">
              Dolor sit ametei usm odolor
              <br />
              sit amet onse tetur 
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <button class="z-[1] w-9 h-9 absolute top-4 right-4 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 14 4" fill="none">
      <path d="M10.8889 2C10.8889 2.39782 11.0528 2.77936 11.3445 3.06066C11.6362 3.34196 12.0319 3.5 12.4444 3.5C12.857 3.5 13.2527 3.34196 13.5444 3.06066C13.8361 2.77936 14 2.39782 14 2C14 1.60218 13.8361 1.22064 13.5444 0.93934C13.2527 0.658035 12.857 0.5 12.4444 0.5C12.0319 0.5 11.6362 0.658035 11.3445 0.93934C11.0528 1.22064 10.8889 1.60217 10.8889 2ZM5.44444 2C5.44444 2.39782 5.60833 2.77935 5.90006 3.06066C6.19178 3.34196 6.58744 3.5 7 3.5C7.41256 3.5 7.80822 3.34196 8.09994 3.06066C8.39167 2.77935 8.55556 2.39782 8.55556 2C8.55556 1.60217 8.39167 1.22064 8.09994 0.93934C7.80822 0.658035 7.41256 0.499999 7 0.499999C6.58744 0.499999 6.19178 0.658035 5.90006 0.939339C5.60833 1.22064 5.44444 1.60217 5.44444 2ZM-1.31134e-07 2C-1.65913e-07 2.39782 0.163889 2.77935 0.455612 3.06066C0.747335 3.34196 1.143 3.5 1.55556 3.5C1.96811 3.5 2.36378 3.34196 2.6555 3.06066C2.94722 2.77935 3.11111 2.39782 3.11111 2C3.11111 1.60217 2.94722 1.22064 2.6555 0.939339C2.36378 0.658035 1.96811 0.499999 1.55556 0.499999C1.143 0.499999 0.747335 0.658034 0.455612 0.939339C0.163889 1.22064 -9.63552e-08 1.60217 -1.31134e-07 2Z" fill="currentColor"></path>
    </svg>
  </button>
  <header class="p-3 w-full flex items-center text-center justify-center flex-col">
    <img class="flex-none mt-1 w-14 h-14 rounded-full ring-2 ring-pink-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar" loading="lazy">
    <div class="flex flex-col mt-2">
      <a href="#" class="text-base font-semibold block">Jhonathan</a>
      <span class="text-gray-600 dark:text-gray-400">Economist and writer</span>
    </div>
  </header>
  <div class="relative -mt-3 w-full grid grid-cols-7 items-start justify-start h-36 pb-3 dark:border-gray-800 text-gray-500">
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs text-black dark:text-white">Mon</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[6rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Tue</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[2rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Wed</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Thu</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[5rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Fri</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Sat</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full flex flex-col justify-center transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[2.5rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Sun</span>
      </div>
    </div>
  </div>
</article>




