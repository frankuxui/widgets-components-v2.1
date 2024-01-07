---
layout: "../../layouts/Layout.astro"
slug: 'social'
category: 'Social'
tags: ['social']
title: 'Widget components with tailwind CSS'
---

<section class="grid grid-cols-2 gap-4" data-filter="social">
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <header>
      <svg width="26" height="26" viewBox="0 0 512 512"><path d="M384 240H96V136a40.12 40.12 0 0140-40h240a40.12 40.12 0 0140 40v104zM48 416V304a64.19 64.19 0 0164-64h288a64.19 64.19 0 0164 64v112" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><path d="M48 416v-8a24.07 24.07 0 0124-24h368a24.07 24.07 0 0124 24v8M112 240v-16a32.09 32.09 0 0132-32h80a32.09 32.09 0 0132 32v16M256 240v-16a32.09 32.09 0 0132-32h80a32.09 32.09 0 0132 32v16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
    </header>
    <section>
      <h2 class="text-base font-medium">Bed time</h2>
      <h3 class="text-lg font-semibold">10:00 PM</h3>
    </section>
    <p class="text-xs text-gray-500">Set your bedtime and wake up time...</p>
  </article>
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <header>
      <svg width="26" height="26" viewBox="0 0 512 512"><path d="M427.68 351.43C402 320 383.87 304 383.87 217.35 383.87 138 343.35 109.73 310 96c-4.43-1.82-8.6-6-9.95-10.55C294.2 65.54 277.8 48 256 48s-38.21 17.55-44 37.47c-1.35 4.6-5.52 8.71-9.95 10.53-33.39 13.75-73.87 41.92-73.87 121.35C128.13 304 110 320 84.32 351.43 73.68 364.45 83 384 101.61 384h308.88c18.51 0 27.77-19.61 17.19-32.57zM320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
    </header>
    <section>
      <h2 class="text-base font-medium">Wake up</h2>
      <h3 class="text-lg font-semibold">6:00 AM</h3>
    </section>
    <p class="text-xs text-gray-500">Set your bedtime and wake up time...</p>
  </article>
</section>

<section class="grid grid-cols-12 gap-3" data-filter="social">
  <article class="relative col-span-7 border break-inside overflow-hidden rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="absolute z-0 top-4 right-4 w-16 h-16 bg-blue-500/30 blur-2xl" ></div>
    <header class="relative w-full">
      <div class="flex flex-col">
        <img class="flex-none w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/men/20.jpg" alt="avatar">
        <div class="mt-2">
          <h2 class="font-semibold text-base">Hendrik</h2>
          <p class="text-gray-500">Software Developer</p>
        </div>
      </div>
      <button class="z-[1] w-10 h-10 absolute top-0 right-0 flex items-center justify-center rounded-full">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 14 4" fill="none">
          <path d="M10.8889 2C10.8889 2.39782 11.0528 2.77936 11.3445 3.06066C11.6362 3.34196 12.0319 3.5 12.4444 3.5C12.857 3.5 13.2527 3.34196 13.5444 3.06066C13.8361 2.77936 14 2.39782 14 2C14 1.60218 13.8361 1.22064 13.5444 0.93934C13.2527 0.658035 12.857 0.5 12.4444 0.5C12.0319 0.5 11.6362 0.658035 11.3445 0.93934C11.0528 1.22064 10.8889 1.60217 10.8889 2ZM5.44444 2C5.44444 2.39782 5.60833 2.77935 5.90006 3.06066C6.19178 3.34196 6.58744 3.5 7 3.5C7.41256 3.5 7.80822 3.34196 8.09994 3.06066C8.39167 2.77935 8.55556 2.39782 8.55556 2C8.55556 1.60217 8.39167 1.22064 8.09994 0.93934C7.80822 0.658035 7.41256 0.499999 7 0.499999C6.58744 0.499999 6.19178 0.658035 5.90006 0.939339C5.60833 1.22064 5.44444 1.60217 5.44444 2ZM-1.31134e-07 2C-1.65913e-07 2.39782 0.163889 2.77935 0.455612 3.06066C0.747335 3.34196 1.143 3.5 1.55556 3.5C1.96811 3.5 2.36378 3.34196 2.6555 3.06066C2.94722 2.77935 3.11111 2.39782 3.11111 2C3.11111 1.60217 2.94722 1.22064 2.6555 0.939339C2.36378 0.658035 1.96811 0.499999 1.55556 0.499999C1.143 0.499999 0.747335 0.658034 0.455612 0.939339C0.163889 1.22064 -9.63552e-08 1.60217 -1.31134e-07 2Z" fill="black"/>
        </svg>
      </button>
    </header>
    <section class="w-full mt-2">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 111 71" fill="none">
        <path d="M0 39.4873C0 37.2782 1.79086 35.4873 4 35.4873H14C16.2091 35.4873 18 37.2782 18 39.4873V69.8646H0V39.4873Z" fill="#DCDCDC"/>
        <path d="M23 24.2974C23 22.0882 24.7909 20.2974 27 20.2974H37C39.2091 20.2974 41 22.0882 41 24.2974V69.8646H23V24.2974Z" fill="#DCDCDC"/>
        <path d="M46 50.6797C46 48.4705 47.7909 46.6797 50 46.6797H60C62.2091 46.6797 64 48.4705 64 50.6797V69.8644H46V50.6797Z" fill="#DCDCDC"/>
        <path d="M69 4.31055C69 2.10141 70.7909 0.310547 73 0.310547H84C86.2091 0.310547 88 2.10141 88 4.31055V70.1553H69V4.31055Z" fill="#36BAFD"/>
        <path d="M93 15.5757C93 13.3665 94.7909 11.5757 97 11.5757H107C109.209 11.5757 111 13.3665 111 15.5757V70.1551H93V15.5757Z" fill="#DCDCDC"/>
      </svg>
    </section>
  </article>
  <section class="grid grid-cols-1 col-span-5">
    <article class="border break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
      aa
    </article>
    <article class="border break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
      aa
    </article>
  </section>
