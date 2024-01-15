---
layout: "../../layouts/Layout.astro"
slug: 'weather'
category: 'Weather'
tags: ['weather']
title: 'Widget components with tailwind CSS'
---

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <div class="flex items-center">
    <div class="flex-auto text-center space-y-1">
      <img class="w-8 h-8 m-auto" src="https://www.svgrepo.com/show/402760/sun-behind-cloud.svg">
      <span class="font-bold block text-sm">Mon</span>
    </div>
    <div class="flex-auto text-center space-y-1">
      <img class="w-8 h-8 m-auto" src="https://www.svgrepo.com/show/402760/sun-behind-cloud.svg">
      <span class="font-bold block text-sm">Tue</span>
    </div>
    <div class="flex-auto text-center space-y-1">
      <img class="w-8 h-8 m-auto" src="https://www.svgrepo.com/show/402760/sun-behind-cloud.svg">
      <span class="font-bold block text-sm">Wed</span>
    </div>
    <div class="flex-auto text-center space-y-1">
      <img class="w-8 h-8 m-auto" src="https://www.svgrepo.com/show/400797/sunbehindcloud.svg">
      <span class="font-bold block text-sm">Thu</span>
    </div>
    <div class="flex-auto text-center space-y-1">
      <img class="w-8 h-8 m-auto" src="https://www.svgrepo.com/show/402761/sun-behind-small-cloud.svg">
      <span class="font-bold block text-sm">Fri</span>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <header class="flex items-center justify-between">
    <h2 class="text-lg font-medium">Weather in the area</h2>
    <button class="inline-flex items-center justify-center w-10 h-10 transition-colors duration-200 rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="mt-3">
    <div class="flex flex-col items-center gap-3">
      <div class="flex items-center gap-2">
        <span class="text-3xl font-bold">18°</span>
        <img class="w-10 h-10 object-cover" src="https://www.svgrepo.com/show/452177/cloud.svg" alt="weather">
      </div>
      <div class="text-center w-full text-xs text-gray-500 dark:text-gray-400">
        <p>Despejado - Sensación térmica 18°</p>
        <p>Max 18° - Min 12°</p>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <header class="flex items-center justify-between">
    <h2 class="text-lg font-medium">Weather</h2>
    <button class="inline-flex items-center justify-center w-10 h-10 transition-colors duration-200 rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="mt-3">
    <div class="flex flex-col items-center gap-3">
      <div class="flex items-center gap-2">
        <span class="text-3xl font-bold">22°</span>
        <img class="w-12 h-12 object-cover" src="https://www.svgrepo.com/show/396041/cloud-with-lightning-and-rain.svg" alt="weather">
      </div>
      <div class="text-center w-full text-xs text-gray-500 dark:text-gray-400">
        <p>Lluvia - Sensación térmica 18°</p>
        <p>Max 18° - Min 12°</p>
      </div>
    </div>
  </section>
  <section class="mt-3">
    <div class="flex items-center justify-between gap-2 rounded-lg p-3 bg-gray-50 dark:bg-gray-900">
      <div class="flex flex-col justify-between text-center gap-4">
        <span class="font-medium">18°</span>
        <div class="flex flex-col gap-1 text-xs font-medium">
          <img class="w-8 h-8 object-cover" src="https://www.svgrepo.com/show/396041/cloud-with-lightning-and-rain.svg" alt="weather">
          <span>Ahora</span>
        </div>
      </div>
      <div class="flex flex-col justify-between text-center gap-4">
        <span class="text-gray-500 dark:text-gray-500">17°</span>
        <div class="flex flex-col gap-1 text-xs font-medium">
          <img class="w-8 h-8 object-cover" src="https://www.svgrepo.com/show/396041/cloud-with-lightning-and-rain.svg" alt="weather">
          <span>21</span>
        </div>
      </div>
      <div class="flex flex-col justify-between text-center gap-4">
        <span class="text-gray-500 dark:text-gray-500">14°</span>
        <div class="flex flex-col gap-1 text-xs font-medium">
          <img class="w-8 h-8 object-cover" src="https://www.svgrepo.com/show/396042/cloud-with-rain.svg" alt="weather">
          <span>22</span>
        </div>
      </div>
      <div class="flex flex-col justify-between text-center gap-4">
        <span class="text-gray-500 dark:text-gray-500">12°</span>
        <div class="flex flex-col gap-1 text-xs font-medium">
          <img class="w-8 h-8 object-cover" src="https://www.svgrepo.com/show/396041/cloud-with-lightning-and-rain.svg" alt="weather">
          <span>23</span>
        </div>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <div class="flex items-center gap-3">
    <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://images.pexels.com/photos/2662116/pexels-photo-2662116.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260" alt="avatar">
    <header class="flex-auto">
      <h2 class="text-base font-medium">Mountains</h2>
      <p>423Km, 3 Week</p>
    </header>
  </div>
  <figure class="flex flex-col items-center">
    <img class="w-9 h-9" src="https://www.svgrepo.com/show/279147/cloudy-forecast.svg">
  </figure>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <div class="flex items-center space-x-4">
    <header class="flex-auto">
      <h2 class="text-base font-medium">California</h2>
      <p class="text-gray-500">We'll be there soon</p>
    </header>
  </div>
  <div class="flex items-center gap-2">
    <span class="text-3xl font-bold">24°</span>
    <img class="w-12 h-12 object-cover" src="https://www.svgrepo.com/show/452177/cloud.svg" alt="weather">
  </div>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <header class="flex items-center gap-2">
    <span class="text-3xl font-bold">21°</span>
    <img class="w-12 h-12 object-cover" src="https://www.svgrepo.com/show/452177/cloud.svg" alt="weather">
  </header>
  <div class="flex items-center space-x-4">
    <header class="flex-auto">
      <h2 class="text-base font-medium">Tenerife</h2>
      <p class="text-gray-500">Semana que viene</p>
    </header>
  </div>
