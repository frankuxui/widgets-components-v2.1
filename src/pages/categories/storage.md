---
layout: "../../layouts/Layout.astro"
slug: 'storage'
category: 'Storage'
tags: ['storage']
title: 'Widget components with tailwind CSS'
visible: true
---

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="storage">
  <svg width='45' height='27' viewBox='0 0 35 17' fill='none' xmlns='http://www.w3.org/2000/svg'>
    <path d='M34.11 14.7892L30.19 8.16921L34.07 1.81921C34.1621 1.66789 34.2124 1.49481 34.2157 1.31769C34.2189 1.14056 34.1751 0.965744 34.0886 0.811122C34.0022 0.6565 33.8762 0.527624 33.7236 0.437678C33.5709 0.347733 33.3972 0.299947 33.22 0.29921H2C1.46957 0.29921 0.960859 0.509924 0.585786 0.884996C0.210714 1.26007 0 1.76878 0 2.29921L0 14.2992C0 14.8296 0.210714 15.3384 0.585786 15.7134C0.960859 16.0885 1.46957 16.2992 2 16.2992H33.25C33.4265 16.2992 33.5999 16.2524 33.7524 16.1637C33.905 16.075 34.0314 15.9475 34.1188 15.7941C34.2061 15.6407 34.2513 15.467 34.2498 15.2905C34.2482 15.114 34.2 14.941 34.11 14.7892ZM10.51 11.4792H9.39L6.13 7.13921V11.4892H5V5.29921H6.13L9.4 9.64921V5.29921H10.52L10.51 11.4792ZM16.84 6.29921H13.31V7.78921H16.51V8.78921H13.31V10.3992H16.84V11.3992H12.18V5.29921H16.83L16.84 6.29921ZM25.13 11.4592H24L22.45 6.86921L20.9 11.4792H19.78L17.78 5.29921H19L20.32 9.72921L21.84 5.29921H23.06L24.52 9.72921L25.85 5.29921H27.08L25.13 11.4592Z' fill='currentColor' />
  </svg>
</article>

<article class='border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <header class='flex items-center gap-4'>
    <div class='flex items-center justify-center w-10 h-10 flex-none rounded-lg bg-gray-200 dark:bg-gray-900'>
      <svg xmlns='http://www.w3.org/2000/svg' fill='none' viewBox='0 0 24 24' stroke-width="1.5" stroke='currentColor' width='24' height='24'>
        <path d='M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z' />
      </svg>
    </div>
    <div class='flex-auto'>
      <h2 class='text-base font-medium block'>Documents</h2>
      <span class='text-sm text-gray-600 dark:text-gray-400'>873 files</span>
    </div>
  </header>
  <div class='flex flex-col items-center gap-1 text-base font-semibold'>
    <span>38 Gb</span>
    <div class='relative w-full h-1 bg-gray-100 rounded-sm overflow-hidden dark:bg-gray-600'>
      <div class='absolute left-0 w-1/3 h-full bg-[#00AC47]' />
    </div>
  </div>
</article>

<article class='border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <header class='flex items-center gap-4'>
    <div class='flex items-center justify-center w-10 h-10 flex-none rounded-lg bg-gray-200 dark:bg-gray-900'>
      <svg width='24' height='24' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m2.25 15.75 5.159-5.159a2.25 2.25 0 0 1 3.182 0l5.159 5.159m-1.5-1.5 1.409-1.409a2.25 2.25 0 0 1 3.182 0l2.909 2.909m-18 3.75h16.5a1.5 1.5 0 0 0 1.5-1.5V6a1.5 1.5 0 0 0-1.5-1.5H3.75A1.5 1.5 0 0 0 2.25 6v12a1.5 1.5 0 0 0 1.5 1.5Zm10.5-11.25h.008v.008h-.008V8.25Zm.375 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Z"></path>
      </svg>
    </div>
    <div class='flex-auto'>
      <h2 class='text-base font-medium block'>Photos</h2>
      <span class='text-xs text-gray-600 dark:text-gray-400'>September 14, 2023</span>
    </div>
  </header>
  <div class='flex flex-col items-center gap-1 text-base font-semibold'>
    <span>38 Gb</span>
    <div class='relative w-full h-1 bg-gray-100 rounded-sm overflow-hidden dark:bg-gray-600'>
      <div class='absolute left-0 w-1/3 h-full bg-[#00AC47]' />
    </div>
  </div>
