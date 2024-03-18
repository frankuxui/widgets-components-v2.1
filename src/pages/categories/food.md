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
  <section class="col-span-8 flex justify-between flex-col p-3 gap-1">
    <header class="flex flex-row justify-between items-start">
      <h2 class="font-medium"> Asparagus salad with scrambled eggs</h2>
    </header>
    <div class="flex items-center justify-between w-full">
      <span class="font-semibold">12,50€</span>
      <button class="flex flex-none items-center justify-center gap-1 font-medium text-sm rounded h-6 w-6 transition-colors duration-200 bg-gray-100 dark:bg-gray-800 dark:text-white focus:bg-gray-300 dark:focus:bg-gray-700">
        <svg class="flex-none" width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
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
  <section class="col-span-8 flex justify-between flex-col p-3 gap-1">
    <header class="flex flex-row justify-between items-start">
      <h2 class="font-medium"> Spaghetti with tomato sauce and basil</h2>
    </header>
    <div class="flex items-center justify-between w-full">
      <span class="font-semibold">18,99€</span>
      <div class="flex items-center justify-between rounded p-1 gap-3 bg-gray-200 dark:bg-gray-800">
        <button class="flex flex-none items-center justify-center gap-1 font-medium text-lg rounded h-4 w-4 transition-colors duration-200 bg-white dark:bg-gray-600">
          &#8722;
        </button>
        <span class="font-medium text-xs">1</span>
        <button class="flex flex-none items-center justify-center gap-1 font-medium text-lg rounded h-4 w-4 transition-colors duration-200 bg-white dark:bg-gray-600">
          &#43;
        </button>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between gap-4 p-3 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <header class="flex items-center justify-start w-full gap-4">
    <figure class="flex items-center justify-center w-10 h-10 p-1 rounded-full border border-gray-300 flex-none bg-white dark:border-white">
      <img src="https://www.svgrepo.com/show/408532/dog-food.svg" alt="avatar" loading="lazy" class="w-full object-cover">
    </figure>
    <h2 class="font-medium"> Chicken with rice and vegetables</h2>
    <button class="flex flex-none items-center justify-center text-xs font-medium h-6 px-3 rounded transition-colors duration-200 bg-green-600 text-white hover:bg-green-500">
      Order
    </button>
  </header>
</article>

<article class="border shadow-sm break-inside flex items-center justify-start flex-col gap-4 p-3 rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
  <svg width="38" height="38" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48">
    <path class="fill-none stroke-current" stroke-width="2" d="M10.92 28.19c-2.72-2-4.85-3.94-6.24-5.12a2.56 2.56 0 0 1-.9-2 2.72 2.72 0 0 1 .12-.8 1 1 0 0 1 1.5-.62c2.07 1.17 7.17 3.55 16.06 4.82a16.24 16.24 0 0 0 8.09-1.06h0"/>
    <path class="fill-none stroke-current" stroke-width="2" d="M38 12c-1 5.26-3.07 15.78-11.48 19.37A55.53 55.53 0 0 1 15 35h0a28.77 28.77 0 0 1-4.54.53 1 1 0 0 0-1 1.13 2.57 2.57 0 0 0 2.11 2.12c4.76.77 16.91 3.69 26.17-2.79 11.36-7.93 4.76-23.06 4.76-23.06l.11-.5v0"/>
    <path class="fill-none stroke-current" stroke-width="2" d="m42 13 1.53-4-.72-.19L39.58 8s-.36 1-1.07 2.64c-2.19 4.91-7.77 15.12-16.72 16.66-8.75 1.5-14.27.79-16.56.31a1 1 0 0 0-1.23 1A2.56 2.56 0 0 0 5.56 31c1.94.8 4.59 2.84 8.44 4"/>
    <path class="fill-none stroke-current" stroke-width="2" d="M-423-423h690v690h-690z"/>
  </svg>
  Coming soon
</article>

