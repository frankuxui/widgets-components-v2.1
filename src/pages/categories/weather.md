---
layout: "../../layouts/Layout.astro"
slug: 'weather'
category: 'Weather'
tags: ['weather']
title: 'Widget components with tailwind CSS'
visible: false
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
  <button class="relative z-[1] inline-flex items-center justify-center w-9 h-9 transition-colors duration-200 rounded-full hover:bg-black/5 dark:hover:bg-white/10">
    <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<section class="grid grid-cols-4 gap-3" data-filter="weather">
  <article class="border shadow-sm break-inside flex flex-col items-center gap-2 rounded-xl p-3 mb-3 text-sm  bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <h2 class="text-sm font-bold">22:00</h2>
    <img class="w-9 h-9 object-cover" src="https://cdn0.iconfinder.com/data/icons/weather-filled-outline-6/64/weather_cloud_sun_moon_rain-09-1024.png" alt="weather">
    <p class="text-black/80">18°</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center gap-2 rounded-xl p-3 mb-3 text-sm border-rose-500 bg-rose-500 text-white">
    <h2 class="text-sm font-bold">22:00</h2>
      <img class="w-9 h-9 object-cover" src="https://www.svgrepo.com/show/227744/snowing-frost.svg" alt="weather">
      <p class="text-white/80">18°</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center gap-2 rounded-xl p-3 mb-3 text-sm  bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <h2 class="text-sm font-bold">22:00</h2>
    <img class="w-9 h-9 object-cover" src="https://cdn0.iconfinder.com/data/icons/weather-filled-outline-6/64/weather_cloud_sun_moon_rain-22-1024.png" alt="weather">
    <p class="text-black/80">18°</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center gap-2 rounded-xl p-3 mb-3 text-sm  bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <h2 class="text-sm font-bold">22:00</h2>
    <img class="w-9 h-9 object-cover" src="https://cdn0.iconfinder.com/data/icons/weather-filled-outline-6/64/weather_cloud_sun_moon_rain-16-1024.png" alt="weather">
    <p class="text-black/80">18°</p>
  </article>
</section>

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

<section class="grid grid-cols-3 gap-3" data-filter="weather">
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M4,10A1,1 0 0,1 3,9A1,1 0 0,1 4,8H12A2,2 0 0,0 14,6A2,2 0 0,0 12,4C11.45,4 10.95,4.22 10.59,4.59C10.2,5 9.56,5 9.17,4.59C8.78,4.2 8.78,3.56 9.17,3.17C9.9,2.45 10.9,2 12,2A4,4 0 0,1 16,6A4,4 0 0,1 12,10H4M19,12A1,1 0 0,0 20,11A1,1 0 0,0 19,10C18.72,10 18.47,10.11 18.29,10.29C17.9,10.68 17.27,10.68 16.88,10.29C16.5,9.9 16.5,9.27 16.88,8.88C17.42,8.34 18.17,8 19,8A3,3 0 0,1 22,11A3,3 0 0,1 19,14H5A1,1 0 0,1 4,13A1,1 0 0,1 5,12H19M18,18H4A1,1 0 0,1 3,17A1,1 0 0,1 4,16H18A3,3 0 0,1 21,19A3,3 0 0,1 18,22C17.17,22 16.42,21.66 15.88,21.12C15.5,20.73 15.5,20.1 15.88,19.71C16.27,19.32 16.9,19.32 17.29,19.71C17.47,19.89 17.72,20 18,20A1,1 0 0,0 19,19A1,1 0 0,0 18,18Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Wind</h2>
    <p class="text-xs text-gray-500">12km/h</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,3.77L11.25,4.61C11.25,4.61 9.97,6.06 8.68,7.94C7.39,9.82 6,12.07 6,14.23A6,6 0 0,0 12,20.23A6,6 0 0,0 18,14.23C18,12.07 16.61,9.82 15.32,7.94C14.03,6.06 12.75,4.61 12.75,4.61L12,3.77M12,6.9C12.44,7.42 12.84,7.85 13.68,9.07C14.89,10.83 16,13.07 16,14.23C16,16.45 14.22,18.23 12,18.23C9.78,18.23 8,16.45 8,14.23C8,13.07 9.11,10.83 10.32,9.07C11.16,7.85 11.56,7.42 12,6.9Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Pressure</h2>
    <p class="text-xs text-gray-500">1020hPa</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,3.77L11.25,4.61C11.25,4.61 9.97,6.06 8.68,7.94C7.39,9.82 6,12.07 6,14.23A6,6 0 0,0 12,20.23A6,6 0 0,0 18,14.23C18,12.07 16.61,9.82 15.32,7.94C14.03,6.06 12.75,4.61 12.75,4.61L12,3.77M12,6.9C12.44,7.42 12.84,7.85 13.68,9.07C14.89,10.83 16,13.07 16,14.23C16,16.45 14.22,18.23 12,18.23C9.78,18.23 8,16.45 8,14.23C8,13.07 9.11,10.83 10.32,9.07C11.16,7.85 11.56,7.42 12,6.9Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Humidity</h2>
    <p class="text-xs text-gray-500">60%</p>
  </article>
