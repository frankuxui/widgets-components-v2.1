---
layout: "../../layouts/Layout.astro"
slug: 'travel'
category: 'Travel'
tags: ['travel']
title: 'Widget components with tailwind CSS'
visible: true
---

<section class="grid grid-cols-2 gap-3">
  <article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
    <div class="w-full relative">
      <img src="https://images.pexels.com/photos/532263/pexels-photo-532263.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" class="w-full h-full object-cover aspect-square">
      <span class="absolute top-2 right-2 h-7 w-7 flex items-center justify-center rounded-full bg-white/70 text-black backdrop-blur-md shadow-md">
        <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"></path>
        </svg>
      </span>
    </div>
    <section class="flex flex-col p-3 gap-1">
      <h2 class="text-base font-medium">Rome</h2>
      <div class="flex items-center justify-between">
        <p class="flex items-center gap-1 text-gray-600">
          <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"></path>
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"></path>
          </svg>
          <span class="mt-1">Italy</span>
        </p>
        <p class="font-medium">€ 432.00</p>
      </div>
    </section>
  </article>
  <article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
    <div class="w-full relative">
      <img src="https://images.pexels.com/photos/1486222/pexels-photo-1486222.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" class="w-full h-full object-cover aspect-square">
      <span class="absolute top-2 right-2 h-7 w-7 flex items-center justify-center rounded-full bg-white/70 text-black backdrop-blur-md shadow-md">
        <svg  width="16" height="16" fill="currentColor" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="M2 6.342a3.375 3.375 0 0 1 6-2.088 3.375 3.375 0 0 1 5.997 2.26c-.063 2.134-1.618 3.76-2.955 4.784a14.437 14.437 0 0 1-2.676 1.61c-.02.01-.038.017-.05.022l-.014.006-.004.002h-.002a.75.75 0 0 1-.592.001h-.002l-.004-.003-.015-.006a5.528 5.528 0 0 1-.232-.107 14.395 14.395 0 0 1-2.535-1.557C3.564 10.22 1.999 8.558 1.999 6.38L2 6.342Z"></path>
        </svg>
      </span>
    </div>
    <section class="flex flex-col p-3 gap-1">
      <h2 class="text-base font-medium">New York</h2>
      <div class="flex items-center justify-between">
        <p class="flex items-center gap-1 text-gray-600">
          <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"></path>
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"></path>
          </svg>
          <span class="mt-1">EUA</span>
        </p>
        <span class="h-6 px-2 inline-flex items-center text-xs leading-5 font-medium rounded-full bg-emerald-100 text-green-800 dark:bg-emerald-500/30 dark:text-emerald-300">3 days</span>
      </div>
    </section>
  </article>
</section>

<article class="border relative shadow-sm break-inside flex items-center flex-col justify-between rounded-xl overflow-hidden mb-3 text-sm bg-gray-800 dark:border-gray-950" data-filter="travel">
  <header class="w-full p-4 flex items-center justify-between">
    <button class="w-8 h-8 flex items-center justify-center rounded-full bg-white text-black">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"></path>
      </svg>
    </button>
    <span class="w-8 h-8 flex items-center justify-center rounded-full text-sm font-medium text-black bg-white">
      5.0
    </span>
  </header>
  <div class="w-full flex flex-col gap-1 bg-gradient-to-t from-black/50 to-transparent p-4">
    <h2 class="font-medium text-xl text-white">Paris</h2>
    <p class="text-gray-300">Travel to Paris with a 20% discount, only for this month</p>
  </div>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
  <header class="col-span-4 flex-none">
    <img class="w-full h-full aspect-square object-cover" src="https://images.pexels.com/photos/2034335/pexels-photo-2034335.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Imagen">
  </header>
  <section class="col-span-8 flex flex-col p-3 gap-1">
    <div class="flex items-center justify-between">
      <h2 class="text-base font-semibold block">Booking</h2>
      <span class="h-6 px-2 inline-flex items-center text-xs font-medium rounded-md uppercase bg-rose-100 text-rose-800 dark:bg-rose-500/30 dark:text-rose-300">NEW</span>
    </div>
    <p class="text-gray-600 dark:text-gray-400">Hotel in Barcelona, with a 20% discount</p>
  </section>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
  <header class="col-span-3 flex-none">
    <img class="w-full h-full aspect-square object-cover" src="https://images.pexels.com/photos/1268855/pexels-photo-1268855.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Imagen">
  </header>
  <section class="col-span-9 flex flex-col p-3">
    <div class="flex items-start justify-between gap-4">
      <div class="flex flex-col">
        <h2 class="text-base font-medium block">Empire building</h2>
        <p class="text-xs text-gray-600">Hotel in Barcelona, with a 200m from the beach</p>
      </div>
      <div class="flex flex-none flex-col gap-1 mt-1">
        <span class="text-xs text-right text-gray-500">from</span>
        <h3 class="font-medium">€ 88.00</h3>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
  <header>
    <h2 class="text-base font-medium">Bamboo Villa Resort</h2>
    <p class="text-xs text-gray-600">Hotel in Barcelona, with a 20% discount</p>
  </header>
  <section class="flex items-center justify-between mt-4">
    <div class="flex items-center gap-2">
      <div class="h-6 px-2 gap-1 inline-flex items-center text-xs font-medium rounded-full uppercase bg-yellow-100 text-black">
        <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M11.48 3.499a.562.562 0 0 1 1.04 0l2.125 5.111a.563.563 0 0 0 .475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 0 0-.182.557l1.285 5.385a.562.562 0 0 1-.84.61l-4.725-2.885a.562.562 0 0 0-.586 0L6.982 20.54a.562.562 0 0 1-.84-.61l1.285-5.386a.562.562 0 0 0-.182-.557l-4.204-3.602a.562.562 0 0 1 .321-.988l5.518-.442a.563.563 0 0 0 .475-.345L11.48 3.5Z"></path>
        </svg>
        <span>5.0</span>
      </div>
      <div class="h-6 px-2 gap-1 inline-flex items-center text-xs font-medium rounded-full uppercase bg-cyan-100 text-black">
        <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z"></path>
        </svg>
        <span>Favorite</span>
      </div>
    </div>
    <div class="flex items-center gap-1">
      <h3 class="text-base font-medium">€ 88.00</h3>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

