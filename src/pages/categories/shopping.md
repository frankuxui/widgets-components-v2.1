---
layout: "../../layouts/Layout.astro"
slug: 'shopping'
category: 'Shopping'
tags: ['shopping']
title: 'Widget components with tailwind CSS'
---

<article class="border shadow-sm break-inside flex flex-col gap-2 rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <header class="flex items-start justify-between">
    <div class="flex items-center gap-2">
      <svg width="24" height="24" fill="none" class="flex-none mt-1" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <h2 class="text-lg font-medium">Awards</h2>
    </div>
    <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="flex items-center">
    <h2 class="flex flex-1 items-start gap-2 text-sm">
      <span>This purchase has a 24-hour replacement guarantee.</span>
    </h2>
    <button class="flex flex-none items-center gap-1 font-medium text-base rounded-full px-2 h-8 bg-indigo-50 dark:text-white dark:bg-gray-900">
      <span>Free</span>
      <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m11.25 11.25.041-.02a.75.75 0 0 1 1.063.852l-.708 2.836a.75.75 0 0 0 1.063.853l.041-.021M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9-3.75h.008v.008H12V8.25Z"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between gap-2 rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <header class="flex items-center space-x-4">
    <figure class="flex items-center justify-center flex-none w-10 h-10 rounded-full bg-gray-950 text-white dark:bg-gray-200 dark:text-black">
      <svg width="24" height="24" viewBox="0 0 24 10" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M23.9999 0.7995L6.44194 8.2755C4.98594 8.8915 3.76294 9.2005 2.77394 9.2005C1.65394 9.2005 0.840936 8.8085 0.336936 8.0235C0.0199359 7.5195 -0.0730641 6.8805 0.0569359 6.1055C0.186936 5.3305 0.532936 4.5055 1.09294 3.6275C1.55994 2.9175 2.32494 1.9845 3.38994 0.827499C3.0287 1.39617 2.76381 2.02056 2.60594 2.6755C2.32594 3.8705 2.57794 4.7475 3.36194 5.3075C3.73494 5.5685 4.24794 5.6995 4.90194 5.6995C5.42394 5.6995 6.01194 5.6155 6.66594 5.4475L23.9999 0.7995Z" fill="currentColor"></path>
      </svg>
    </figure>
    <section class="flex-auto">
      <h2 class="text-base font-semibold block">Nike store</h2>
      <p class="text-xs">6 months of promotions</p>
    </section>
  </header>
  <section class="inline-flex flex-col items-end space-y-1 text-right">
    <span class="font-semibold">-27.50 €</span>
    <span class="text-xs">11:00AM</span>
  </section>
</article>