</section>

<section class="grid grid-cols-3 gap-3" data-filter="weather">
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm border-transparent text-white bg-gradient-to-r from-violet-600 to-indigo-600">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M4,10A1,1 0 0,1 3,9A1,1 0 0,1 4,8H12A2,2 0 0,0 14,6A2,2 0 0,0 12,4C11.45,4 10.95,4.22 10.59,4.59C10.2,5 9.56,5 9.17,4.59C8.78,4.2 8.78,3.56 9.17,3.17C9.9,2.45 10.9,2 12,2A4,4 0 0,1 16,6A4,4 0 0,1 12,10H4M19,12A1,1 0 0,0 20,11A1,1 0 0,0 19,10C18.72,10 18.47,10.11 18.29,10.29C17.9,10.68 17.27,10.68 16.88,10.29C16.5,9.9 16.5,9.27 16.88,8.88C17.42,8.34 18.17,8 19,8A3,3 0 0,1 22,11A3,3 0 0,1 19,14H5A1,1 0 0,1 4,13A1,1 0 0,1 5,12H19M18,18H4A1,1 0 0,1 3,17A1,1 0 0,1 4,16H18A3,3 0 0,1 21,19A3,3 0 0,1 18,22C17.17,22 16.42,21.66 15.88,21.12C15.5,20.73 15.5,20.1 15.88,19.71C16.27,19.32 16.9,19.32 17.29,19.71C17.47,19.89 17.72,20 18,20A1,1 0 0,0 19,19A1,1 0 0,0 18,18Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Wind</h2>
    <p class="text-xs text-white/80">12km/h</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm border-transparent text-white bg-gradient-to-r from-red-500 to-orange-500">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,3.77L11.25,4.61C11.25,4.61 9.97,6.06 8.68,7.94C7.39,9.82 6,12.07 6,14.23A6,6 0 0,0 12,20.23A6,6 0 0,0 18,14.23C18,12.07 16.61,9.82 15.32,7.94C14.03,6.06 12.75,4.61 12.75,4.61L12,3.77M12,6.9C12.44,7.42 12.84,7.85 13.68,9.07C14.89,10.83 16,13.07 16,14.23C16,16.45 14.22,18.23 12,18.23C9.78,18.23 8,16.45 8,14.23C8,13.07 9.11,10.83 10.32,9.07C11.16,7.85 11.56,7.42 12,6.9Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Pressure</h2>
    <p class="text-xs text-white/80">1020hPa</p>
  </article>
  <article class="border shadow-sm break-inside flex flex-col gap-1 rounded-xl p-4 mb-3 text-sm border-transparent text-white bg-gradient-to-r from-fuchsia-500 to-cyan-500">
    <svg width="22" height="22" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,3.77L11.25,4.61C11.25,4.61 9.97,6.06 8.68,7.94C7.39,9.82 6,12.07 6,14.23A6,6 0 0,0 12,20.23A6,6 0 0,0 18,14.23C18,12.07 16.61,9.82 15.32,7.94C14.03,6.06 12.75,4.61 12.75,4.61L12,3.77M12,6.9C12.44,7.42 12.84,7.85 13.68,9.07C14.89,10.83 16,13.07 16,14.23C16,16.45 14.22,18.23 12,18.23C9.78,18.23 8,16.45 8,14.23C8,13.07 9.11,10.83 10.32,9.07C11.16,7.85 11.56,7.42 12,6.9Z" fill="currentColor" /></svg>
    <h2 class="text-sm font-bold">Humidity</h2>
    <p class="text-xs text-white/80">60%</p>
  </article>