</article>

<article class='border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <div class='flex items-center gap-4'>
    <div class='flex items-center justify-center flex-none'>
      <svg width='40' height='37' viewBox='0 0 37 34' fill='none' xmlns='http://www.w3.org/2000/svg'>
        <path d='M2.79724 28.7827L4.42898 31.596C4.76805 32.1884 5.2554 32.6538 5.8276 32.9923C7.46657 30.9156 8.6072 29.322 9.25007 28.2115C9.90234 27.0846 10.704 25.3217 11.6552 22.9231C9.09181 22.5862 7.14933 22.4179 5.82774 22.4179C4.5592 22.4179 2.61672 22.5862 0 22.9231C0 23.5788 0.169534 24.2346 0.508601 24.827L2.79724 28.7827Z' fill='#0066DA' />
        <path d='M31.1724 32.9923C31.7447 32.6538 32.2321 32.1884 32.571 31.5962L33.2492 30.4327L36.4915 24.827C36.8243 24.2474 36.9996 23.5911 37 22.9231C34.3681 22.5862 32.4292 22.4179 31.1831 22.4179C29.8439 22.4179 27.9049 22.5862 25.366 22.9231C26.3059 25.3348 27.0971 27.0977 27.7395 28.2115C28.3874 29.3352 29.5317 30.9287 31.1724 32.9923Z' fill='#EA4335' />
        <path d='M18.5 11.0769C20.3962 8.79086 21.7031 7.02798 22.4204 5.78852C22.9981 4.79043 23.6339 3.19677 24.3276 1.0077C23.7554 0.669234 23.0985 0.5 22.4204 0.5H14.5796C13.9015 0.5 13.2447 0.690442 12.6724 1.0077C13.5549 3.51836 14.3039 5.3052 14.919 6.36807C15.5988 7.54275 16.7925 9.11231 18.5 11.0769Z' fill='#00832D' />
        <path d='M25.3448 22.9231H11.6552L5.8276 32.9923C6.39965 33.3308 7.05668 33.5 7.73482 33.5H29.2652C29.9433 33.5 30.6003 33.3097 31.1724 32.9923L25.3448 22.9231Z' fill='#2684FC' />
        <path d='M18.5 11.0769L12.6724 1.0077C12.1001 1.34617 11.6128 1.8116 11.2738 2.40399L0.508601 21.0193C0.175767 21.5988 0.000439729 22.2551 0 22.9231H11.6552L18.5 11.0769Z' fill='#00AC47' />
        <path d='M31.109 11.7116L25.7262 2.40384C25.3873 1.81145 24.8998 1.34617 24.3276 1.0077L18.5 11.0769L25.3448 22.9231H36.9789C36.9789 22.2672 36.8094 21.6117 36.4703 21.0193L31.109 11.7116Z' fill='#FFBA00' />
      </svg>
    </div>
    <div class='flex-auto'>
      <h2 class='text-base font-medium block'>Google drive</h2>
      <span class='text-sm text-gray-600 dark:text-gray-400'>543 files</span>
    </div>
  </div>
  <div class='flex flex-col items-center gap-1 text-base font-semibold'>
    <span>10 Gb</span>
    <div class='relative w-full h-1 bg-gray-100 rounded-sm overflow-hidden dark:bg-gray-600'>
      <div class='absolute left-0 w-1/3 h-full bg-indigo-500' />
    </div>
  </div>
</article>

<article class='border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <div class='flex items-center gap-4'>
    <div class='flex items-center justify-center flex-none w-10 h-10 rounded-full bg-gray-200 dark:bg-gray-900'>
      <svg width='24' height='24' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 0 1-3-3m3 3a3 3 0 1 0 0 6h13.5a3 3 0 1 0 0-6m-16.5-3a3 3 0 0 1 3-3h13.5a3 3 0 0 1 3 3m-19.5 0a4.5 4.5 0 0 1 .9-2.7L5.737 5.1a3.375 3.375 0 0 1 2.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 0 1 .9 2.7m0 0a3 3 0 0 1-3 3m0 3h.008v.008h-.008v-.008Zm0-6h.008v.008h-.008v-.008Zm-3 6h.008v.008h-.008v-.008Zm0-6h.008v.008h-.008v-.008Z"></path>
      </svg>
    </div>
    <div class='flex flex-col w-full space-y-1'>
      <div class='flex justify-between items-center'>
        <h2 class='text-base font-medium block'>Storage</h2>
        <div class='flex items-center font-medium text-gray-500'>
          <span>27 Gb</span>&nbsp;/&nbsp;<span class="text-blue-600">32 Gb</span>
        </div>
      </div>
      <div class='relative w-full h-1 bg-gray-100 rounded-sm overflow-hidden dark:bg-gray-600'>
        <div class='absolute left-0 w-1/2 h-full bg-purple-500' />
      </div>
    </div>
  </div>
