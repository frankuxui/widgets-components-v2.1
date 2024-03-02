---
layout: "../../layouts/ExpoLayout.astro"
slug: 'food'
category: 'Food'
tags: ['food']
title: 'Widget components with tailwind CSS'
visible: true
---

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <div class="flex-none col-span-4">
    <img class="w-full h-full object-cover" src="https://images.pexels.com/photos/1640772/pexels-photo-1640772.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="avatar" loading="lazy">
  </div>
  <section class="col-span-8 flex justify-between flex-col p-3 gap-3">
    <header class="flex flex-row justify-between items-start">
      <h2 class="font-medium text-base"> Asparagus salad with scrambled eggs</h2>
    </header>
    <div class="flex items-center justify-between w-full">
      <span class="font-semibold text-base">12,50€</span>
      <button class="flex flex-none items-center justify-center gap-1 font-medium text-sm rounded h-6 w-6 transition-colors duration-200 bg-gray-100 dark:bg-gray-800 dark:text-white focus:bg-gray-300 dark:focus:bg-gray-700">
        <svg class="flex-none" width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15"></path>
        </svg>
      </button>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside grid grid-cols-12 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <div class="flex-none col-span-4">
    <img class="w-full h-full object-cover" src="https://images.pexels.com/photos/691114/pexels-photo-691114.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="avatar" loading="lazy">
  </div>
  <section class="col-span-8 flex justify-between flex-col p-3 gap-3">
    <header class="flex flex-row justify-between items-start">
      <h2 class="font-medium text-base"> Spaghetti with tomato sauce and basil</h2>
    </header>
    <div class="flex items-center justify-between w-full">
      <span class="font-semibold text-lg">18,99€</span>
      <div class="flex items-center justify-between rounded p-1 gap-3 bg-gray-200 dark:bg-gray-800">
        <button class="flex flex-none items-center justify-center gap-1 font-medium text-lg rounded h-5 w-5 transition-colors duration-200 bg-white dark:bg-gray-600">
          &#8722;
        </button>
        <span class="font-semibold text-xs">1</span>
        <button class="flex flex-none items-center justify-center gap-1 font-medium text-lg rounded h-5 w-5 transition-colors duration-200 bg-white dark:bg-gray-600">
          &#43;
        </button>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between gap-4 p-3 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <header class="flex items-center justify-start w-full gap-4">
    <figure class="flex items-center justify-center w-14 h-14 p-1 rounded-full border flex-none bg-white dark:border-white">
      <img src="https://www.svgrepo.com/show/408532/dog-food.svg" alt="avatar" loading="lazy" class="w-full object-cover">
    </figure>
    <h2 class="font-medium text-base"> Chicken with rice and vegetables</h2>
  </header>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between gap-4 p-3 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <header class="flex items-center justify-start w-full gap-4">
    <figure class="flex items-center justify-center w-14 h-14 p-1 rounded-full border flex-none bg-white dark:border-white ring-4 ring-black/5 dark:ring-white/5">
      <img src="https://www.svgrepo.com/show/408538/cat-bed.svg" alt="avatar" loading="lazy" class="w-full object-cover">
    </figure>
    <h2 class="font-medium text-base"> Vegetarian cat food with salmon and spinach</h2>
  </header>
</article>