</section>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <div class="flex items-center gap-2 w-full">
    <div class="flex flex-col items-center justify-between flex-1 text-center gap-4">
      <div class="flex flex-col items-center justify-center">
        <img class="w-8 h-8 object-cover" src="https://cdn3.iconfinder.com/data/icons/weather-free-2/32/Weather_Free_Outline_day-cloud-weather-cloudy-sky-512.png" alt="weather">
        <span class="mt-1 text-[11px] text-gray-500">05:00 AM</span>
        <span class="mt-1 text-lg font-medium">18°</span>
      </div>
    </div>
    <div class="flex flex-col items-center justify-between flex-1 text-center gap-4">
      <div class="flex flex-col items-center justify-center">
        <img class="w-8 h-8 object-cover" src="https://cdn3.iconfinder.com/data/icons/weather-free-2/32/Weather_Free_Outline_cloud-thunder-rain-weather-512.png" alt="weather">
        <span class="mt-1 text-[11px] text-gray-500">06:00 AM</span>
        <span class="mt-1 text-lg font-medium">17°</span>
      </div>
    </div>
    <div class="flex flex-col items-center justify-between flex-1 text-center gap-4">
      <div class="flex flex-col items-center justify-center">
        <img class="w-8 h-8 object-cover" src="https://cdn2.iconfinder.com/data/icons/weather-74/24/weather-05-512.png" alt="weather">
        <span class="mt-1 text-[11px] text-gray-500">07:00 AM</span>
        <span class="mt-1 text-lg font-medium">14°</span>
      </div>
    </div>
    <div class="flex flex-col items-center justify-between flex-1 text-center gap-4">
      <div class="flex flex-col items-center justify-center">
        <img class="w-8 h-8 object-cover" src="https://cdn2.iconfinder.com/data/icons/weather-74/24/weather-09-1024.png" alt="weather">
        <span class="mt-1 text-[11px] text-gray-500">08:00 AM</span>
        <span class="mt-1 text-lg font-medium">12°</span>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  <header class="w-full flex items-start justify-between">
    <div class="">
      <h2 class="text-lg font-medium">Calidad del aire</h2>
      <p class="text-sm text-gray-500">Salou, Tarragona</p>
    </div>
    <button class="relative z-[1] inline-flex items-center justify-center w-9 h-9 transition-colors duration-200 rounded-full hover:bg-black/5 dark:hover:bg-white/10">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="flex flex-col gap-1 mt-3">
    <div 
      class="h-1 rounded w-full"
      style="background-image: linear-gradient(90deg, rgba(65,0,163,1) 0%, rgba(0,26,116,1) 12%, rgba(0,43,181,1) 29%, rgba(0,49,193,1) 46%, rgba(0,169,182,1) 73%, rgba(0,218,157,1) 100%);"
    >
    </div>
    <p class="text-xs">La calidad del aire es buena comparada con otras ciudades</p>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="weather">
  a
</article>

