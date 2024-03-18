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

<section class="grid grid-cols-3 gap-3 mb-3">
  <article class="break-inside overflow-hidden relative flex flex-col items-center text-center gap-2 rounded-lg text-sm p-3 bg-gray-100 dark:bg-gray-900 dark:text-white" data-filter="food">
    <svg width="40" height="40" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"><path d="M511.948866 570.036552m-453.963447 0a453.963448 453.963448 0 1 0 907.926895 0 453.963448 453.963448 0 1 0-907.926895 0Z" fill="#FF8A57" /><path d="M954.049336 214.760811C876.121842 137.855987 801.262359 97.562768 683.143913 202.693299c0 0 172.217717 118.118446 254.235893 30.680116" fill="#69DB64" /><path d="M800.035154 2.658943l26.793968 18.40807a16.260461 16.260461 0 0 1 4.295216 22.19195A1067.872566 1067.872566 0 0 1 678.235094 231.123539a15.340058 15.340058 0 0 1-21.680615-0.511335 16.260461 16.260461 0 0 1 0-22.601019c21.067013-21.680615 68.416658-78.745631 120.572855-198.500349a15.544592 15.544592 0 0 1 22.90782-6.851893z" fill="#604D42" /><path d="M634.132428 266.093127a46.736043 35.588934 30 1 0 35.588934-61.641843 46.736043 35.588934 30 1 0-35.588934 61.641843Z" fill="#604D42" /><path d="M805.148507 675.985219m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M718.528313 780.706681m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M595.09198 880.00799m-24.748626 0a24.748627 24.748627 0 1 0 49.497253 0 24.748627 24.748627 0 1 0-49.497253 0Z" fill="#E2642D" /><path d="M809.034655 805.455308m-24.748627 0a24.748627 24.748627 0 1 0 49.497254 0 24.748627 24.748627 0 1 0-49.497254 0Z" fill="#E2642D" /><path d="M736.220513 880.00799m-24.748626 0a24.748627 24.748627 0 1 0 49.497253 0 24.748627 24.748627 0 1 0-49.497253 0Z" fill="#E2642D" /><path d="M292.483771 323.163887c43.463497 0 43.463497-67.598522 0-67.598522s-43.565765 67.598522 0 67.598522zM201.159293 341.981025C129.572356 421.237991 109.118945 531.788675 123.027265 634.567063c5.829222 42.849895 70.871068 24.64636 65.144112-17.896734-10.226705-77.927494 6.647358-167.308898 60.644363-226.930591C277.859583 357.934685 230.305403 309.664636 201.159293 341.981025z" fill="#FFFFFF" /></svg>
    <section class="flex flex-col w-full">
      <h2 class="font-medium">Orange</h2>
      <span class="font-medium"> &euro; 1.30 </span>
    </section>
  </article>
  <article class="break-inside overflow-hidden relative flex flex-col items-center text-center gap-2 rounded-lg text-sm p-3 bg-gray-100 dark:bg-gray-900 dark:text-white" data-filter="food">
      <svg width="40" height="40" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><g id="Tomato"><path d="M149.33333,469.33333c64,0,64,21.33334,106.66667,21.33334s42.66667-21.33334,106.66667-21.33334c85.33333,0,128-106.66666,128-213.33333S448,85.33333,362.66667,85.33333C298.66667,85.33333,320,64,256,64S213.33333,85.33333,149.33333,85.33333c-85.33333,0-128,64-128,170.66667S64,469.33333,149.33333,469.33333Z" style="fill:#c11107"/><path d="M384,320c0-149.33333-42.66667-256-128-256-64,0-42.66667,21.33333-106.66667,21.33333-85.33333,0-128,64-128,170.66667S64,469.33333,149.33333,469.33333c64,0,64,21.33334,106.66667,21.33334C256,490.66667,384,469.33333,384,320Z" style="fill:#c82e25"/><ellipse cx="106.66667" cy="170.66667" rx="48.26898" ry="36.20174" transform="translate(-89.43761 125.41183) rotate(-45)" style="fill:#d2514a"/><ellipse cx="85.33333" cy="149.33333" rx="26.19041" ry="14.96574" transform="translate(-80.60106 104.0785) rotate(-45)" style="fill:#de807a"/><path d="M251.8125,490.25C250.58333,490,128,463.58333,128,298.66667c0-139.58334,93.15625-187.77084,97.125-189.75l19.08333,38.16666c-2.875,1.47917-73.54166,39.39584-73.54166,151.58334,0,128.85416,86.02083,148.97916,89.67708,149.77083Z" style="fill:#c11107"/><path d="M362.66667,469.33333V426.66667C418.09375,426.66667,448,338.72917,448,256c0-128-64.22917-128-85.33333-128V85.33333c47.80208,0,128,22.16667,128,170.66667C490.66667,358.75,450.61458,469.33333,362.66667,469.33333Z" style="fill:#af0a00"/><path d="M362.66667,128l53.24349-14.1237S405.33333,64,341.33333,64,256,85.33333,256,85.33333,234.66667,64,192,64s-64,0-85.33333-21.33333c0,0,0,64,85.33333,64,0,0-64,42.66666-64,85.33333,0,0,42.66667-42.66667,85.33333-42.66667C192,170.66667,192,197.67448,192,234.66667c0,0,41.5625-62.36849,106.66667-64,40.6875,22.44791,64,58.23958,64,85.33333,0,0,42.66666-21.33333,42.66666-64S362.66667,128,362.66667,128Z" style="fill:#ef7f00"/><path d="M156.6875,169.3125,145.125,151.39583C169.16667,135.875,192.11458,128,213.33333,128h25.75v21.33333h-25.75C196.53125,149.33333,176.94792,156.25,156.6875,169.3125Z" style="fill:#e76400"/><path d="M364.84375,256.375l-4.39583-15.9375c-7.15625-25.95833-30.83334-52.6875-61.78125-69.77083H298.625c-38.85417.95833-69.25,23.33333-87.90625,41.9375l-15.0625-15.125c21.40625-21.33334,56.5625-47,102.47917-48.14584l5.79166-.125L308.96875,152c29.95833,16.52083,53.51042,40.4375,65.78125,66.125,5.21875-6.97917,9.25-15.75,9.25-26.125h21.33333c0,25.35417-15.10416,43.25-27.78125,53.8125Z" style="fill:#e76400"/><rect x="331.72504" y="105.04856" width="71.227" height="21.34038" transform="translate(-17.39683 98.19375) rotate(-14.87737)" style="fill:#e76400"/><circle cx="288" cy="138.66667" r="32" style="fill:#e76400"/><path d="M256,122.04172v.00005a27.29157,27.29157,0,0,0,27.29157,27.29156h0a27.28737,27.28737,0,0,0,22.71863-12.19959c8.15315-12.16364,44.42863-52.33953,66.15976-66.37153A26.479,26.479,0,0,0,384,48.44821v0a27.11483,27.11483,0,0,0-27.11483-27.11484h0a54.41546,54.41546,0,0,0-31.63254,10.02388C314.122,39.27162,277.84918,73.206,265.69067,90.4937A54.87029,54.87029,0,0,0,256,122.04172Z" style="fill:#f59707"/><path d="M283.29167,149.33333A27.32489,27.32489,0,0,1,256,122.04167h21.33333c0,5.27083,7.88542,7.8125,10.96875,3.20833,8.79167-13.10417,47.14584-56.16667,72.29167-72.39583l11.5625,17.91666c-21.61458,13.95834-58.01042,54.25-66.14583,66.35417A27.34259,27.34259,0,0,1,283.29167,149.33333Z" style="fill:#ef7f00"/><ellipse cx="234.66667" cy="277.33333" rx="42.66667" ry="64" style="fill:#d2514a"/></g></svg>
    <section class="flex flex-col w-full">
      <h2 class="font-medium">Tomato</h2>
      <span class="font-medium"> &euro; 0.98 </span>
    </section>
  </article>
  <article class="break-inside overflow-hidden relative flex flex-col items-center text-center gap-2 rounded-lg text-sm p-3 bg-gray-100 dark:bg-gray-900 dark:text-white" data-filter="food">
    <svg width="40" height="40" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>Artboard 137</title><g id="Apple"><path d="M245.33333,149.33333a10.66053,10.66053,0,0,1-10.66666-10.66666c0-2.84375.79166-70.22917,68.75-115.54167A10.66642,10.66642,0,0,1,315.25,40.875C256.6875,79.92708,256,138.08333,256,138.66667A10.66053,10.66053,0,0,1,245.33333,149.33333Z" style="fill:#ffa300"/><path d="M245.33333,149.3125c-5.4375-.08333-10.66666-4.75-10.66666-10.64583,0-.61459.08333-15.32292,6.66651-35.33334A10.65966,10.65966,0,1,1,261.58333,110C256.14583,126.54167,256,138.58333,256,138.70833A10.68767,10.68767,0,0,1,245.33333,149.3125Z" style="fill:#f98b00"/><path d="M362.66667,106.66667c-64,0-64,21.33333-106.66667,21.33333s-42.66667-21.33333-106.66667-21.33333-128,42.66666-128,128,64,101.41276,64,149.33333c0,42.66667,21.33334,85.33333,85.33334,85.33333,42.66666,0,42.66666,21.33334,85.33333,21.33334s42.66667-21.33334,85.33333-21.33334S426.66667,426.66667,426.66667,384c0-47.92057,64-64,64-149.33333S426.66667,106.66667,362.66667,106.66667Z" style="fill:#14a142"/><path d="M197.41623,473.10763c55.12423,17.79333,117.2222-9.31576,138.32313-63.26049,3.66235-9.36286,5.5487-18.277,5.59528-26.16615.28255-47.67318,63.99869-63.87109,63.99869-149.01432,0-29.38282-7.59375-53.6875-20.16406-72.931-22.47656-34.40886-65.99219-46.556-105.82552-36.43229-.27344.069-.61589.099-.89323.16666a82.75757,82.75757,0,0,1-9.14323,1.70443c-.46224.0599-.97656.09375-1.45052.14713A104.16527,104.16527,0,0,1,256,128c-42.66667,0-42.66667-21.33333-106.66667-21.33333s-128,42.66666-128,128,64,101.41276,64,149.33333c0,42.66667,21.33334,85.33333,85.33334,85.33333C182.09939,469.33333,190.46866,470.86506,197.41623,473.10763Z" style="fill:#4cc66e"/><ellipse cx="117.33333" cy="202.66667" rx="86.45793" ry="60.60814" transform="translate(-108.94084 142.32689) rotate(-45)" style="fill:#84d89c"/><ellipse cx="96" cy="181.33333" rx="38.73501" ry="23.38784" transform="translate(-100.10428 120.99355) rotate(-45)" style="fill:#b7e8c4"/><ellipse cx="138.66667" cy="416" rx="22.87035" ry="39.04213" transform="translate(-253.54189 219.89572) rotate(-45)" style="fill:#84d89c"/></g></svg>
    <section class="flex flex-col w-full">
      <h2 class="font-medium">Apple</h2>
      <span class="font-medium"> &euro; 2.10 </span>
    </section>
  </article>
</section>

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