</article>

<article class='border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <section class='flex items-center space-x-4'>
    <div class='relative flex flex-row items-center justify-center'>
      <svg width='60' height='60' viewBox='0 0 64 64' fill='none' xmlns='http://www.w3.org/2000/svg'>
        <path d='M64 32C64 49.6731 49.6731 64 32 64C14.3269 64 0 49.6731 0 32C0 14.3269 14.3269 2.3509e-05 32 2.3509e-05C49.6731 2.3509e-05 64 14.3269 64 32ZM6.13666 32C6.13666 46.284 17.7161 57.8634 32 57.8634C46.2839 57.8634 57.8633 46.284 57.8633 32C57.8633 17.7161 46.2839 6.13668 32 6.13668C17.7161 6.13668 6.13666 17.7161 6.13666 32Z' class="fill-gray-200 dark:fill-gray-700" />
        <path d='M20.0412 5.65559C19.3408 4.11254 20.0205 2.2786 21.6235 1.72908C27.1738 -0.173579 33.1614 -0.519827 38.9281 0.759001C45.6969 2.26006 51.795 5.91887 56.3049 11.1848C60.8148 16.4508 63.4924 23.039 63.9348 29.9581C64.3117 35.8528 63.0489 41.716 60.3154 46.9078C59.5259 48.4072 57.6093 48.7968 56.1923 47.8674C54.7753 46.9381 54.3984 45.0422 55.1535 43.5252C57.1768 39.4605 58.1027 34.9168 57.8106 30.3497C57.4531 24.7575 55.2889 19.4327 51.6439 15.1766C47.9989 10.9205 43.0702 7.96331 37.5995 6.75011C33.1316 5.7593 28.4996 5.97546 24.1721 7.34971C22.557 7.8626 20.7417 7.19864 20.0412 5.65559Z' class="fill-gray-800 dark:fill-white" />
      </svg>
      <span class='absolute text-md font-medium top-1/2 left-1/2 -translate-y-1/2 -translate-x-1/2'>32%</span>
    </div>
    <header class='flex-auto'>
      <h2 class='text-base font-medium block'>Verified space</h2>
      <p class='flex items-center gap-2 text-gray-500'> This operation may take several minutes </p>
    </header>
  </section>
  <span class='flex items-center justify-center p-1'>
    <svg width='26' height='26' viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'>
      <path d='M12 2C6.5 2 2 6.5 2 12S6.5 22 12 22 22 17.5 22 12 17.5 2 12 2M12 20C7.59 20 4 16.41 4 12S7.59 4 12 4 20 7.59 20 12 16.41 20 12 20M16.59 7.58L10 14.17L7.41 11.59L6 13L10 17L18 9L16.59 7.58Z' fill='currentColor' />
    </svg>
  </span>
</article>