</section>

<article class="border shadow-md break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center gap-3">
    <span class="text-base font-medium">01</span>
    <div class="flex items-center gap-4">
      <img class="flex-none w-12 h-12 rounded-2xl" src="https://randomuser.me/api/portraits/women/21.jpg" alt="avatar">
      <div class="flex-auto">
        <span class="text-sm text-gray-600 dark:text-gray-300">September 2023</span>
        <h2 class="text-base font-semibold block">Caroline</h2>
      </div>
    </div>
  </header>
  <svg width="22" height="22" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" class="fill-gray-600 dark:fill-gray-100">
    <path clip-rule="evenodd" fill-rule="evenodd" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12Zm13.36-1.814a.75.75 0 1 0-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 0 0-1.06 1.06l2.25 2.25a.75.75 0 0 0 1.14-.094l3.75-5.25Z"></path>
  </svg>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center gap-4">
    <div class="flex-none w-12 h-12 rounded-full flex items-center justify-center font-medium text-lg text-amber-700 bg-amber-200">AB</div>
    <div class="flex-auto">
      <h2 class="text-base font-medium block">Annette Black</h2>
      <p class="text-xs text-gray-600 dark:text-gray-300">Hi there! I'm a designer and developer from San Francisco.</p>
    </div>
  </header>
  <section class="flex flex-col items-center justify-between h-full gap-3">
    <span class="text-xs font-medium text-gray-600 dark:text-gray-300">Today</span>
    <span class="flex flex-none items-center justify-center font-medium w-5 h-5 text-xs rounded-full transition-colors bg-rose-500 text-white"> 2 </span>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center gap-4">
    <img class="flex-none rounded-full w-12 h-12" src="https://randomuser.me/api/portraits/men/76.jpg" alt="avatar">
    <div class="flex-auto">
      <h2 class="text-base font-medium block">Philip Johnson</h2>
      <p class="text-xs text-gray-600 dark:text-gray-300">Hi there! I'm a dog trainer from Oakland.</p>
    </div>
  </header>
  <section class="flex flex-col items-center justify-between h-full gap-3">
    <span class="text-xs font-medium text-gray-600 dark:text-gray-300">Today</span>
    <button class="flex flex-none items-center justify-center font-medium w-8 h-8 text-xs rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900 text-gray-600 dark:text-gray-500">
      <svg width="18" height="18" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M11.294 0.983997L15.016 4.706C15.2153 4.90534 15.3634 5.14986 15.4479 5.41876C15.5324 5.68766 15.5506 5.97299 15.5012 6.25046C15.4517 6.52794 15.3359 6.78936 15.1637 7.01249C14.9915 7.23561 14.7679 7.41383 14.512 7.532L13.185 8.145C12.7616 8.3409 12.388 8.63018 12.0924 8.99112C11.7967 9.35205 11.5867 9.77527 11.478 10.229L10.894 12.683C10.577 14.015 8.922 14.483 7.954 13.515L5.75 11.311L1.78 15.28C1.7104 15.3496 1.62777 15.4048 1.53683 15.4425C1.44589 15.4801 1.34843 15.4995 1.25 15.4995C1.15157 15.4995 1.0541 15.4801 0.963165 15.4425C0.872227 15.4048 0.789599 15.3496 0.719999 15.28C0.650398 15.2104 0.595188 15.1278 0.55752 15.0368C0.519853 14.9459 0.500465 14.8484 0.500465 14.75C0.500465 14.6516 0.519853 14.5541 0.55752 14.4632C0.595188 14.3722 0.650398 14.2896 0.719999 14.22L4.689 10.25L2.485 8.046C1.517 7.078 1.985 5.423 3.317 5.106L5.771 4.522C6.22499 4.41394 6.64849 4.20413 7.00952 3.90842C7.37054 3.6127 7.65965 3.23882 7.855 2.815L8.468 1.488C8.58616 1.23211 8.76439 1.00854 8.98751 0.836323C9.21063 0.664104 9.47205 0.548328 9.74953 0.498841C10.027 0.449354 10.3123 0.467622 10.5812 0.552091C10.8501 0.63656 11.0947 0.78473 11.294 0.983997ZM6.283 9.723L9.015 12.454C9.04646 12.4855 9.08574 12.5079 9.1288 12.5192C9.17185 12.5304 9.21711 12.5299 9.25992 12.5177C9.30272 12.5056 9.34151 12.4823 9.37229 12.4502C9.40307 12.418 9.42472 12.3783 9.435 12.335L10.019 9.881C10.1801 9.20638 10.4921 8.57709 10.9315 8.04048C11.371 7.50387 11.9264 7.07392 12.556 6.783L13.884 6.17C13.9206 6.15313 13.9526 6.12766 13.9772 6.09576C14.0019 6.06387 14.0184 6.02648 14.0255 5.9868C14.0326 5.94712 14.03 5.90632 14.0178 5.86787C14.0057 5.82942 13.9845 5.79447 13.956 5.766L10.234 2.044C10.2055 2.01547 10.1706 1.99425 10.1321 1.98215C10.0937 1.97004 10.0529 1.96742 10.0132 1.97449C9.97351 1.98156 9.93613 1.99812 9.90423 2.02276C9.87233 2.0474 9.84686 2.07939 9.83 2.116L9.217 3.444C8.9262 4.0737 8.49629 4.6292 7.95966 5.06865C7.42303 5.50811 6.79367 5.82005 6.119 5.981L3.665 6.565C3.62171 6.57528 3.58196 6.59693 3.54983 6.6277C3.51771 6.65848 3.49438 6.69727 3.48225 6.74008C3.47012 6.78288 3.46964 6.82814 3.48084 6.8712C3.49205 6.91425 3.51454 6.95354 3.546 6.985L6.277 9.717L6.283 9.723Z" fill="currentColor"/>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <img class="flex-none w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/44.jpg" alt="avatar">
    <div class="flex-auto">
      <a href="#" class="text-base font-semibold block">Yolanda</a>
      <span class="text-sm text-gray-600 dark:text-gray-300">Web Development</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-10 h-10 rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6 12 3.269 3.125A59.769 59.769 0 0 1 21.485 12 59.768 59.768 0 0 1 3.27 20.875L5.999 12Zm0 0h7.5"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <figure class="relative w-12 h-12">
      <img class="flex-none w-full rounded-full" src="https://randomuser.me/api/portraits/men/14.jpg" alt="avatar">
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Frederisck</a>
      <span class="text-sm text-gray-600 dark:text-gray-300">Industrial Designer</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-12 h-12 rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg fill="none" stroke-width="1.5" width="28" height="28" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.827 6.175A2.31 2.31 0 0 1 5.186 7.23c-.38.054-.757.112-1.134.175C2.999 7.58 2.25 8.507 2.25 9.574V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18V9.574c0-1.067-.75-1.994-1.802-2.169a47.865 47.865 0 0 0-1.134-.175 2.31 2.31 0 0 1-1.64-1.055l-.822-1.316a2.192 2.192 0 0 0-1.736-1.039 48.774 48.774 0 0 0-5.232 0 2.192 2.192 0 0 0-1.736 1.039l-.821 1.316Z"></path>
      <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 12.75a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0ZM18.75 10.5h.008v.008h-.008V10.5Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <img class="flex-none w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/81.jpg" alt="avatar">
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Marina Flick</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">Technical Director</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="24" height="24" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm relative break-inside rounded-xl overflow-hidden p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute top-0 left-1/2 w-12 h-12 bg-rose-500/30 blur-2xl"></div>
  <section class="relative z-[1] flex items-center justify-between">
    <div class="flex items-center gap-4">
      <a href="#">
        <img class="flex-none w-12 h-12 rounded-full ring-2 ring-pink-500 border-2 border-white dark:border-gray-700" src="https://randomuser.me/api/portraits/men/82.jpg" alt="avatar">
      </a>
      <div class="flex-auto">
        <a href="#" class="font-medium block">Jhonathan Doe</a>
        <span class="text-sm text-gray-600 dark:text-gray-400">Web Developer</span>
      </div>
    </div>
    <button class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-200 hover:bg-rose-100 dark:hover:bg-gray-900 text-rose-600">
      <svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <a href="#">
      <img class="flex-none w-12 h-12 rounded-full ring-2 ring-indigo-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar">
    </a>
    <div class="flex-auto">
      <a href="#" class="flex items-center font-medium gap-1">
        <span>Anthony</span>
        <svg width="16" height="16" class="text-blue-600" viewBox="0 0 512 512"><path d="M256 48C141.31 48 48 141.31 48 256s93.31 208 208 208 208-93.31 208-208S370.69 48 256 48zm108.25 138.29l-134.4 160a16 16 0 01-12 5.71h-.27a16 16 0 01-11.89-5.3l-57.6-64a16 16 0 1123.78-21.4l45.29 50.32 122.59-145.91a16 16 0 0124.5 20.58z" fill="currentColor"/></svg>
      </a>
      <span class="text-sm text-gray-600 dark:text-gray-400">Tester &amp; Developer</span>
    </div>
  </div>
  <span class="px-2 py-1 flex items-center justify-center uppercase text-xs rounded-sm bg-indigo-600 text-white">NEW</span>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <a href="#" class="flex items-center gap-4">
    <img class="flex-none w-12 h-12 rounded-full ring-1 ring-gray-300 border-2 border-white dark:border-gray-950 dark:ring-gray-400" src="https://randomuser.me/api/portraits/men/85.jpg" alt="avatar">
    <div class="flex-auto">
      <h2 class="font-semibold block">Alexander</h2>
      <span class="text-xs text-gray-600 dark:text-gray-400">Last seen 2 hours ago</span>
    </div>
  </a>
  <button class="flex flex-none items-center justify-center w-10 h-10 transition-all rounded-full p-1 hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 512 512"><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="44" d="M358.62 129.28L86.49 402.08 70 442l39.92-16.49 272.8-272.13-24.1-24.1zM413.07 74.84l-11.79 11.78 24.1 24.1 11.79-11.79a16.51 16.51 0 000-23.34l-.75-.75a16.51 16.51 0 00-23.35 0z"/></svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-col justify-between rounded-xl py-3 mb-3 text-sm divide-y dark:divide-gray-900 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between px-4 pb-3">
    <h2 class="font-medium text-lg">Details</h2>
    <button class="flex flex-none items-center justify-center w-8 h-8 transition-all rounded-full p-1 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="32" height="32" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" fill="currentColor"></path>
      </svg>
    </button>
  </header>
  <section class="flex justify-between items-center px-4 pt-3">
    <div class="flex items-center gap-4">
      <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/60.jpg" alt="avatar">
      <div class="flex-col items-start flex-auto">
        <a href="#" class="text-base font-medium block">Marc Jacobs</a>
        <span class="text-sm text-gray-600 dark:text-gray-400">Doctor</span>
      </div>
    </div>
    <div class="flex items-center gap-2 text-gray-600 dark:text-gray-400">
      <svg width="20" height="20" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 20C16.4 20 20 16.4 20 12S16.4 4 12 4 4 7.6 4 12 7.6 20 12 20M12 2C17.5 2 22 6.5 22 12S17.5 22 12 22C6.5 22 2 17.5 2 12C2 6.5 6.5 2 12 2M12.5 13H11L7 10.7L7.8 9.4L11.1 11.3V7H12.6V13Z" fill="currentColor"></path>
      </svg>
      <span class="font-medium">3 min</span>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex justify-between flex-col p-4 mb-3 text-sm gap-4 rounded-lg bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-start items-center gap-3">
    <figure class="relative w-12 h-12 flex-none">
      <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/men/65.jpg" alt="avatar">
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-cyan-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <h2 class="font-medium text-base">
      Improve large organization
      <br />
      onboarding
    </h2>
  </div>
  <div class="flex justify-between items-center gap-2">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z"></path>
      </svg>
      <span>24</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z"></path>
      </svg>
      <span>6</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <span>12</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
      </svg>
      <span>6</span>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside flex justify-between divide-y dark:divide-gray-900 flex-col p-4 mb-3 text-sm gap-4 rounded-lg bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-start items-start gap-3">
    <figure class="relative w-12 h-12 flex-none">
      <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/men/71.jpg" alt="avatar">
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <section class="ml-2">
      <h2 class="flex items-center gap-1 font-medium text-base text-blue-700 dark:text-white">
        <span>Frank Ocean</span>
        <svg width="16" height="16" class="ionicon" viewBox="0 0 512 512"><path d="M256 48C141.31 48 48 141.31 48 256s93.31 208 208 208 208-93.31 208-208S370.69 48 256 48zm108.25 138.29l-134.4 160a16 16 0 01-12 5.71h-.27a16 16 0 01-11.89-5.3l-57.6-64a16 16 0 1123.78-21.4l45.29 50.32 122.59-145.91a16 16 0 0124.5 20.58z" fill="currentColor"/></svg>
      </h2>
      <p class="text-gray-600 dark:text-gray-400">
        I'm a singer-songwriter and
        <br />
        rapper from New Orleans...
      </p>
    </section>
  </div>
  <div class="flex justify-between items-center gap-2 pt-4">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-cyan-200 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z"></path>
      </svg>
      <span>9</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-green-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z"></path>
      </svg>
      <span>32</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-amber-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <span>66</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-rose-100 dark:bg-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
      </svg>
      <span>24</span>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside flex justify-between flex-col py-3 mb-3 text-sm rounded-lg divide-y dark:divide-gray-900 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between px-4 pb-3">
    <h2 class="flex items-center gap-2 font-medium text-base">
      <span class="px-2 py-0.5 flex items-center justify-center uppercase text-xs rounded-sm bg-indigo-500 text-white">NEW</span>
      <span>Header</span>
    </h2>
    <button class="flex flex-none items-center justify-center w-8 h-8 transition-all rounded-full p-1 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="32" height="32" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" fill="currentColor"></path>
      </svg>
    </button>
  </header>
  <section class="flex justify-start items-center gap-3 p-4">
    <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/67.jpg" alt="avatar">
    <h2 class="text-sm font-medium">Improve large organization onboarding</h2>
  </section>
  <div class="flex justify-between items-center gap-2 px-4 pt-3">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z"></path>
      </svg>
      <span>24</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z"></path>
      </svg>
      <span>6</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <span>12</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
      </svg>
      <span>6</span>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <section class="flex items-center gap-4">
    <figure class="flex justify-center items-center bg-gray-100 dark:bg-gray-900 w-10 h-10 rounded-full">
      <svg width="22" height="22" viewBox="0 0 24 24">
        <path fill="currentColor" d="M21.7 13.35L20.7 14.35L18.65 12.35L19.65 11.35C19.85 11.14 20.19 11.13 20.42 11.35L21.7 12.63C21.89 12.83 21.89 13.15 21.7 13.35M12 18.94V21H14.06L20.12 14.88L18.07 12.88L12 18.94M5 19H10V21H5C3.9 21 3 20.11 3 19V5C3 3.9 3.9 3 5 3H6V1H8V3H16V1H18V3H19C20.11 3 21 3.9 21 5V9H5V19M5 5V7H19V5H5Z"></path>
      </svg>
    </figure>
    <header class="flex flex-col flex-auto">
      <span class="text-xs text-gray-400 dark:text-gray-400">SCHEDULE DATE</span>
      <a href="#" class="text-sm font-medium block">Sat 24, September</a>
    </header>
  </section>
  <button class="inline-block hover:bg-gray-100 transition-all rounded-full p-1 dark:hover:bg-gray-900">
    <svg width="28" height="28" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" fill="currentColor"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-start gap-4">
    <img class="flex-none mt-1 w-12 h-12 rounded-full ring-2 ring-emerald-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar">
    <div class="flex flex-col gap-1">
      <a href="#" class="font-medium text-base">Anderson</a>
      <ul class="flex items-center flex-wrap gap-2">
        <li class="flex px-2 py-0.5 text-xs rounded-sm items-center justify-center bg-green-200 text-green-700 dark:bg-green-500/30 dark:text-green-400">UX/UI</li>
        <li class="flex px-2 py-0.5 text-xs rounded-sm items-center justify-center bg-green-200 text-green-700 dark:bg-green-500/30 dark:text-green-400">Javascript</li>
        <li class="flex px-2 py-0.5 text-xs rounded-sm items-center justify-center bg-green-200 text-green-700 dark:bg-green-500/30 dark:text-green-400">React</li>
      </ul>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between">
    <div class="flex flex-col items-start justify-center">
      <a href="#" class="text-base font-semibold block">Create header here</a>
      <span class="text-gray-600 dark:text-gray-400">Engineering</span>
    </div>
    <button class="rounded-full flex items-center justify-center w-10 h-10 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="34" height="34" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="flex items-center justify-between mt-5">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <span class="flex items-center justify-center font-semibold w-9 h-9 rounded-full bg-indigo-200 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950">AT</span>
        </a>
      </dd>
    </div>
    <button class="flex items-center justify-center cursor-pointer rounded-md h-7 px-3 text-sm bg-indigo-600 text-white">View all</button>
  </section>
