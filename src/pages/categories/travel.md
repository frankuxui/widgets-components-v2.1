---
layout: "../../layouts/Layout.astro"
slug: 'travel'
category: 'Travel'
tags: ['travel']
title: 'Widget components with tailwind CSS'
---

<section class="grid grid-cols-2 gap-3">
  <article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
    <img src="https://images.pexels.com/photos/532263/pexels-photo-532263.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" class="w-full object-cover max-h-20 aspect-square">
    <section class="flex flex-col p-3 gap-1">
      <h2 class="text-base font-medium">Rome</h2>
      <div class="flex items-center justify-between">
        <p class="flex items-center gap-1 text-gray-600">
          <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"></path>
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"></path>
          </svg>
          <span>Italy</span>
        </p>
        <p class="font-medium">€ 432.00</p>
      </div>
    </section>
  </article>
  <article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel">
    <img src="https://images.pexels.com/photos/1486222/pexels-photo-1486222.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" class="w-full object-cover max-h-20 aspect-square">
    <section class="flex flex-col p-3 gap-1">
      <h2 class="text-base font-medium">New York</h2>
      <div class="flex items-center justify-between">
        <p class="flex items-center gap-1 text-gray-600">
          <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"></path>
            <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"></path>
          </svg>
          <span>EUA</span>
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
  <section class="col-span-9 flex flex-col p-3 gap-1">
    <div class="flex items-center justify-between">
      <div class="flex flex-col">
        <h2 class="text-base font-semibold block">Empire building</h2>
        <p class="flex items-center text-xs gap-1 text-gray-600 dark:text-gray-400">
          <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"></path>
          </svg>
          <span class="mt-0.5">2 hours</span>
        </p>
      </div>
      <div class="flex flex-col gap-1 mt-2">
        <span class="text-xs text-right text-gray-500">from</span>
        <h3 class="font-medium">€ 88.00</h3>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="travel"></article>