<article class='border shadow-sm break-inside flex flex-row justify-between items-center rounded-xl p-4 mb-3 gap-4 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900' data-filter="storage">
  <div class='flex items-center justify-start gap-4'>
    <div class='relative flex-none'>
      <svg width='65' height='65' viewBox='0 0 59 61' fill='none' xmlns='http://www.w3.org/2000/svg'>
        <path d='M56.7593 41.2212C59.6861 34.1467 59.7479 26.2115 56.9317 19.0923C54.1154 11.973 48.6417 6.22754 41.6672 3.06984C34.6927 -0.0878663 26.7638 -0.410408 19.5558 2.17037C12.3479 4.75114 6.42564 10.0331 3.04044 16.9C-0.344766 23.767 -0.927703 31.681 1.4148 38.9699C3.75731 46.2587 8.84175 52.3514 15.5937 55.9604C22.3457 59.5695 30.2364 60.4122 37.5983 58.3105C44.9602 56.2088 51.2166 51.3273 55.0456 44.6976L47.3819 40.2714C44.7016 44.9122 40.3221 48.3293 35.1688 49.8005C30.0155 51.2717 24.492 50.6818 19.7656 48.1554C15.0392 45.6291 11.4801 41.3643 9.84037 36.2621C8.20062 31.1599 8.60867 25.62 10.9783 20.8132C13.348 16.0063 17.4935 12.3089 22.5391 10.5024C27.5847 8.69585 33.1349 8.92163 38.0171 11.132C42.8992 13.3424 46.7308 17.3643 48.7022 22.3477C50.6735 27.3312 50.6303 32.8859 48.5815 37.838L56.7593 41.2212Z' fill='currentColor' class='fill-gray-200 dark:fill-gray-600' />
        <path d='M54.575 30.6546C57.0189 30.6546 59.034 32.6467 58.6688 35.0631C58.1258 38.6557 56.9218 42.13 55.1047 45.3056C52.5522 49.7665 48.8785 53.4832 44.4475 56.0873C40.0165 58.6915 34.9821 60.0929 29.8428 60.1526C24.7036 60.2124 19.6379 58.9284 15.1476 56.4279C10.6573 53.9273 6.89824 50.2971 4.24273 45.8967C1.58722 41.4962 0.127435 36.4784 0.00799284 31.3402C-0.11145 26.202 1.11359 21.1218 3.56176 16.6027C5.30453 13.3858 7.62408 10.5327 10.3922 8.17926C12.2542 6.59631 15.0088 7.26037 16.2957 9.33794C17.5826 11.4155 16.8979 14.1143 15.1415 15.8136C13.6337 17.2724 12.3508 18.9585 11.3432 20.8183C9.62952 23.9816 8.77199 27.5378 8.8556 31.1345C8.93921 34.7313 9.96106 38.2438 11.8199 41.324C13.6788 44.4043 16.3101 46.9455 19.4533 48.6959C22.5966 50.4463 26.1425 51.3451 29.74 51.3032C33.3375 51.2614 36.8616 50.2805 39.9633 48.4575C43.0649 46.6346 45.6365 44.0329 47.4233 40.9103C48.4738 39.0744 49.2316 37.0959 49.6777 35.0459C50.1974 32.6579 52.1312 30.6546 54.575 30.6546Z' fill='url(#paint0_linear_336_221)' />
        <defs>
          <linearGradient id='paint0_linear_336_221' x1='0' y1='30.6546' x2='59' y2='30.6546' gradientUnits='userSpaceOnUse'>
            <stop stop-color='#EB3349' />
            <stop offset='1' stop-color='#F45C43' />
          </linearGradient>
        </defs>
      </svg>
      <span class='absolute text-sm font-semibold top-1/2 left-1/2 -translate-y-1/2 -translate-x-1/2'>70%</span>
    </div>
    <div class="flex-1">
      <h2 class='text-lg font-medium'>Storage</h2>
      <p class="text-xs">This is the space you currently occupy...</p>
    </div>
  </div>
  <button class="rounded-full flex flex-none items-center justify-center w-9 h-9 transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24">
      <path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" fill="currentColor"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-row justify-between items-center rounded-xl p-4 mb-3 gap-4 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="storage">
  <label class="flex items-center gap-4 cursor-pointer">
    <div class="flex flex-col gap-1">
      <span class="text-base font-medium">Strictly Necessary</span>
      <p class="text-sm text-gray-700 dark:text-gray-300">These cookies are essential in order to use the website and use its features.</p>
    </div>
    <div class="relative inline-flex items-center cursor-pointer">
      <input type="checkbox" value="" class="sr-only peer" checked>
      <div class="w-11 h-6 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 dark:bg-gray-700 peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"></div>
    </div>
  </label>
</article>

<article class="border shadow-sm break-inside flex flex-row justify-between items-center rounded-xl p-4 mb-3 gap-4 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="storage">
  <label class="flex items-center gap-4 cursor-pointer">
    <div class="flex flex-col gap-1">
      <span class="text-base font-medium">Functional Cookies</span>
      <p class="text-sm text-gray-700 dark:text-gray-300">These cookies allow the website to provide personalized functionality.</p>
    </div>
    <div class="relative inline-flex items-center cursor-pointer">
      <input type="checkbox" value="" class="sr-only peer" checked>
      <div class="w-11 h-6 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 dark:bg-gray-700 peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"></div>
    </div>
  </label>
</article>