</article>

<article class="border shadow-sm flex flex-col break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-between items-center">
    <div class="block">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/48.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/15.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/37.jpg" alt="avatar">
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-9 h-9 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/78.jpg" alt="avatar">
        </a>
      </dd>
    </div>
    <div class="flex justify-center items-center rounded-md px-2 py-1 bg-green-100 gap-1 font-medium dark:bg-green-500/20">
      <span class="text-sm font-medium text-green-700 dark:text-green-400">23%</span>
      <svg width="15" height="15" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1.57835 7.65466H14.1787C14.3063 7.6544 14.4313 7.6309 14.5404 7.5867C14.6495 7.5425 14.7384 7.47927 14.7977 7.40382C14.8569 7.32837 14.8842 7.24356 14.8767 7.15851C14.8692 7.07346 14.827 6.9914 14.7548 6.92115L8.45465 0.84365C8.19354 0.591667 7.56492 0.591667 7.30311 0.84365L1.00293 6.92115C0.93001 6.99125 0.887245 7.07336 0.879287 7.15855C0.871328 7.24374 0.898481 7.32876 0.957793 7.40437C1.01711 7.47997 1.10631 7.54328 1.21572 7.58741C1.32512 7.63154 1.45054 7.6548 1.57835 7.65466Z" fill="currentColor" class="fill-green-500 dark:fill-green-400"></path>
      </svg>
    </div>
    <button class="inline-flex items-center justify-center w-10 h-10 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="34" height="34" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </div>