</article>

<article class="border shadow-sm break-inside relative overflow-hidden flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <div class="absolute left-0 top-0 w-14 h-14 bg-rose-500/30 blur-2xl"></div>
  <div class="absolute right-0 top-0 w-14 h-14 bg-amber-500/40 blur-2xl"></div>
  <section class="flex items-center gap-2">
    <svg width="54" height="54" id="Layer_1" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
      <path fill="#ff5939" d="M32.35,13.44A21.08,21.08,0,0,0,14.05,45h36.6a21.08,21.08,0,0,0-18.3-31.54Z"/>
      <path fill="currentColor" d="M31.35,4.52V9.35a1,1,0,1,0,2,0V4.52a1,1,0,1,0-2,0Z"/>
      <path fill="currentColor" d="M57.48,33.48a1,1,0,0,0,0,2h4.83a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M2.4,33.48a1,1,0,0,0,0,2H7.23a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M10.46,12.59a1,1,0,0,0,0,1.41l3.42,3.42A1,1,0,0,0,15.3,16l-3.42-3.42A1,1,0,0,0,10.46,12.59Z"/>
      <path fill="currentColor" d="M52.83,12.59,49.41,16a1,1,0,1,0,1.41,1.41L54.25,14a1,1,0,0,0-1.41-1.41Z"/>
      <path fill="currentColor" d="M14.06,46H56.48a1,1,0,0,0,0-2H52.3a22.08,22.08,0,1,0-40-18.61,1,1,0,0,0,1.82.83A20.08,20.08,0,1,1,50.07,44H14.64a20,20,0,0,1-2.37-9.46,20.32,20.32,0,0,1,.25-3.18,1,1,0,0,0-2-.31,22.08,22.08,0,0,0,1.86,13H1.69a1,1,0,1,0,0,2Z"/>
      <path fill="currentColor" d="M62.31,44H60.5a1,1,0,0,0,0,2h1.81a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M40.69,48.65H20.83a1,1,0,0,0,0,2H40.69a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M17.18,48.65H7.87a1,1,0,0,0,0,2h9.31a1,1,0,1,0,0-2Z"/>
      <path fill="currentColor" d="M57.35,52.9H54.83a1,1,0,0,0,0,2h2.52a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M51.65,53.9a1,1,0,0,0-1-1H28.35a1,1,0,0,0,0,2h22.3A1,1,0,0,0,51.65,53.9Z"/>
      <path fill="currentColor" d="M35.45,58.48a1,1,0,0,0,0,2h5.78a1,1,0,0,0,0-2Z"/>
      <path fill="currentColor" d="M33.88,59.48a1,1,0,0,0-1-1h-9.4a1,1,0,0,0,0,2h9.4A1,1,0,0,0,33.88,59.48Z"/>
    </svg>
    <header class="flex-auto">
      <h2 class="text-base font-medium">Spain</h2>
      <p class="text-gray-500">We'll be there soon</p>
    </header>
  </section>
  <button class="inline-flex items-center justify-center w-10 h-10 transition-colors duration-200 rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <section class="flex items-center gap-2">
    <img class="w-10 h-10 object-cover" src="https://www.svgrepo.com/show/227751/windy-wind.svg" alt="weather">
    <header class="flex-auto">
      <h2 class="text-lg font-medium">Weather</h2>
      <p class="text-gray-500">We'll be there soon</p>
    </header>
    <button class="inline-flex items-center justify-center w-8 h-8 transition-colors duration-200 rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <circle cx="12" cy="12" r="1"></circle>
        <circle cx="12" cy="5" r="1"></circle>
        <circle cx="12" cy="19" r="1"></circle>
      </svg>
    </button>
  </section>
  <section class="mt-3 flex items-center gap-2">
    <p class="text-xs text-gray-500">Lluvia - Sensación térmica 18° - Max 18° - Min 12°</p>
    <button class="inline-flex text-sm font-medium flex-none items-center justify-center px-3 h-8 transition-colors duration-200 rounded text-white bg-indigo-600 hover:bg-indigo-800 dark:hover:bg-indigo-700">
      View more
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside relative overflow-hidden flex flex-col rounded-xl p-4 mb-3 text-sm bg-gray-900 text-white border-transparent" data-filter="weather">
  <div class="absolute right-0 top-0 w-14 h-14 bg-lime-500/40 blur-2xl"></div>
  <section class="relative flex items-start justify-between gap-2 w-full">
    <header class="flex flex-col">
      <h2 class="text-lg font-medium">Mi ubicación</h2>
      <p class="text-gray-300">Salou</p>
    </header>
    <span class="text-3xl font-medium">21°</span>
  </section>
  <section class="relative mt-3 flex items-center gap-4">
    <p class="text-xs leading-4 text-gray-300">Lluvia - Sensación térmica 18° - Max 18° - Min 12°</p>
    <button class="inline-flex text-xs uppercase font-medium flex-none items-center justify-center px-3 h-8 transition-colors duration-200 rounded-full text-white bg-emerald-600 hover:bg-emerald-700">
      View more
    </button>
  </section>
</article>