<section class="grid grid-cols-3 gap-3 mb-3">
  <article class="relative border shadow-sm break-inside flex items-center justify-start flex-col gap-1 font-medium text-center p-3 rounded-xl overflow-hidden text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    <div class="absolute w-12 h-12 top-0 left-2 rounded-full z-0 bg-rose-400"></div>
    <header class="relative">
      <svg width="50" height="50" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" >
        <path fill="none" d="M0 0h64v64H0z"/>
        <path d="M47.541 38.773H16.459l4.104 18.873h22.874l4.104-18.873zM45 23.773a7.5 7.5 0 0 1 7.5 7.5s0 0 0 0a7.5 7.5 0 0 1-7.5 7.5" stroke-width="2" stroke="currentColor" fill="none"/>
        <path d="M19 38.773a7.5 7.5 0 0 1-7.5-7.5s0 0 0 0a7.5 7.5 0 0 1 7.5-7.5h.614c.742-6.179 6.008-10.975 12.386-10.975 2.513 0 4.854.744 6.813 2.025M44.386 23.773c0 2.398-.142 4.244-.567 5.5M25 24v1" stroke-width="2" stroke="currentColor" fill="none"/>
        <circle cx="44.102" cy="18.484" r="5.289" stroke-width="2" stroke="currentColor" fill="none"/>
        <path d="M34.425 53.83h5.581l1.419-6.79M46.052 13.148s.714-1.785 2.231-2.945" stroke-width="2" stroke="currentColor" fill="none"/>
      </svg>
      <h2>Cake</h2>
    </header>
  </article>
  <article class="relative border shadow-sm break-inside flex items-center justify-start flex-col gap-1 font-medium text-center p-3 rounded-xl overflow-hidden text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    <div class="absolute w-12 h-12 top-0 left-2 rounded-full z-0 bg-amber-400"></div>
    <header class="relative">
      <svg width="50" height="50" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" >
        <path fill="none" d="M0 0h64v64H0z"/>
        <path d="M54.448 33a1.335 1.335 0 0 1 1.322 1.534l-.726 4.839A16 16 0 0 1 39.221 53H24.779A16 16 0 0 1 8.956 39.373l-.726-4.839A1.335 1.335 0 0 1 9.552 33h44.896z" stroke="currentColor" fill="none" stroke-width="2"/>
        <path d="M47.5 45.284a15.105 15.105 0 0 1-9.6 3.432M43 52.503v1.37A3.13 3.13 0 0 1 39.872 57H24.128A3.127 3.127 0 0 1 21 53.873v-1.37M28.529 33a9.886 9.886 0 0 1-.365-5.247 9.891 9.891 0 0 1 3.461-5.736 16.81 16.81 0 0 0 5.824-9.684c.094-.42.177-.834.257-1.232a3.862 3.862 0 0 1 4.548-3.024s0 0 0 0a3.861 3.861 0 0 1 3.024 4.548l-.248 1.234a16.813 16.813 0 0 0 1.626 11.188 9.83 9.83 0 0 1 .98 6.624A9.963 9.963 0 0 1 47.272 33M18.141 33a9.97 9.97 0 0 1-.103-1.434c0-2.393.849-4.59 2.261-6.306a16.806 16.806 0 0 0 3.799-10.642c.009-.431.009-.853.009-1.259a3.862 3.862 0 0 1 3.862-3.862s0 0 0 0a3.862 3.862 0 0 1 3.862 3.862v1.259c0 .448.018.895.054 1.339" stroke="currentColor" fill="none" stroke-width="2"/>
        <circle cx="38" cy="28" r="4" stroke="currentColor" fill="none" stroke-width="2"/>
        <path d="M53 33s1.521-5.869-1.649-9.511M13.002 33A9.952 9.952 0 0 1 11 27c0-5.114 3.848-9.337 8.804-9.929M11.635 23.489 14 24M12 32l2-1M19 18v1" stroke="currentColor" fill="none" stroke-width="2"/>
      </svg>
      <h2>Salad</h2>
    </header>
  </article>
  <article class="relative border shadow-sm break-inside flex items-center justify-start flex-col gap-1 font-medium text-center p-3 rounded-xl overflow-hidden text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    <div class="absolute w-12 h-12 top-0 left-2 rounded-full z-0 bg-green-400"></div>
    <header class="relative">
      <svg width="50" height="50" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" >
        <path fill="none" d="M0 0h64v64H0z"/>
        <path d="M54.448 33a1.335 1.335 0 0 1 1.322 1.534l-.726 4.839A16 16 0 0 1 39.221 53H24.779A16 16 0 0 1 8.956 39.373l-.726-4.839A1.335 1.335 0 0 1 9.552 33h44.896z" fill="none" stroke="currentColor" stroke-width="2"/>
        <path d="M47.5 45.284a15.105 15.105 0 0 1-9.6 3.432M43 52.503V57H21v-4.497M12.3 33a10.161 10.161 0 0 1 3.085-2.524 5.391 5.391 0 0 1 5.667-6.547 6.986 6.986 0 0 1 5.941-2.013c1.295-6.811 8.282-6.624 11.959-3.805 4.507.19 4.917 2.734 4.917 2.734a5.003 5.003 0 0 1 3.88 6.49c.505.472.961.994 1.362 1.558A5.01 5.01 0 0 1 52.941 33M26.5 28.5l-1-.5M42.5 29l.5-.5" fill="none" stroke="currentColor" stroke-width="2"/>
      </svg>
      <h2>Rice</h2>
    </header>
  </article>