</article>



<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img class="flex-none w-16 object-cover" src="https://randomuser.me/api/portraits/women/45.jpg" alt="avatar">
  <div class="flex-auto">
    <a href="#" class="text-base font-semibold block">Adrianne</a>
    <span class="text-gray-600 dark:text-gray-400">Frontend Development</span>
  </div>
</article>

<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <img class="flex-none w-16 object-cover" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar">
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Matheus Duarte</a>
      <span class="text-gray-600 dark:text-gray-400">Art Director</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <div class="flex items-center justify-center w-16 h-16 font-semibold text-lg bg-purple-100 dark:bg-purple-600/50">
      CM
    </div>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Carolina Melo</a>
      <span class="text-gray-600 dark:text-gray-400">UX/UI Designer</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl overflow-hidden py-4 mb-3 gap-4 text-sm divide-y dark:divide-gray-800 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex justify-between items-center px-4">
    <button type="button" class="h-8 px-4 font-medium text-base transition-colors duration-200 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">September</button>
    <div class="flex justify-center items-center">
      <button class="flex h-7 w-7 items-center justify-center transition-colors duration-200 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">
        <svg width="24" height="24" viewBox="0 0 24 24">
          <path fill="currentColor" d="M15.41,16.58L10.83,12L15.41,7.41L14,6L8,12L14,18L15.41,16.58Z"></path>
        </svg>
      </button>
      <button class="flex h-7 w-7 items-center justify-center transition-colors duration-200 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">
        <svg width="24" height="24" viewBox="0 0 24 24">
          <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z"></path>
        </svg>
      </button>
    </div>
  </header>
  <section class="flex items-center gap-1 pt-4 px-4">
    <button class="flex items-center justify-center h-7 w-7 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">
      <svg width="28" height="28" viewBox="0 0 24 24">
        <path fill="currentColor" d="M15.41,16.58L10.83,12L15.41,7.41L14,6L8,12L14,18L15.41,16.58Z"></path>
      </svg>
    </button>
    <button class="flex-auto text-center rounded-md p-1 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="font-semibold block">2021</span>
    </button>
    <button class="flex-auto text-center rounded-md p-1 transition-colors duration-200 hover:bg-rose-600 bg-rose-500 text-white dark:text-white dark:hover:bg-rose-600">
      <span class="font-semibold block">2022</span>
    </button>
    <button class="flex-auto text-center rounded-md p-1 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="font-semibold block">2023</span>
    </button>
    <button class="flex-auto text-center rounded-md p-1 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="font-semibold block">2024</span>
    </button>
    <button class="flex items-center justify-center h-7 w-7 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">
      <svg width="28" height="28" viewBox="0 0 24 24">
        <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pl-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <button class="flex-none rounded-full flex items-center justify-center w-10 h-10 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="34" height="34" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <div class="flex-auto text-right">
      <a href="#" class="text-base font-semibold block">Leandro</a>
      <span class="text-gray-600 dark:text-gray-400">Software Engineer</span>
    </div>
    <img class="flex-none w-16 object-cover" src="https://randomuser.me/api/portraits/men/46.jpg" alt="avatar">
  </header>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1">
    <p class="text-sm"> All your notifications are well turned on </p>
  </header>
  <div class="border h-6 rounded-sm border-gray-300 dark:border-gray-900"></div>
  <section class="flex items-center justify-center gap-1">
    <button class="flex flex-none items-center justify-center w-10 h-10 rounded-full hover:bg-gray-100 transition-colors duration-200 dark:hover:bg-gray-900">
      <svg width="24" height="24" class="ionicon" viewBox="0 0 512 512">
        <path d="M427.68 351.43C402 320 383.87 304 383.87 217.35 383.87 138 343.35 109.73 310 96c-4.43-1.82-8.6-6-9.95-10.55C294.2 65.54 277.8 48 256 48s-38.21 17.55-44 37.47c-1.35 4.6-5.52 8.71-9.95 10.53-33.39 13.75-73.87 41.92-73.87 121.35C128.13 304 110 320 84.32 351.43 73.68 364.45 83 384 101.61 384h308.88c18.51 0 27.77-19.61 17.19-32.57zM320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
      </svg>
    </button>
    <span class="bg-black flex items-center justify-center rounded-xl w-6 h-6 text-white dark:bg-white dark:text-black">3</span>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1">
    <p class="text-sm">All your notifications are well turned off</p>
  </header>
  <div class="border h-6 rounded-sm border-gray-300 dark:border-gray-900"></div>
  <section class="flex items-center justify-center gap-1">
    <button class="flex flex-none items-center justify-center w-10 h-10 rounded-full hover:bg-gray-100 transition-colors duration-200 dark:hover:bg-gray-900">
      <svg width="24" height="24" class="ionicon" viewBox="0 0 512 512">
        <path d="M128.51 204.59q-.37 6.15-.37 12.76C128.14 304 110 320 84.33 351.43 73.69 364.45 83 384 101.62 384H320M414.5 335.3c-18.48-23.45-30.62-47.05-30.62-118 0-79.3-40.52-107.57-73.88-121.3-4.43-1.82-8.6-6-9.95-10.55C294.21 65.54 277.82 48 256 48s-38.2 17.55-44 37.47c-1.35 4.6-5.52 8.71-10 10.53a149.57 149.57 0 00-18 8.79M320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
        <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-miterlimit="10" stroke-width="32" d="M448 448L64 64"/>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <section class="flex items-center gap-4">
    <figure class="flex-none w-12 h-12 rounded-lg flex items-center justify-center text-lg font-semibold bg-amber-200 text-amber-500 dark:bg-amber-600/50 dark:text-white">
      <svg width="24" height="24" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M9.53 16.122a3 3 0 0 0-5.78 1.128 2.25 2.25 0 0 1-2.4 2.245 4.5 4.5 0 0 0 8.4-2.245c0-.399-.078-.78-.22-1.128Zm0 0a15.998 15.998 0 0 0 3.388-1.62m-5.043-.025a15.994 15.994 0 0 1 1.622-3.395m3.42 3.42a15.995 15.995 0 0 0 4.764-4.648l3.876-5.814a1.151 1.151 0 0 0-1.597-1.597L14.146 6.32a15.996 15.996 0 0 0-4.649 4.763m3.42 3.42a6.776 6.776 0 0 0-3.42-3.42"></path>
      </svg>
    </figure>
    <header class="flex-auto">
      <a href="#" class="text-base font-medium block">Ilustration design</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">
        The best design
      </span>
    </header>
  </section>
  <button class="rounded-full flex items-center justify-center w-9 h-9 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24">
      <path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" fill="currentColor"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <div class="flex-none w-12 h-12 rounded-lg flex items-center justify-center text-lg font-semibold bg-rose-100 text-rose-400 dark:bg-rose-600/50 dark:text-white">
      <svg width="28" height="28" class="ionicon" viewBox="0 0 512 512">
        <path d="M430.11 347.9c-6.6-6.1-16.3-7.6-24.6-9-11.5-1.9-15.9-4-22.6-10-14.3-12.7-14.3-31.1 0-43.8l30.3-26.9c46.4-41 46.4-108.2 0-149.2-34.2-30.1-80.1-45-127.8-45-55.7 0-113.9 20.3-158.8 60.1-83.5 73.8-83.5 194.7 0 268.5 41.5 36.7 97.5 55 152.9 55.4h1.7c55.4 0 110-17.9 148.8-52.4 14.4-12.7 11.99-36.6.1-47.7z" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32"/>
        <circle fill="currentColor" cx="144" cy="208" r="32"/>
        <circle fill="currentColor" cx="152" cy="311" r="32"/>
        <circle fill="currentColor" cx="224" cy="144" r="32"/>
        <circle fill="currentColor" cx="256" cy="367" r="48"/>
        <circle fill="currentColor" cx="328" cy="144" r="32"/>
      </svg>
    </div>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Palette design</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">
        This is the best palette
      </span>
    </div>
  </div>
  <button class="rounded-full flex items-center justify-center w-9 h-9 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24">
      <path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" fill="currentColor"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <div class="relative flex-none w-11 h-11 rounded-full flex items-center justify-center text-base font-semibold bg-blue-200 text-blue-500 dark:bg-blue-600/50 dark:text-white">
      LK
      <span class="absolute bottom-0 right-0 w-3 h-3 rounded-full bg-red-500 border-2 border-white dark:border-gray-900"></span>
    </div>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Leonard Krasner</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">
        Marketing
      </span>
    </div>
  </div>
  <button class="rounded-full flex items-center justify-center h-8 px-3 text-xs font-medium uppercase transition-colors border hover:bg-gray-100 dark:hover:bg-gray-900 dark:border-gray-800">
    Follow
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <div class="relative flex-none w-11 h-11 rounded-full flex items-center justify-center text-base font-semibold bg-green-200 text-green-600 dark:bg-green-600/50 dark:text-white">
      JM
      <span class="absolute flex items-center justify-center -bottom-1 -right-1 w-5 h-5 rounded-full bg-purple-200 border-2 text-purple-600 border-white dark:border-gray-900 dark:bg-white">
        <svg width="10" height="10" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="m11.645 20.91-.007-.003-.022-.012a15.247 15.247 0 0 1-.383-.218 25.18 25.18 0 0 1-4.244-3.17C4.688 15.36 2.25 12.174 2.25 8.25 2.25 5.322 4.714 3 7.688 3A5.5 5.5 0 0 1 12 5.052 5.5 5.5 0 0 1 16.313 3c2.973 0 5.437 2.322 5.437 5.25 0 3.925-2.438 7.111-4.739 9.256a25.175 25.175 0 0 1-4.244 3.17 15.247 15.247 0 0 1-.383.219l-.022.012-.007.004-.003.001a.752.752 0 0 1-.704 0l-.003-.001Z"></path>
        </svg>
      </span>
    </div>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Joshua M. Young</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">
        Data scientist
      </span>
    </div>
  </div>
  <button class="rounded-full flex items-center justify-center h-10 w-10 transition-colors hover:bg-gray-100 dark:hover:bg-gray-900 ">
    <svg width="20" height="20" class="ionicon" viewBox="0 0 512 512">
      <path d="M376 144c-3.92 52.87-44 96-88 96s-84.15-43.12-88-96c-4-55 35-96 88-96s92 42 88 96z" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="50"/>
      <path d="M288 304c-87 0-175.3 48-191.64 138.6-2 10.92 4.21 21.4 15.65 21.4H464c11.44 0 17.62-10.48 15.65-21.4C463.3 352 375 304 288 304z" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="50"/>
      <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="50" d="M88 176v112M144 232H32"/></svg>
  </button>