<article class="border shadow-sm break-inside flex flex-col justify-between rounded-xl p-4 gap-2 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <header class="flex items-center justify-between">
    <div class="flex items-center gap-2 -mt-1 text-indigo-600 dark:text-white">
      <svg class="flex-none" width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 18.75a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h6m-9 0H3.375a1.125 1.125 0 0 1-1.125-1.125V14.25m17.25 4.5a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h1.125c.621 0 1.129-.504 1.09-1.124a17.902 17.902 0 0 0-3.213-9.193 2.056 2.056 0 0 0-1.58-.86H14.25M16.5 18.75h-2.25m0-11.177v-.958c0-.568-.422-1.048-.987-1.106a48.554 48.554 0 0 0-10.026 0 1.106 1.106 0 0 0-.987 1.106v7.635m12-6.677v6.677m0 4.5v-4.5m0 0h-12"></path>
      </svg>
      <h2 class="text-base font-medium mt-1">Shipping</h2>
    </div>
    <button class="flex flex-none items-center gap-1 font-medium text-sm rounded-full px-2 h-8 bg-gray-100 dark:text-white dark:bg-gray-900">
      <span>Free</span>
      <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m11.25 11.25.041-.02a.75.75 0 0 1 1.063.852l-.708 2.836a.75.75 0 0 0 1.063.853l.041-.021M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9-3.75h.008v.008H12V8.25Z"></path>
      </svg>
    </button>
  </header>
  <section class="flex items-center gap-4">
    <p class="font-medium text-sm">Receive it between Friday, Jan 15 and Monday, Jan 18</p>
    <button class="rounded-full flex flex-none items-center justify-center w-9 h-9 transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24">
        <path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" fill="currentColor"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <header class="flex items-center justify-between">
    <div class="flex items-center gap-3">
      <div class="flex items-center justify-center w-12 h-12 rounded-full border border-gray-300 dark:border-gray-800">
        <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="m21 7.5-9-5.25L3 7.5m18 0-9 5.25m9-5.25v9l-9 5.25M3 7.5l9 5.25M3 7.5v9l9 5.25m0-9v9"></path>
        </svg>
      </div>
      <div class="flex flex-col">
        <h2 class="text-lg font-semibold">2352JUA</h2>
        <span class="text-xs text-gray-600 dark:text-gray-400">Paid on Dec 23. 2020</span>
      </div>
    </div>
    <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="mt-8">
    <div class="relative w-full h-2">
      <div class="absolute top-1/2 -translate-y-1/2 left-0 w-full h-0 border border-dashed border-gray-300 dark:border-gray-600 rounded-full"></div>
      <div class="absolute top-1/2 -translate-y-1/2 left-0 w-1/2 h-1 bg-green-500">
        <div class="flex items-center justify-center absolute right-0 top-1/2 p-0.5 bg-white dark:bg-gray-950 -translate-y-1/2">
          <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 18.75a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h6m-9 0H3.375a1.125 1.125 0 0 1-1.125-1.125V14.25m17.25 4.5a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h1.125c.621 0 1.129-.504 1.09-1.124a17.902 17.902 0 0 0-3.213-9.193 2.056 2.056 0 0 0-1.58-.86H14.25M16.5 18.75h-2.25m0-11.177v-.958c0-.568-.422-1.048-.987-1.106a48.554 48.554 0 0 0-10.026 0 1.106 1.106 0 0 0-.987 1.106v7.635m12-6.677v6.677m0 4.5v-4.5m0 0h-12"></path>
          </svg>
        </div>
      </div>
      <div class="flex items-center justify-center absolute left-0 top-1/2 w-7 h-7 rounded-full bg-green-500 transform -translate-y-1/2">
        <span class="w-3 h-3 rounded-full bg-white dark:bg-gray-950"></span>
      </div>
      <div class="flex items-center justify-center absolute top-1/2 -translate-y-1/2 right-0 w-9 h-9 rounded-full border text-gray-500 border-gray-300 bg-white dark:border-gray-600 dark:bg-gray-950">
        <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"></path>
          <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"></path>
        </svg>
      </div>
    </div>
  </section>
  <section class="flex items-center justify-between mt-5">
    <div class="flex flex-col items-start">
      <h3 class="font-semibold text-sm">Tarragona</h3>
      <p class="text-sm text-gray-600 dark:text-gray-400">Spain</p>
    </div>
    <div class="flex flex-col items-end">
      <h3 class="font-semibold text-sm">Madrid</h3>
      <p class="text-sm text-gray-600 dark:text-gray-400">Spain</p>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 gap-2 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <section class="flex items-start gap-4">
    <svg class="flex-none" width="32" height="32" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 18.75a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h6m-9 0H3.375a1.125 1.125 0 0 1-1.125-1.125V14.25m17.25 4.5a1.5 1.5 0 0 1-3 0m3 0a1.5 1.5 0 0 0-3 0m3 0h1.125c.621 0 1.129-.504 1.09-1.124a17.902 17.902 0 0 0-3.213-9.193 2.056 2.056 0 0 0-1.58-.86H14.25M16.5 18.75h-2.25m0-11.177v-.958c0-.568-.422-1.048-.987-1.106a48.554 48.554 0 0 0-10.026 0 1.106 1.106 0 0 0-.987 1.106v7.635m12-6.677v6.677m0 4.5v-4.5m0 0h-12"></path>
    </svg>
    <p class="text-sm">Envios <b>Gratuitos</b> en pedidos superiores a <b>€80.00</b></p>
    <button class="flex items-center justify-center h-8 w-8 flex-none rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="22" height="22" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m11.25 11.25.041-.02a.75.75 0 0 1 1.063.852l-.708 2.836a.75.75 0 0 0 1.063.853l.041-.021M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-9-3.75h.008v.008H12V8.25Z"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside relative overflow-hidden flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <div class="absolute z-0 top-0 left-1/2 w-12 h-12 bg-green-500/80 blur-2xl"></div>
  <header class="flex items-center gap-4 relative">
    <div class="rounded-full flex flex-none items-center justify-center w-12 h-12 border dark:border-gray-800">
      <svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M21 11.25v8.25a1.5 1.5 0 0 1-1.5 1.5H5.25a1.5 1.5 0 0 1-1.5-1.5v-8.25M12 4.875A2.625 2.625 0 1 0 9.375 7.5H12m0-2.625V7.5m0-2.625A2.625 2.625 0 1 1 14.625 7.5H12m0 0V21m-8.625-9.75h18c.621 0 1.125-.504 1.125-1.125v-1.5c0-.621-.504-1.125-1.125-1.125h-18c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125Z"></path>
      </svg>
    </div>
    <div class="flex flex-col relative">
      <h2 class="text-base font-medium">Regalo</h2>
      <span class="text-xs text-gray-600 dark:text-gray-400">Paid on Dec 23. 2020</span>
    </div>
  </header>
  <span class="text-lg font-semibold">54,00€</span>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="shopping">
  <header class="flex flex-col gap-1">
    <p>Total you owe</p>
    <h2 class="text-xl font-semibold">129, 67€</h2>
    <span class="text-xs text-gray-600 dark:text-gray-400">At the moment there is nothing to show</span>
  </header>
  <button class="flex h-9 px-4 flex-none items-center justify-center rounded-full text-sm font-medium transition-colors duration-200 bg-gray-100 hover:bg-gray-200 dark:bg-gray-900 dark:hover:bg-gray-800">Ver detalles</button>
</article>