</section>

<section class="grid grid-cols-3 gap-3 mb-3">
  <article class="relative overflow-hidden border shadow-sm break-inside rounded text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    <svg width="50" height="50" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"><path d="M511.948866 570.036552m-453.963447 0a453.963448 453.963448 0 1 0 907.926895 0 453.963448 453.963448 0 1 0-907.926895 0Z" fill="#FF8A57" /><path d="M954.049336 214.760811C876.121842 137.855987 801.262359 97.562768 683.143913 202.693299c0 0 172.217717 118.118446 254.235893 30.680116" fill="#69DB64" /><path d="M800.035154 2.658943l26.793968 18.40807a16.260461 16.260461 0 0 1 4.295216 22.19195A1067.872566 1067.872566 0 0 1 678.235094 231.123539a15.340058 15.340058 0 0 1-21.680615-0.511335 16.260461 16.260461 0 0 1 0-22.601019c21.067013-21.680615 68.416658-78.745631 120.572855-198.500349a15.544592 15.544592 0 0 1 22.90782-6.851893z" fill="#604D42" /><path d="M634.132428 266.093127a46.736043 35.588934 30 1 0 35.588934-61.641843 46.736043 35.588934 30 1 0-35.588934 61.641843Z" fill="#604D42" /><path d="M805.148507 675.985219m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M718.528313 780.706681m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M595.09198 880.00799m-24.748626 0a24.748627 24.748627 0 1 0 49.497253 0 24.748627 24.748627 0 1 0-49.497253 0Z" fill="#E2642D" /><path d="M809.034655 805.455308m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M736.220513 880.00799m-24.748626 0a24.748627 24.748627 0 1 0 49.497253 0 24.748627 24.748627 0 1 0-49.497253 0Z" fill="#E2642D" /><path d="M292.483771 323.163887c43.463497 0 43.463497-67.598522 0-67.598522s-43.565765 67.598522 0 67.598522zM201.159293 341.981025C129.572356 421.237991 109.118945 531.788675 123.027265 634.567063c5.829222 42.849895 70.871068 24.64636 65.144112-17.896734-10.226705-77.927494 6.647358-167.308898 60.644363-226.930591C277.859583 357.934685 230.305403 309.664636 201.159293 341.981025z" fill="#FFFFFF" /></svg>
  </article>
  <article class="relative overflow-hidden border shadow-sm break-inside rounded text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    a
  </article>
  <article class="relative overflow-hidden border shadow-sm break-inside rounded text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="food">
    a
  </article>
</section>