</article>

<section class="grid grid-cols-3 gap-3" data-filter="social">
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Favorite</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Bookmark</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="m2.25 12 8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"></path>
    </svg>
    <h2 class="font-medium text-sm">Home</h2>
  </article>
</section>

<section class="grid grid-cols-3 gap-3" data-filter="social">
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" >
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Phone</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"></path>
    </svg>
    <h2 class="font-medium text-sm">Mail</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M12 20.25c4.97 0 9-3.694 9-8.25s-4.03-8.25-9-8.25S3 7.444 3 12c0 2.104.859 4.023 2.273 5.48.432.447.74 1.04.586 1.641a4.483 4.483 0 0 1-.923 1.785A5.969 5.969 0 0 0 6 21c1.282 0 2.47-.402 3.445-1.087.81.22 1.668.337 2.555.337Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Chat</h2>
  </article>
</section>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-6 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="grid gap-1">
    <h2 class="font-medium text-base">Maintenance</h2>
    <p class="text-xs opacity-90">Friday, February 10, 2023</p>
  </header>
  <button type="button" class="inline-flex h-8 shrink-0 items-center justify-center rounded-md border bg-transparent px-3 text-sm font-medium dark:border-gray-900">Undo</button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-start gap-2">
    <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/45.jpg" alt="avatar">
    <div class="flex-auto">
      <div class="flex items-center space-x-1">
        <a href="#" class="text-base font-medium">Esther Howard</a>
        <span class="fill-gray-800 dark:fill-white">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="16" height="16">
            <path fill="fill-blue-500" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z"></path>
          </svg>
        </span>
      </div>
      <div class="flex items-center gap-2">
        <p class="text-xs text-gray-600 dark:text-gray-400">
          Hi, I've been calling you and your
          <br />
          phone doesn't ring...
        </p>
      </div>
    </div>
  </div>
  <div class="flex flex-col items-center gap-2 text-xs">
    <span class="mt-[1px] text-gray-500 dark:text-gray-400">Now</span>
    <span class="flex items-center justify-center rounded-full w-5 h-5 font-mniudm bg-violet-600 text-white dark:bg-white">2</span>
  </div>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <div class="flex-none w-12 h-12 rounded-full flex items-center justify-center text-base font-semibold bg-gradient-to-br from-yellow-500 to-rose-500 text-white">
      <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M4.098 19.902a3.75 3.75 0 0 0 5.304 0l6.401-6.402M6.75 21A3.75 3.75 0 0 1 3 17.25V4.125C3 3.504 3.504 3 4.125 3h5.25c.621 0 1.125.504 1.125 1.125v4.072M6.75 21a3.75 3.75 0 0 0 3.75-3.75V8.197M6.75 21h13.125c.621 0 1.125-.504 1.125-1.125v-5.25c0-.621-.504-1.125-1.125-1.125h-4.072M10.5 8.197l2.88-2.88c.438-.439 1.15-.439 1.59 0l3.712 3.713c.44.44.44 1.152 0 1.59l-2.879 2.88M6.75 17.25h.008v.008H6.75v-.008Z"></path>
      </svg>
    </div>
    <div class="flex-auto">
      <p class="text-sm text-gray-600 dark:text-gray-400"> 3 days ago</p>
      <h2 class="text-base font-medium block">UX/UI Design</h2>
    </div>
  </div>
  <button class="rounded-full flex items-center justify-center h-9 w-9 transition-colors hover:bg-gray-100 dark:hover:bg-gray-900 ">
    <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5ZM12 12.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5ZM12 18.75a.75.75 0 1 1 0-1.5.75.75 0 0 1 0 1.5Z"></path>
    </svg>
  </button>
</article>

<article class="break-inside relative overflow-hidden flex flex-col justify-between space-y-2 text-sm rounded-xl p-4 mb-3 bg-gray-900 text-white" data-filter="social">
  <header class="flex items-center justify-between">
    <span class="uppercase text-xs text-gray-100">upgrade team</span>
    <span class="text-xs font-medium rounded-sm flex items-center justify-center px-1 h-5 text-black bg-yellow-500">NEW</span>
  </header>
  <div class="flex flex-row items-center space-x-3">
    <svg width="58" height="56" viewBox="0 0 52 50" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M32.6458 38.4379C33.9918 37.1198 33.2655 34.0922 31.0668 30.5948C31.8658 30.4707 32.6129 30.281 33.178 29.9905C35.2112 28.9466 36.584 27.044 37.6232 25.0759C38.7403 22.9647 39.49 20.644 40.9477 18.7215C41.1939 18.3966 41.44 18.1052 41.6853 17.831C44.8304 18.206 47.3412 18.8784 47.3412 18.8784L48.3006 16.4534C47.0896 16.0212 45.848 15.6791 44.586 15.4302C45.3591 14.9931 45.8635 14.8569 45.8635 14.8569L44.9543 12.4121C43.4966 13.025 42.3136 13.9293 41.323 15.0121C37.6206 14.806 33.8921 15.5397 30.9506 17.8086C28.7389 19.5155 27.2447 21.8819 25.839 24.2491C24.5935 23.0333 23.2671 21.9023 21.8688 20.8638C22.134 20.4302 22.4182 20.0405 22.7242 19.7397C24.5728 17.9293 27.0116 16.7716 28.6115 14.7C31.9742 10.35 29.5146 3.53103 26.7481 0C26.2524 0.475 25.4325 1.16724 24.8155 1.71379C27.7561 4.70948 29.8127 9.95431 27.5082 13.8733C26.2203 16.0638 23.8404 17.4379 22.1764 19.3198C21.8887 19.6466 21.6313 20.0603 21.3982 20.5172C17.0466 17.4129 13.053 16.1638 11.4704 17.7138C11.3133 17.8737 11.1838 18.0584 11.0874 18.2603L11.0813 18.2543L11.0388 18.3776C10.9799 18.5112 10.9261 18.65 10.8897 18.8017L0 50L31.774 38.95L31.7653 38.9414C32.1068 38.8319 32.4075 38.6707 32.6458 38.4379ZM6.32065 45.9759L3.66863 44.7465L5.45831 39.6172L13.6666 43.4207L6.32065 45.9759ZM21.0116 40.8664L7.24972 34.4879L9.0394 29.3595L19.3233 34.494C13.1847 30.5198 10.8291 24.2293 10.8291 24.2293L11.441 22.4767C12.5286 25.2138 14.9215 28.6224 18.2097 31.8397C21.5256 35.0862 25.0399 37.4379 27.8488 38.4888L21.0116 40.8664ZM26.2975 24.7112C27.7344 22.6621 29.2156 20.594 31.2748 19.1224C33.2352 17.7207 36.4176 17.4647 39.4345 17.6328C38.4153 19.4034 37.6622 21.3681 36.9861 23.2552C36.1689 25.5397 35.0734 27.9086 32.9847 29.3095C32.4214 29.6871 31.6318 29.9629 30.7886 30.1672C29.6298 28.4009 28.1097 26.5336 26.2975 24.7112Z" fill="white"></path>
      <path d="M18.2287 16.3793C19.0971 16.3793 16.4937 13.7931 16.9287 11.525C18.5962 11.3974 22.4078 12.1448 20.1892 9.11379C22.699 9.55345 23.9991 7.68966 21.6296 5.92328C22.4182 5.97845 23.6437 4.49914 22.764 4.31207C19.9456 3.7181 18.8423 5.23448 20.6312 7.42155C18.7505 7.07328 17.2173 7.9431 18.63 9.89655C13.1994 9.22328 16.2891 16.3793 18.2287 16.3793ZM36.8726 14.081C37.6864 13.7155 36.3058 11.3009 35.8569 10.6836C39.2915 10.3181 39.1615 9.3 37.0078 7.11897C42.8631 7.31466 37.1889 4.00431 37.9846 2.69397C38.6736 1.55776 40.7874 2.74914 40.5915 2.11638C39.9311 0 33.6668 1.43103 37.631 5.38276C34.1712 5.45 33.8393 6.575 36.4176 8.9069C31.9265 8.95603 35.5908 14.6552 36.8726 14.081ZM51.7378 22.6078C50.3667 22.9897 50.1553 22.8466 50.3381 24.2043C47.1713 22.7543 43.8207 20.7379 45.854 26.0802C42.2573 23.95 42.4367 25.8155 41.7641 28.8853C40.8888 28.2069 39.6451 26.419 39.6451 26.419L38.3278 27.5319C38.3278 27.5319 40.7414 30.9181 41.9331 30.7259C42.9809 30.5578 43.5512 28.5879 43.6093 26.8517C46.946 28.2526 48.5432 28.4397 47.017 24.3431C49.6846 25.8336 52.9555 27.1483 51.7378 22.6078ZM3.50916 7.27328L5.96011 9.71207L3.50916 12.15L1.05734 9.71207L3.50916 7.27328ZM24.1005 26.5181L21.6478 28.956L19.1959 26.5164L21.6486 24.0776L24.1005 26.5181ZM13.1908 3.44828L15.6417 5.88621L13.1899 8.32586L10.7389 5.88621L13.1908 3.44828ZM39.8765 37.4862L37.4238 35.0474L39.8748 32.6078L42.3275 35.0466L39.8765 37.4862ZM34.4113 45.85L31.9603 43.4121L34.4113 40.9733L36.8631 43.4121L34.4113 45.85ZM45.1649 47.7759L42.7123 45.3371L45.1623 42.8974L47.615 45.3362L45.1649 47.7759ZM47.6159 36.669L45.1649 34.2302L47.6159 31.7922L50.0668 34.2302L47.6159 36.669ZM43.5243 6.03448L45.9753 8.47241L43.5235 10.9112L41.0725 8.47241L43.5243 6.03448Z" fill="white"></path>
    </svg>
    <span class="text-base font-normal">Congratulations, your team has been upgraded</span>
  </div>
  <div class="flex justify-between items-center">
    <span class="text-gray-400">September 10, 2023</span>
    <button class="flex items-center justify-center text-sm font-medium rounded-full px-3 h-8 space-x-1 bg-white text-black group">
      <span>Next</span>
      <svg xmlns="http://www.w3.org/2000/svg" class="transition-all duration-200 group-hover:translate-x-1" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="M5 12h13M12 5l7 7-7 7"></path>
      </svg>
    </button>
  </div>
</article>