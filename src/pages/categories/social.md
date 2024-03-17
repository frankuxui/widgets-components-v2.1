---
layout: "../../layouts/ExpoLayout.astro"
slug: 'social'
category: 'Social'
tags: ['social']
title: 'Widget components with tailwind CSS - Social'
visible: true
---

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between">
    <div class="flex items-center gap-2">
      <h2 class="text-sm font-medium">Project Management</h2>
      <span class="h-6 px-2 text-xs rounded-md flex items-center justify-center bg-green-100 text-green-600 dark:bg-green-500/30 dark:text-green-300">Success</span>
    </div>
    <button class="inline-flex items-center justify-center w-8 h-8 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="28" height="28" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section>
    <h2 class="text-base font-semibold">New Design</h2>
    <p class="text-sm text-gray-500">Design a new logo for our website, we are a startup company.</p>
  </section>
  <section class="flex items-center justify-between mt-3">
    <div class="col-start-2 row-start-1 row-end-3 flex-none">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar" loading="lazy" />
        </a>
      </dd>
    </div>
    <div class="flex items-center justify-end gap-4">
      <div class="flex items-center gap-1 font-medium">
        <svg width="20" height="20" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M8.625 12a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H8.25m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0H12m4.125 0a.375.375 0 1 1-.75 0 .375.375 0 0 1 .75 0Zm0 0h-.375M21 12c0 4.556-4.03 8.25-9 8.25a9.764 9.764 0 0 1-2.555-.337A5.972 5.972 0 0 1 5.41 20.97a5.969 5.969 0 0 1-.474-.065 4.48 4.48 0 0 0 .978-2.025c.09-.457-.133-.901-.467-1.226C3.93 16.178 3 14.189 3 12c0-4.556 4.03-8.25 9-8.25s9 3.694 9 8.25Z"></path>
        </svg>
        <span>23</span>
      </div>
      <div class="flex items-center gap-1 font-medium">
        <svg width="20" height="20" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 9.776c.112-.017.227-.026.344-.026h15.812c.117 0 .232.009.344.026m-16.5 0a2.25 2.25 0 0 0-1.883 2.542l.857 6a2.25 2.25 0 0 0 2.227 1.932H19.05a2.25 2.25 0 0 0 2.227-1.932l.857-6a2.25 2.25 0 0 0-1.883-2.542m-16.5 0V6A2.25 2.25 0 0 1 6 3.75h3.879a1.5 1.5 0 0 1 1.06.44l2.122 2.12a1.5 1.5 0 0 0 1.06.44H18A2.25 2.25 0 0 1 20.25 9v.776"></path>
        </svg>
        <span>87</span>
      </div>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between">
    <div class="flex items-center gap-2">
      <h2 class="text-base font-semibold">Michael</h2>
      <span class="text-xs text-gray-600">24 min ago</span>
    </div>
    <div class="flex items-center gap-1">
      <svg width="20" height="20" class="fill-amber-500" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path clip-rule="evenodd" fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z"></path>
      </svg>
      <span class="font-medium mt-1">4/5</span>
    </div>
  </header>
  <section class="mt-2">
    <p class="text-gray-600 dark:text-gray-400">Hi there! I'm a designer and developer from San Francisco and I'm looking...</p>
  </section>
</article>

<article class="border shadow-sm break-inside divide-y rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center justify-between">
    <div class="flex items-center gap-3">
      <span class="flex flex-none items-center justify-center font-medium w-5 h-5 text-xs rounded-full transition-colors bg-fuchsia-600 text-white">3</span>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5m-9-6h.008v.008H12v-.008ZM12 15h.008v.008H12V15Zm0 2.25h.008v.008H12v-.008ZM9.75 15h.008v.008H9.75V15Zm0 2.25h.008v.008H9.75v-.008ZM7.5 15h.008v.008H7.5V15Zm0 2.25h.008v.008H7.5v-.008Zm6.75-4.5h.008v.008h-.008v-.008Zm0 2.25h.008v.008h-.008V15Zm0 2.25h.008v.008h-.008v-.008Zm2.25-4.5h.008v.008H16.5v-.008Zm0 2.25h.008v.008H16.5V15Z" />
      </svg>
      <span class="font-medium text-sm">23 24 2024</span>
    </div>
    <button class="flex flex-none items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="28" height="28" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path clip-rule="evenodd" fill-rule="evenodd" d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z"></path>
      </svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside divide-y rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center justify-between">
    <div class="flex items-center gap-3">
      <span class="flex flex-none items-center justify-center font-medium w-5 h-5 text-xs rounded-full transition-colors bg-blue-700 dark:bg-blue-500 text-white">3</span>
      <div class="h-9 flex items-center justify-center rounded-full gap-2 px-3 bg-cyan-50 dark:bg-cyan-600/30 dark:text-cyan-400">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5m-9-6h.008v.008H12v-.008ZM12 15h.008v.008H12V15Zm0 2.25h.008v.008H12v-.008ZM9.75 15h.008v.008H9.75V15Zm0 2.25h.008v.008H9.75v-.008ZM7.5 15h.008v.008H7.5V15Zm0 2.25h.008v.008H7.5v-.008Zm6.75-4.5h.008v.008h-.008v-.008Zm0 2.25h.008v.008h-.008V15Zm0 2.25h.008v.008h-.008v-.008Zm2.25-4.5h.008v.008H16.5v-.008Zm0 2.25h.008v.008H16.5V15Z" />
        </svg>
        <span class="font-medium text-sm">23 24 2024</span>
      </div>
    </div>
    <button class="flex flex-none items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="28" height="28" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path clip-rule="evenodd" fill-rule="evenodd" d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z"></path>
      </svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between">
    <div class="flex items-center gap-2">
      <h2 class="text-lg font-medium">Teams</h2>
      <button class="flex items-center justify-center w-6 h-6 rounded-sm transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-800">
        <svg width="18" height="18" viewBox="0 0 24 24" stroke-width="2" fill="none" xmlns="http://www.w3.org/2000/svg" color="currentColor"><path d="M14.3632 5.65156L15.8431 4.17157C16.6242 3.39052 17.8905 3.39052 18.6716 4.17157L20.0858 5.58579C20.8668 6.36683 20.8668 7.63316 20.0858 8.41421L18.6058 9.8942M14.3632 5.65156L4.74749 15.2672C4.41542 15.5993 4.21079 16.0376 4.16947 16.5054L3.92738 19.2459C3.87261 19.8659 4.39148 20.3848 5.0115 20.33L7.75191 20.0879C8.21972 20.0466 8.65806 19.8419 8.99013 19.5099L18.6058 9.8942M14.3632 5.65156L18.6058 9.8942" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg>
      </button>
    </div>
    <div class="flex items-center gap-2">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z"></path>
      </svg>
      <span class="font-medium mt-1">8</span>
    </div>
  </header>
  <section class="mt-4 flex items-center gap-1">
    <button class="h-6 text-xs px-2 font-medium rounded-full flex items-center border dark:border-gray-900">#087</button>
    <button class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-rose-200 dark:border-gray-900 bg-rose-200 text-rose-700 dark:bg-rose-500/30 dark:text-rose-300">#3593</button>
    <button class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-emerald-200 dark:border-gray-900 bg-emerald-200 text-emerald-700 dark:bg-emerald-500/30 dark:text-emerald-300">Done</button>
  </section>
  <section class="flex items-center justify-between mt-4">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <span class="flex items-center justify-center font-medium w-6 h-6 text-xs rounded-full bg-indigo-200 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950">+4</span>
        </a>
      </dd>
    </div>
    <button class="w-8 h-8 flex items-center justify-center rounded-full border-2 border-dashed text-gray-600 border-gray-300 dark:border-gray-700">
      <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"></path>
      </svg>
    </button>
    <div class="flex items-center gap-1 text-gray-600">
      <svg width="16" height="16" fill="none" stroke-width="2.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z"></path>
      </svg>
      <span class="font-medium mt-[1px]">23</span>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-start justify-between">
    <h2 class="text-base font-medium"> Create calendar and autentication </h2>
    <div class="flex items-center gap-2 mt-0.5">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 0 0-3.375-3.375h-1.5A1.125 1.125 0 0 1 13.5 7.125v-1.5a3.375 3.375 0 0 0-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 0 0-9-9Z"></path>
      </svg>
      <span class="font-medium mt-1">8</span>
    </div>
  </header>
  <section class="mt-4 flex items-center gap-1">
    <button class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-fuchsia-200 dark:border-gray-900 bg-fuchsia-200 text-fuchsia-700 dark:bg-fuchsia-500/30 dark:text-fuchsia-300">Development</button>
    <button class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-amber-200 dark:border-gray-900 bg-amber-200 text-amber-700 dark:bg-amber-500/30 dark:text-amber-300">Backlog</button>
  </section>
  <section class="flex items-center justify-between mt-4">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/12.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/13.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/14.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <span class="flex items-center justify-center font-medium w-6 h-6 text-xs rounded-full bg-green-200 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950">+4</span>
        </a>
      </dd>
    </div>
    <button class="w-8 h-8 flex items-center justify-center rounded-full border-2 border-dashed text-gray-600 border-gray-300 dark:border-gray-700">
      <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"></path>
      </svg>
    </button>
    <div class="flex items-center gap-1 text-gray-600">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="16 3 21 8 8 21 3 21 3 16 16 3"></polygon></svg>
      <span class="font-medium mt-[2px]">17</span>
    </div>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between">
    <section class="flex items-center gap-1">
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-green-100 dark:border-gray-900 bg-green-100 text-green-700 dark:bg-green-500/30 dark:text-green-300">Development</span>
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-cyan-100 dark:border-gray-900 bg-cyan-100 text-cyan-700 dark:bg-cyan-500/30 dark:text-cyan-300">Backlog</span>
    </section>
    <button class="inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="mt-2">
    <h2 class="text-base font-medium leading-snug">New collaborative project for the marketing team</h2>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <section class="flex items-center justify-between">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/65.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/67.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/68.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <span class="text-xs flex items-center justify-center w-6 h-6 rounded-full bg-black text-white ring-2 ring-white dark:bg-white dark:text-black dark:ring-gray-950">+4</span>
        </a>
      </dd>
    </div>
    <button class="flex-none w-8 h-8 flex items-center justify-center rounded-full bg-gray-200 dark:bg-gray-700">
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.44 11.05l-9.19 9.19a6 6 0 0 1-8.49-8.49l9.19-9.19a4 4 0 0 1 5.66 5.66l-9.2 9.19a2 2 0 0 1-2.83-2.83l8.49-8.48"></path></svg>
    </button>
    <button class="flex items-center justify-center border px-3 h-7 rounded dark:border-gray-900">
      Create
    </button>
    <div class="flex items-center gap-1 text-gray-600">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="16 3 21 8 8 21 3 21 3 16 16 3"></polygon></svg>
      <span class="font-medium mt-[2px]">17</span>
    </div>
  </section>
</article>

<section class="mb-3 grid grid-cols-3 gap-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col items-center justify-center gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex flex-col items-center justify-start">
      <div class="flex items-center justify-center w-9 h-9 rounded-full text-indigo-500 bg-gray-200 dark:bg-gray-900">
        <svg width="20" height="20" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="M7 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6ZM14.5 9a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5ZM1.615 16.428a1.224 1.224 0 0 1-.569-1.175 6.002 6.002 0 0 1 11.908 0c.058.467-.172.92-.57 1.174A9.953 9.953 0 0 1 7 18a9.953 9.953 0 0 1-5.385-1.572ZM14.5 16h-.106c.07-.297.088-.611.048-.933a7.47 7.47 0 0 0-1.588-3.755 4.502 4.502 0 0 1 5.874 2.636.818.818 0 0 1-.36.98A7.465 7.465 0 0 1 14.5 16Z"></path>
        </svg>
      </div>
      <h2 class="font-medium mt-1">465+</h2>
      <p class="text-xs text-gray-500 dark:text-gray-400">Followers</p>
    </header>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col items-center justify-center gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex flex-col items-center justify-start">
      <div class="flex items-center justify-center w-9 h-9 rounded-full text-indigo-500 bg-gray-200 dark:bg-gray-900">
        <svg width="20" height="20" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path clip-rule="evenodd" fill-rule="evenodd" d="M4.25 2A2.25 2.25 0 0 0 2 4.25v11.5A2.25 2.25 0 0 0 4.25 18h11.5A2.25 2.25 0 0 0 18 15.75V4.25A2.25 2.25 0 0 0 15.75 2H4.25Zm4.03 6.28a.75.75 0 0 0-1.06-1.06L4.97 9.47a.75.75 0 0 0 0 1.06l2.25 2.25a.75.75 0 0 0 1.06-1.06L6.56 10l1.72-1.72Zm4.5-1.06a.75.75 0 1 0-1.06 1.06L13.44 10l-1.72 1.72a.75.75 0 1 0 1.06 1.06l2.25-2.25a.75.75 0 0 0 0-1.06l-2.25-2.25Z"></path>
        </svg>
      </div>
      <h2 class="font-medium mt-1">9+</h2>
      <p class="text-xs text-gray-500 dark:text-gray-400">Projects</p>
    </header>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col items-center justify-center gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex flex-col items-center justify-start">
      <div class="flex items-center justify-center w-9 h-9 rounded-full text-indigo-500 bg-gray-200 dark:bg-gray-900">
        <svg width="20" height="20" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path clip-rule="evenodd" fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z"></path>
        </svg>
      </div>
      <h2 class="font-medium mt-1">5.0</h2>
      <p class="text-xs text-gray-500 dark:text-gray-400">Rating</p>
    </header>
  </article>
</section>


<article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="relative w-full mb-auto">
    <img class="w-full max-w-full h-[6rem] object-cover" src="https://images.pexels.com/photos/185576/pexels-photo-185576.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Timur Saglambilek" alt="portada" data-author-profile="https://www.pexels.com/es-es/@marketingtuig/"/>
    <div class="flex flex-col p-4 relative -mt-10 z-[1]">
      <img class="flex-none w-14 h-14 rounded-full ring-4 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/20.jpg" alt="avatar" loading="lazy" />
      <div class="mt-2">
        <h2 class="font-semibold text-base">Hendrik</h2>
        <p class="text-gray-500">Director of Marketing</p>
      </div>
    </div>
  </header>
  <section class="flex items-start justify-between px-4">
    <section class="flex items-center gap-1 flex-wrap">
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-green-100 dark:border-gray-900 bg-green-100 text-green-700 dark:bg-green-500/30 dark:text-green-300">
        Development
      </span>
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-amber-100 dark:border-gray-900 bg-amber-100 text-amber-700 dark:bg-amber-500/30 dark:text-amber-300">
        Design
      </span>
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-cyan-100 dark:border-gray-900 bg-cyan-100 text-cyan-700 dark:bg-cyan-500/30 dark:text-cyan-300">
        Backlog
      </span>
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-rose-100 dark:border-gray-900 bg-rose-100 text-rose-700 dark:bg-rose-500/30 dark:text-rose-300">
        News
      </span>
      <span class="h-6 text-xs px-2 font-medium rounded-full flex items-center border border-indigo-100 dark:border-gray-900 bg-indigo-100 text-indigo-700 dark:bg-indigo-500/30 dark:text-indigo-300">
        Web
      </span>
    </section>
    <button class="flex-none inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </section>
  <section class="mt-3 px-4">
    <h2 class="text-base font-medium">New collaborative project for the marketing team</h2>
  </section>
  <section class="border-t p-4 flex items-center justify-between mt-4 dark:border-gray-800">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/65.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/67.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/68.jpg" alt="avatar" loading="lazy" />
        </a>
      </dd>
    </div>
    <div class="flex items-center gap-3">
      <button class="flex items-center gap-1 text-gray-600">
        <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M12 20.25c4.97 0 9-3.694 9-8.25s-4.03-8.25-9-8.25S3 7.444 3 12c0 2.104.859 4.023 2.273 5.48.432.447.74 1.04.586 1.641a4.483 4.483 0 0 1-.923 1.785A5.969 5.969 0 0 0 6 21c1.282 0 2.47-.402 3.445-1.087.81.22 1.668.337 2.555.337Z"></path>
        </svg>
        <span class="font-medium mt-[2px]">2</span>
      </button>
      <button class="flex items-center gap-1 text-gray-600">
        <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z"></path>
        </svg>
        <span class="font-medium mt-[2px]">8</span>
      </button>
      <button class="flex items-center gap-1 text-gray-600">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="16 3 21 8 8 21 3 21 3 16 16 3"></polygon></svg>
        <span class="font-medium mt-[2px]">11</span>
      </button>
    </div>
  </section>
</article>

<article class="border break-inside flex flex-col items-start relative overflow-hidden rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute left-1/2 top-0 w-14 h-14 bg-rose-500/30 blur-2xl"></div>
  <div class="absolute right-0 top-0 w-14 h-14 bg-yellow-500/40 blur-2xl"></div>
  <header class="flex items-center w-full">
    <svg width="28" height="28" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 0 1 4.5 9.75h15A2.25 2.25 0 0 1 21.75 12v.75m-8.69-6.44-2.12-2.12a1.5 1.5 0 0 0-1.061-.44H4.5A2.25 2.25 0 0 0 2.25 6v12a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18V9a2.25 2.25 0 0 0-2.25-2.25h-5.379a1.5 1.5 0 0 1-1.06-.44Z"></path>
    </svg>
  </header>
  <section class="mt-4 space-y-1">
    <h2 class="text-lg font-semibold block">Your <span class="text-rose-500">favorite</span> pack</h2>
    <p class="text-sm text-gray-600 dark:text-gray-300">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod...</p>
  </section>
</article>

<article class="border break-inside flex flex-col items-start relative overflow-hidden rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute left-1/2 top-0 w-14 h-14 bg-indigo-500/30 blur-2xl"></div>
  <div class="absolute right-0 top-0 w-14 h-14 bg-green-500/40 blur-2xl"></div>
  <header class="flex items-center w-full">
    <svg width="28" height="28" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
    </svg>
  </header>
  <section class="mt-4 space-y-1">
    <h2 class="text-lg font-semibold block"><span class="text-indigo-500">Upgrading</span> to Pro</h2>
    <p class="text-sm text-gray-600 dark:text-gray-300">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod...</p>
  </section>
</article>

<article class="shadow-sm break-inside relative overflow-hidden group flex items-center justify-between rounded-xl p-[1px] mb-3 text-sm " data-filter="social">
  <div class="absolute -top-4 -left-4 -right-8 -bottom-4 flex z-0 blur-md transition-all duration-700 group-hover:rotate-180">
    <div class="flex-1 bg-rose-600"></div>
    <div class="flex-1 bg-violet-600"></div>
    <div class="flex-1 bg-indigo-600"></div>
    <div class="flex-1 bg-blue-600"></div>
    <div class="flex-1 bg-emerald-600"></div>
    <div class="flex-1 bg-amber-600"></div>
    <div class="flex-1 bg-rose-600"></div>
    <div class="flex-1 bg-green-600"></div>
    <div class="flex-1 bg-green-600"></div>
    <div class="flex-1 bg-green-600"></div>
    <div class="flex-1 bg-green-600"></div>
  </div>
  <div class="flex items-atart gap-4 z-[1] p-4 relative overflow-hidden rounded-xl bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <div class="absolute left-0 bottom-0 w-14 h-14 bg-lime-500/60 blur-2xl"></div>
    <div class="flex-none mt-1">
      <svg width="32" height="32" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 21v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21m0 0h4.5V3.545M12.75 21h7.5V10.75M2.25 21h1.5m18 0h-18M2.25 9l4.5-1.636M18.75 3l-1.5.545m0 6.205 3 1m1.5.5-1.5-.5M6.75 7.364V3h-3v18m3-13.636 10.5-3.819"></path>
      </svg>
    </div>
    <div class="flex-1">
      <h2 class="text-lg font-semibold block">
        <span class="text-green-500"> Upgrading</span> 
        now your
        <br />
        organization
      </h2>
      <p class="text-sm text-gray-600 dark:text-gray-300">Lorem ipsum dolor sit amet, consectetur adipiscing...</p>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <section class="flex items-center justify-between gap-2">
    <div class="flex flex-col shadow rounded-lg overflow-hidden w-full max-w-[3rem]">
      <div class="flex items-center justify-center font-medium py-1 uppercase text-xs bg-rose-500 text-white">
        ENE
      </div>
      <div class="flex items-center justify-center font-medium text-sm py-1 dark:bg-gray-900">
        18
      </div>
    </div>
    <svg class="flex-none" width="24" height="24" fill="none" stroke-width="2.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"></path>
    </svg>
    <div class="flex flex-col shadow rounded-lg overflow-hidden w-full max-w-[3rem]">
      <div class="flex items-center justify-center font-medium py-1 uppercase text-xs bg-rose-500 text-white">
        ENE
      </div>
      <div class="flex items-center justify-center font-medium text-sm py-1 dark:bg-gray-900">
        28
      </div>
    </div>
    <header class="flex flex-col gap1">
      <h2 class="text-base font-semibold block">Vacations</h2>
      <p class="text-sm">You have 10 days</p>
    </header>
  </section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center justify-between w-full gap-6">
    <section class="flex items-center justify-between w-full flex-1 gap-3">
      <div class="flex flex-col shadow rounded-xl overflow-hidden flex-1">
        <div class="flex items-center justify-center font-medium py-1 uppercase text-xs bg-gray-500 text-white">
          SEP
        </div>
        <div class="flex items-center justify-center font-medium text-sm py-1 dark:bg-gray-900">
          05
        </div>
      </div>
      <svg class="flex-none" width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"></path>
      </svg>
      <div class="flex flex-col shadow rounded-xl overflow-hidden flex-1">
        <div class="flex items-center justify-center font-medium py-1 uppercase text-xs bg-gray-500 text-white">
          SEP
        </div>
        <div class="flex items-center justify-center font-medium text-sm py-1 dark:bg-gray-900">
          20
        </div>
      </div>
      <header class="flex flex-col gap1">
        <h2 class="text-sm font-medium block">Vacations</h2>
        <p class="text-sm text-gray-500">15 days</p>
      </header>
    </section>
    <button class="flex flex-none items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg class="flex-none" width="20" height="20" fill="none" stroke-width="2.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"></path>
      </svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside relative overflow-hidden flex flex-col items-start rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute left-0 bottom-0 w-14 h-14 bg-lime-500/50 blur-2xl"></div>
  <div class="absolute right-0 top-0 w-14 h-14 bg-amber-500/20 blur-2xl"></div>
  <section class="relative flex justify-start items-start gap-3">
    <figure class="relative flex-none w-14 h-14">
      <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/women/67.jpg" alt="avatar" loading="lazy" />
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <div class="flex flex-col">
      <h2 class="font-medium text-base">Marina</h2>
      <p class="text-xs text-gray-500 dark:text-gray-400">Human Resources</p>
      <p class="text-xs">The requested vacation has been approved</p>
    </div>
  </section>
  <section class="relative flex items-center justify-between gap-6 w-full mt-4">
    <div class="flex flex-col shadow rounded-lg overflow-hidden w-full">
      <div class="flex items-center justify-center font-medium py-1.5 uppercase text-xs bg-lime-500 text-white">
        September
      </div>
      <div class="flex items-center justify-center font-bold text-sm py-1.5 bg-white dark:bg-gray-900">
        2
      </div>
    </div>
    <svg class="flex-none" width="24" height="24" fill="none" stroke-width="2.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"></path>
    </svg>
    <div class="flex flex-col shadow rounded-lg overflow-hidden w-full">
      <div class="flex items-center justify-center font-medium py-1.5 uppercase text-xs bg-lime-500 text-white">
        September
      </div>
      <div class="flex items-center justify-center font-bold text-sm py-1.5 bg-white dark:bg-gray-900">
        14
      </div>
    </div>
  </section>
</article>

<section class="grid grid-cols-4 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="flex items-center justify-center font-medium py-2 uppercase text-xs bg-lime-500 text-white">
      Sep
    </div>
    <div class="flex items-center flex-col justify-center text-center gap-1 text-sm p-1.5 bg-white dark:bg-gray-900">
      <span class="border w-8 h-8 rounded-full flex items-center justify-center font-bold dark:border-gray-800">8</span>
    </div>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="flex items-center justify-center font-medium py-2 uppercase text-xs bg-indigo-500 text-white">
      Jan
    </div>
    <div class="flex items-center flex-col justify-center text-center gap-1 text-sm p-1.5 bg-white dark:bg-gray-900">
      <span class="border w-8 h-8 rounded-full flex items-center justify-center font-bold dark:border-gray-800">11</span>
    </div>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="flex items-center justify-center font-medium py-2 uppercase text-xs bg-rose-500 text-white">
      Feb
    </div>
    <div class="flex items-center flex-col justify-center text-center gap-1 text-sm p-1.5 bg-white dark:bg-gray-900">
      <span class="border w-8 h-8 rounded-full flex items-center justify-center font-bold dark:border-gray-800">23</span>
    </div>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="flex items-center justify-center font-medium py-2 uppercase text-xs bg-emerald-500 text-white">
      Mar
    </div>
    <div class="flex items-center flex-col justify-center text-center gap-1 text-sm p-1.5 bg-white dark:bg-gray-900">
      <span class="border w-8 h-8 rounded-full flex items-center justify-center font-bold dark:border-gray-800">9</span>
    </div>
  </article>
</section>

<article class="border shadow-sm break-inside rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between gap-2">
    <div class="flex items-center gap-3">
      <div class="flex-none w-12 h-12 flex items-center justify-center rounded-full border">
        <svg width="24" height="24" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5m.75-9 3-3 2.148 2.148A12.061 12.061 0 0 1 16.5 7.605"></path>
        </svg>
      </div>
      <div class="flex flex-col">
        <h2 class="font-medium text-base">Analytics</h2>
        <p class="text-xs">Loerm ipsum permiso flinte lor dolor sit amet...</p>
      </div>
    </div>
    <input type="checkbox" checked class="h-[20px] px-[3px] w-[38px] relative flex-none cursor-pointer appearance-none rounded-full bg-gray-300 dark:bg-gray-700 before:transition-transform before:duration-200 before:pointer-events-none before:absolute before:top-1/2 before:-translate-y-1/2 before:h-4 before:w-4 before:rounded-full before:bg-transparent before:content-[''] before:transform before:translate-x-0 before:bg-white focus:bg-gray-400 dark:focus:bg-gray-600 focus:checked:bg-blue-600 checked:bg-blue-600 checked:before:translate-x-full checked:before:bg-white" />
  </header>
</article>

<article class="border shadow-sm break-inside rounded-xl p-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between gap-2">
    <div class="flex items-center gap-3">
      <div class="flex-none w-6 h-6 flex items-center justify-center rounded-full bg-rose-200 text-rose-800 dark:bg-rose-600/40 dark:text-rose-300">
        2
      </div>
      <h2 class="font-medium text-base">My assignment</h2>
    </div>
    <button class="inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
</article>

<article class="break-inside rounded-xl p-2 mb-3 text-sm bg-emerald-100 dark:bg-emerald-600/30 dark:text-emerald-200" data-filter="social">
  <header class="flex items-center justify-between gap-2">
    <div class="flex items-center gap-3">
      <div class="flex-none w-6 h-6 flex items-center justify-center rounded-full bg-emerald-500 text-white">
        4
      </div>
      <h2 class="font-medium text-base">Assignment</h2>
    </div>
    <button class="inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-black/10 dark:hover:bg-white/10">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
</article>

<article class="shadow-sm relative break-inside rounded-xl overflow-hidden mb-3 text-sm max-h-[10rem]" data-filter="social">
  <button class="absolute top-4 right-4 inline-flex items-center justify-center w-8 h-8 transition-all rounded-full text-white hover:bg-black/20">
    <svg width="28" height="28" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
  <img src="https://images.pexels.com/photos/14469514/pexels-photo-14469514.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Aldair Nuñez" data-author-profile="https://www.pexels.com/es-es/@aldairwow/">
  <div class="absolute bottom-0 left-0 w-full p-4 bg-gradient-to-t from-black to-transparent text-white">
    <div class="flex items-center gap-3">
      <figure class="relative w-10 h-10">
        <img class="flex-none w-full rounded-full" src="https://randomuser.me/api/portraits/women/18.jpg" alt="avatar" loading="lazy" />
        <figcaption class="sr-only">Avatar</figcaption>
      </figure>
      <div class="flex-auto">
        <a href="#" class="text-base font-medium block">Anna</a>
        <span class="text-sm text-gray-200">Industrial Designer</span>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl overflow-hidden mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <button class="absolute top-4 right-4 inline-flex items-center justify-center w-8 h-8 transition-all rounded-full text-white hover:bg-black/20">
    <svg width="28" height="28" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
  <img class="w-full max-w-full h-24 object-cover" src="https://images.pexels.com/photos/92866/pexels-photo-92866.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Leonie Fahjen" data-author-profile="https://www.pexels.com/es-es/@leonie-fahjen-20345/">
  <div class="p-4 relative">
    <figure class="relative w-14 h-14 -mt-12">
      <img class="flex-none w-full rounded-full border-4 border-white" src="https://randomuser.me/api/portraits/women/20.jpg" alt="avatar" loading="lazy" />
      <figcaption class="sr-only">Avatar</figcaption>
    </figure>
    <div class="w-full mt-1">
      <div class="flex items-center justify-between gap-3">
        <div class="flex-auto">
          <a href="#" class="text-base font-medium block">Alexandra Flik</a>
          <span class="text-sm">Designer</span>
        </div>
        <button class="flex items-center justify-center cursor-pointer rounded-full h-7 px-3 text-sm bg-indigo-600 text-white">Follow</button>
      </div>
    </div>
  </div>
</article>

<section class="grid grid-cols-12 gap-3 mb-3">
  <article class="col-span-4 border shadow-sm break-inside relative overflow-hidden flex items-start flex-col justify-between rounded-xl gap-2 p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="absolute right-0 top-0 w-12 h-12 bg-rose-500/40 blur-2xl"></div>
    <img class="flex-none rounded-full w-11 h-11" src="https://randomuser.me/api/portraits/men/77.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Frank Mendes</h2>
    <button class="flex items-center justify-center cursor-pointer rounded-full h-7 px-3 w-full text-sm bg-blue-700 text-white">Edit</button>
  </article>
  <label html-for="user-1" class="cursor-pointer col-span-5 border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/85.jpg" alt="avatar" loading="lazy" />
    <div>
      <h2 class="text-base font-medium">Amanda</h2>
      <p class="text-xs">23 years old</p>
    </div>
    <p class="text-xs">Enable user for project</p>
    <input type="checkbox" name="user-1" checked="" class="h-[16px] px-[3px] w-[30px] relative flex-none cursor-pointer appearance-none rounded-full bg-gray-300 dark:bg-gray-700 before:transition-transform before:duration-200 before:pointer-events-none before:absolute before:top-1/2 before:-translate-y-1/2 before:h-3 before:w-3 before:rounded-full before:bg-transparent before:content-[''] before:transform before:translate-x-0 before:bg-white focus:bg-gray-400 dark:focus:bg-gray-600 focus:checked:bg-green-600 checked:bg-green-600 checked:before:translate-x-full checked:before:bg-white">
  </label>
  <article class="col-span-3 border shadow-sm break-inside flex items-center justify-between flex-col rounded-xl gap-2 p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-10 h-10 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/67.jpg" alt="avatar" loading="lazy" />
    <button class="inline-flex items-center justify-center w-8 h-8 transition-all rounded-full border hover:bg-black/10 dark:hover:bg-white/10">
      <svg width="18" height="18" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"></path>
      </svg>
    </button>
    <button class="inline-flex items-center justify-center w-8 h-8 transition-all rounded-full border hover:bg-black/10 dark:hover:bg-white/10">
      <svg width="18" height="18" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"></path>
      </svg>
    </button>
  </article>
  <article class="col-span-5 border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    a
  </article>
  <article class="col-span-3 border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    a
  </article>
  <article class="col-span-4 border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    a
  </article>
</section>

<article class="border shadow-sm overflow-hidden break-inside grid grid-cols-12 rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img class="w-full max-w-full h-full object-cover col-span-4" src="https://images.pexels.com/photos/708488/pexels-photo-708488.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Sydney Troxell" data-author-profile="https://www.pexels.com/es-es/@sydney-troxell-223521" loading="lazy" />
  <div class="p-3 flex flex-col col-span-8">
    <a href="#" class="text-base font-semibold block">Jhoanna Millers</a>
    <span class="text-gray-600 dark:text-gray-400">Auxiliar</span>
  </div>
</article>

<article class="border shadow-sm overflow-hidden break-inside grid grid-cols-12 rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img class="w-full max-w-full h-full object-cover col-span-4" src="https://images.pexels.com/photos/991678/pexels-photo-991678.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Tan Danh" data-author-profile="https://www.pexels.com/es-es/@dtanpt/" loading="lazy" />
  <div class="p-4 col-span-8">
    <img class="flex-none mt-1 w-12 h-12 rounded-full ring-2 ring-emerald-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar" loading="lazy" />
    <div class="flex flex-col mt-2">
      <a href="#" class="text-base font-semibold block">Jhonathan</a>
      <span class="text-gray-600 dark:text-gray-400">Frontend Development</span>
    </div>
  </div>
</article>

<article class="border shadow-sm overflow-hidden break-inside grid grid-cols-12 rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img class="w-full max-w-full h-[8rem] object-cover col-span-5" src="https://images.pexels.com/photos/3182452/pexels-photo-3182452.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Alex Azabache" data-author-profile="https://www.pexels.com/es-es/@alexazabache/" loading="lazy" />
  <div class="h-full flex items-center col-span-7">
    <div class="p-4 flex items-center gap-3 relative -ml-[3rem]">
      <img class="flex-none mt-1 w-14 h-14 rounded-full border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/95.jpg" alt="avatar" loading="lazy" />
      <div class="flex flex-col">
        <a href="#" class="text-base font-semibold block">Roman</a>
        <span class="text-gray-600 dark:text-gray-400">Photographer</span>
      </div>
    </div>
  </div>
</article>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/81.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Natalia G.</h2>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Bruce W.</h2>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Marcos</h2>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/men/81.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Andres</h2>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-11 h-11 rounded-full" src="https://randomuser.me/api/portraits/men/94.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Hendrix</h2>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center justify-between p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-2">
      <img class="flex-none w-7 h-7 rounded-full" src="https://randomuser.me/api/portraits/men/21.jpg" alt="avatar" loading="lazy" />
      <h2 class="text-sm font-medium">Duarte</h2>
    </header>
    <button class="flex flex-none items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="18" height="18" viewBox="0 0 24 24" stroke-width="2" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M14.3632 5.65156L15.8431 4.17157C16.6242 3.39052 17.8905 3.39052 18.6716 4.17157L20.0858 5.58579C20.8668 6.36683 20.8668 7.63316 20.0858 8.41421L18.6058 9.8942M14.3632 5.65156L4.74749 15.2672C4.41542 15.5993 4.21079 16.0376 4.16947 16.5054L3.92738 19.2459C3.87261 19.8659 4.39148 20.3848 5.0115 20.33L7.75191 20.0879C8.21972 20.0466 8.65806 19.8419 8.99013 19.5099L18.6058 9.8942M14.3632 5.65156L18.6058 9.8942" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
      </svg>
    </button>
  </article>
  <article class="relative rounded-full bg-gray-100 dark:bg-gray-900" data-filter="social">
    <div class="relative -top-1 -left-1 rotate-3 border shadow-lg break-inside rounded-full flex items-center justify-between p-1.5 gap-2 text-sm bg-white dark:bg-gray-700 dark:text-white dark:border-gray-700">
      <header class="flex items-center gap-2">
      <img class="flex-none w-7 h-7 rounded-full" src="https://randomuser.me/api/portraits/men/11.jpg" alt="avatar" loading="lazy" />
      <h2 class="text-sm font-medium">Manolo</h2>
    </header>
    <button class="flex flex-none items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
    </button>
    </div>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center justify-between p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-2">
      <img class="flex-none w-7 h-7 rounded-full" src="https://randomuser.me/api/portraits/men/21.jpg" alt="avatar" loading="lazy" />
      <h2 class="text-xs font-medium">Jhon M.</h2>
    </header>
    <button class="flex flex-none items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0"></path>
      </svg>
    </button>
  </article>
  <article class="border shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/41.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Cristina</h2>
  </article>
  <article class="shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm text-white bg-gradient-to-tr from-rose-600 to-amber-500" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/11.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Fabiola</h2>
  </article>
  <article class="shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm text-white bg-gradient-to-bl from-lime-400 via-emerald-500 to-green-600" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/61.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Laritha</h2>
  </article>
  <article class="shadow-sm break-inside rounded-full flex items-center justify-between p-1.5 gap-2 text-sm text-white bg-gradient-to-tl from-pink-600 to-rose-600" data-filter="social">
    <header class="flex items-center gap-2">
      <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/men/51.jpg" alt="avatar" loading="lazy" />
      <h2 class="text-sm font-medium">Luis P.</h2>
    </header>
    <button class="flex flex-none items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-white/10 dark:hover:bg-gray-900">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0"></path>
      </svg>
    </button>
  </article>
  <article class="shadow-sm break-inside rounded-full flex items-center p-1.5 gap-2 text-sm text-white bg-gradient-to-tr from-blue-700 via-violet-800 to-fuchsia-900" data-filter="social">
    <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/men/41.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-sm font-medium">Ernesto</h2>
  </article>
  <div class="border-2 border-dashed border-rose-300 bg-rose-100 relative rounded-full h-[45px] dark:bg-rose-500/15 dark:border-rose-600/30">
    <article class="absolute -top-2 -left-2 w-full rotate-2 shadow-[2px_5px_13px_-4px_#c3005961_,_1px_-1px_6px_-1px_#04000024] break-inside rounded-full flex items-center justify-between p-1.5 gap-1 text-sm bg-white dark:bg-gray-950 dark:text-white" data-filter="social">
      <header class="flex items-center gap-1">
        <img class="flex-none w-8 h-8 rounded-full" src="https://randomuser.me/api/portraits/women/11.jpg" alt="avatar" loading="lazy" />
        <h2 class="text-sm font-medium">Martha</h2>
      </header>
      <button class="flex flex-none items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
        <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0"></path>
        </svg>
      </button>
    </article>
  </div>
</section>

<article class="relative group overflow-hidden shadow-sm break-inside rounded-xl p-[1px] mb-3 text-sm" data-filter="social">
  <div class="absolute -top-4 -left-4 -right-8 -bottom-4 flex z-0 blur-md transition-all duration-500 group-hover:rotate-180">
    <div class="flex-1 bg-amber-600"></div>
    <div class="flex-1 bg-rose-600"></div>
    <div class="flex-1 bg-red-600"></div>
    <div class="flex-1 bg-pink-600"></div>
    <div class="flex-1 bg-blue-600"></div>
    <div class="flex-1 bg-cyan-600"></div>
    <div class="flex-1 bg-green-600"></div>
  </div>
  <div class="flex items-center justify-between relative z-1 w-full rounded-xl p-4 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
    <div class="flex items-center gap-4">
      <div class="flex-none w-12 h-12 rounded-full flex items-center justify-center text-lg font-semibold bg-emerald-100 text-emerald-500 dark:bg-emerald-600/50 dark:text-white">
        <svg width="28" height="28" class="ionicon" viewBox="0 0 512 512">
          <path d="M430.11 347.9c-6.6-6.1-16.3-7.6-24.6-9-11.5-1.9-15.9-4-22.6-10-14.3-12.7-14.3-31.1 0-43.8l30.3-26.9c46.4-41 46.4-108.2 0-149.2-34.2-30.1-80.1-45-127.8-45-55.7 0-113.9 20.3-158.8 60.1-83.5 73.8-83.5 194.7 0 268.5 41.5 36.7 97.5 55 152.9 55.4h1.7c55.4 0 110-17.9 148.8-52.4 14.4-12.7 11.99-36.6.1-47.7z" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32"></path>
          <circle fill="currentColor" cx="144" cy="208" r="32"></circle>
          <circle fill="currentColor" cx="152" cy="311" r="32"></circle>
          <circle fill="currentColor" cx="224" cy="144" r="32"></circle>
          <circle fill="currentColor" cx="256" cy="367" r="48"></circle>
          <circle fill="currentColor" cx="328" cy="144" r="32"></circle>
        </svg>
      </div>
      <div class="flex-auto">
        <a href="#" class="text-base font-medium block">Fantastic Design</a>
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
  </div>
</article>

<article class="border group shadow-sm break-inside rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="grid grid-cols-12 gap-3">
    <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/women/54.jpg" alt="Avatar">
      </a>
      <span class="w-0.5 h-full rounded bg-gray-200"></span>
    </div>
    <div class="col-span-10">
      <div class="flex-1 relative">
        <button class="hidden absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full p-1 transition-all hover:bg-gray-200 dark:hover:bg-white/10">
          <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path></svg>
        </button>
        <div class="flex items-center">
          <a class="inline-block font-bold mr-2" href="#">Dianne Russell</a>
          <span class="text-xs text-gray-400">3 min ago</span>
        </div>
        <p class="text-xs"> Dolor sit ameteiusmod Dolor sit ameteiusmod 🐸conse tetur. </p>
        <div class="mt-1 flex items-center">
          <a class="inline-flex items-center py-2 mr-3" href="#">
            <span class="mr-2">
              <svg class="fill-rose-600" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 512 512"><path d="M256 448a32 32 0 01-18-5.57c-78.59-53.35-112.62-89.93-131.39-112.8-40-48.75-59.15-98.8-58.61-153C48.63 114.52 98.46 64 159.08 64c44.08 0 74.61 24.83 92.39 45.51a6 6 0 009.06 0C278.31 88.81 308.84 64 352.92 64c60.62 0 110.45 50.52 111.08 112.64.54 54.21-18.63 104.26-58.61 153-18.77 22.87-52.8 59.45-131.39 112.8a32 32 0 01-18 5.56z"/></svg>
            </span>
            <span class="font-bold">167</span>
          </a>
          <button class="py-1 px-4 font-medium transition-colors duration-300 hover:bg-gray-50 dark:hover:bg-white/10 rounded-md">Repply</button>
        </div>
      </div>
    </div>
  </div>
  <div class="grid grid-cols-12 gap-3 pt-2">
    <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/men/57.jpg" alt="Avatar">
      </a>
    </div>
    <div class="col-span-10">
      <div class="flex-1 relative">
        <button class="hidden absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full p-1 transition-all hover:bg-gray-200 dark:hover:bg-white/10">
          <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path></svg>
        </button>
        <div class="flex items-center">
          <a class="inline-block font-bold mr-2" href="#">Jhon</a>
          <span class="text-xs text-gray-400">3 min ago</span>
        </div>
        <p class="text-xs"> Dolor sit ametei usm odolor sit amet onse tetur. </p>
        <div class="mt-1 flex items-center">
          <a class="inline-flex items-center py-2 mr-3" href="#">
            <span class="mr-2">
              <svg class="fill-rose-600" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 512 512"><path d="M256 448a32 32 0 01-18-5.57c-78.59-53.35-112.62-89.93-131.39-112.8-40-48.75-59.15-98.8-58.61-153C48.63 114.52 98.46 64 159.08 64c44.08 0 74.61 24.83 92.39 45.51a6 6 0 009.06 0C278.31 88.81 308.84 64 352.92 64c60.62 0 110.45 50.52 111.08 112.64.54 54.21-18.63 104.26-58.61 153-18.77 22.87-52.8 59.45-131.39 112.8a32 32 0 01-18 5.56z"/></svg>
            </span>
            <span class="font-bold">8</span>
          </a>
          <button class="py-1 px-4 font-medium transition-colors duration-300 hover:bg-gray-50 dark:hover:bg-white/10 rounded-md">Repply</button>
        </div>
      </div>
    </div>
  </div>
</article>

<article class="border group shadow-sm break-inside rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="grid grid-cols-12 gap-3 p-3">
    <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/women/24.jpg" alt="Avatar">
      </a>
    </div>
    <div class="col-span-10">
      <div class="flex-1 relative">
        <button class="hidden absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full p-1 transition-all hover:bg-gray-200 dark:hover:bg-white/10">
          <svg width="22" height="22" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12,16A2,2 0 0,1 14,18A2,2 0 0,1 12,20A2,2 0 0,1 10,18A2,2 0 0,1 12,16M12,10A2,2 0 0,1 14,12A2,2 0 0,1 12,14A2,2 0 0,1 10,12A2,2 0 0,1 12,10M12,4A2,2 0 0,1 14,6A2,2 0 0,1 12,8A2,2 0 0,1 10,6A2,2 0 0,1 12,4Z" fill="currentColor"></path></svg>
        </button>
        <div class="flex items-center">
          <a class="inline-block font-bold mr-2" href="#">Carmen Ramsey</a>
          <span class="text-xs text-gray-400">3 min ago</span>
        </div>
        <p class="text-xs">
          Dolor sit 😂😂😂 smod
          <br />
          olor sit ame tetur.
        </p>
        <div class="flex items-center">
          <a class="inline-flex items-center py-2 mr-3" href="#">
            <span class="mr-2">
              <svg class="fill-rose-600" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 512 512"><path d="M256 448a32 32 0 01-18-5.57c-78.59-53.35-112.62-89.93-131.39-112.8-40-48.75-59.15-98.8-58.61-153C48.63 114.52 98.46 64 159.08 64c44.08 0 74.61 24.83 92.39 45.51a6 6 0 009.06 0C278.31 88.81 308.84 64 352.92 64c60.62 0 110.45 50.52 111.08 112.64.54 54.21-18.63 104.26-58.61 153-18.77 22.87-52.8 59.45-131.39 112.8a32 32 0 01-18 5.56z"/></svg>
            </span>
            <span class="font-bold">12</span>
          </a>
          <button class="py-1 px-4 font-medium transition-colors duration-300 hover:bg-gray-50 dark:hover:bg-white/10 rounded-md">Repply</button>
        </div>
      </div>
    </div>
  </div>
  <div class="p-2">
    <div class="relative h-[76px] border-2 border-dashed rounded-lg border-rose-200 bg-rose-50 dark:bg-rose-500/15 dark:border-rose-600/30">
      <div class="absolute -left-6 -top-4 rotate-2 grid grid-cols-12 gap-3 p-3 rounded-lg w-full max-w-[290px] shadow-[2px_5px_43px_-4px_#c3005961_,_1px_-1px_3px_-1px_#04000024] bg-white dark:bg-gray-900">
        <div class="flex flex-col gap-2 items-center flex-none h-full col-span-2">
          <a class="inline-block" href="#">
            <img class="rounded-full max-w-none w-9 h-9" src="https://randomuser.me/api/portraits/men/47.jpg" alt="Avatar">
          </a>
        </div>
        <div class="col-span-10">
          <div class="flex-1 relative">
            <button class="flex absolute right-0 top-0 group-hover:flex items-center justify-center rounded-full w-9 h-9 transition-all bg-rose-200 text-rose-700 hover:bg-rose-300 dark:bg-rose-500/20 dark:text-rose-400 dark:hover:bg-rose-500/30">
              <svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="1.5" width="20" height="20" class="text-current">
                <path class="stroke-current fill-none" d="M16.88,22.5H7.12a1.9,1.9,0,0,1-1.9-1.8L4.36,5.32H19.64L18.78,20.7A1.9,1.9,0,0,1,16.88,22.5Z"></path>
                <line class="stroke-current fill-none" x1="2.45" y1="5.32" x2="21.55" y2="5.32"></line>
                <path class="stroke-current fill-none" d="M10.09,1.5h3.82a1.91,1.91,0,0,1,1.91,1.91V5.32a0,0,0,0,1,0,0H8.18a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,10.09,1.5Z"></path>
                <line class="stroke-current fill-none" x1="12" y1="8.18" x2="12" y2="19.64"></line>
                <line class="stroke-current fill-none" x1="15.82" y1="8.18" x2="15.82" y2="19.64"></line>
                <line class="stroke-current fill-none" x1="8.18" y1="8.18" x2="8.18" y2="19.64"></line>
              </svg>
            </button>
            <div class="flex items-center">
              <a class="inline-block font-bold mr-2" href="#">Stephan Mills</a>
              <span class="text-xs text-gray-400">3 min ago</span>
            </div>
            <p class="text-xs">
              Dolor sit ametei usm odolor
              <br />
              sit amet onse tetur 
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl flex py-4 pl-0 pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-start gap-4">
    <span class="w-1.5 h-full rounded-full bg-green-600"></span>
    <div class="flex flex-col">
      <div class="flex items-center justify-between">
        <h2 class="font-medium text-lg">Reunión</h2>
        <span class="text-xs text-gray-500">10:00 AM</span>
      </div>
      <div class="flex items-center justify-between gap-4">
        <p class="text-xs">Loren ipsum dolor sit amet, conct etur adip iscing elit.</p>
        <button class="flex items-center justify-center cursor-pointer rounded-full h-7 px-3 text-sm bg-indigo-600 text-white">Join</button>
      </div>
    </div>
  </header>
</article>

<section class="grid grid-cols-2 gap-4">
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header>
      <svg width="26" height="26" viewBox="0 0 512 512"><path d="M384 240H96V136a40.12 40.12 0 0140-40h240a40.12 40.12 0 0140 40v104zM48 416V304a64.19 64.19 0 0164-64h288a64.19 64.19 0 0164 64v112" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><path d="M48 416v-8a24.07 24.07 0 0124-24h368a24.07 24.07 0 0124 24v8M112 240v-16a32.09 32.09 0 0132-32h80a32.09 32.09 0 0132 32v16M256 240v-16a32.09 32.09 0 0132-32h80a32.09 32.09 0 0132 32v16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
    </header>
    <section>
      <h2 class="text-base font-medium">Bed time</h2>
      <h3 class="text-lg font-semibold">10:00 PM</h3>
    </section>
    <p class="text-xs text-gray-500">Set your bedtime and wake up time...</p>
  </article>
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
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

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header>
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
    </header>
    <section>
      <h2 class="text-sm">Calendar</h2>
      <h3 class="text-base font-semibold">December, 24</h3>
    </section>
    <p class="text-xs text-gray-500">Set your bedtime and wake up time...</p>
  </article>
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header>
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3"></path></svg>
    </header>
    <section>
      <h2 class="text-sm">Interactions</h2>
      <h3 class="text-base font-semibold">Monday, 12</h3>
    </section>
    <div class="flex items-center justify-between w-full">
      <div class="col-start-2 row-start-1 row-end-3 flex-none">
        <dt class="sr-only">Users</dt>
        <dd class="flex justify-start -space-x-1.5">
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar" loading="lazy" />
          </a>
        </dd>
      </div>
      <h5 class="font-medium">+23</h5>
    </div>
  </article>
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header>
      <svg width="26" height="26" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" class="fill-rose-600">
        <path d="m9.653 16.915-.005-.003-.019-.01a20.759 20.759 0 0 1-1.162-.682 22.045 22.045 0 0 1-2.582-1.9C4.045 12.733 2 10.352 2 7.5a4.5 4.5 0 0 1 8-2.828A4.5 4.5 0 0 1 18 7.5c0 2.852-2.044 5.233-3.885 6.82a22.049 22.049 0 0 1-3.744 2.582l-.019.01-.005.003h-.002a.739.739 0 0 1-.69.001l-.002-.001Z"></path>
      </svg>
    </header>
    <section>
      <h2 class="text-sm">Events</h2>
      <h3 class="text-base font-semibold text-rose-600">Favorites</h3>
    </section>
    <div class="flex items-center justify-between w-full mt-3">
      <span class="flex items-center justify-center h-5 px-1 gap-1 rounded text-sm bg-red-100/90 text-red-600 dark:bg-red-600/40 dark:text-red-500">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 7l9.2 9.2M17 7v10H7"/></svg>
        <span class="text-xs mt-[1px] font-medium text-red-800 dark:text-red-500">15%</span>
      </span>
      <h5 class="font-medium">23</h5>
    </div>
  </article>
  <article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header>
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="2.18" ry="2.18"></rect><line x1="7" y1="2" x2="7" y2="22"></line><line x1="17" y1="2" x2="17" y2="22"></line><line x1="2" y1="12" x2="22" y2="12"></line><line x1="2" y1="7" x2="7" y2="7"></line><line x1="2" y1="17" x2="7" y2="17"></line><line x1="17" y1="17" x2="22" y2="17"></line><line x1="17" y1="7" x2="22" y2="7"></line></svg>
    </header>
    <section>
      <h2 class="text-sm">Visits</h2>
      <h3 class="text-base font-semibold">Best movies</h3>
    </section>
    <div class="flex items-center justify-between w-full mt-3">
      <span class="flex items-center justify-center h-5 px-1 gap-1 rounded text-sm bg-green-100/90 text-green-600 dark:bg-green-600/40 dark:text-green-500">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17l9.2-9.2M17 17V7H7"/></svg>
        <span class="text-xs mt-[1px] font-medium text-green-800 dark:text-green-500">15%</span>
      </span>
      <h5 class="font-medium">8</h5>
    </div>
  </article>
</section>

<section class="grid grid-cols-12 gap-3">
  <article class="relative col-span-7 border break-inside overflow-hidden flex flex-col justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="absolute z-0 top-4 right-4 w-16 h-16 bg-blue-500/30 blur-2xl" ></div>
    <header class="relative w-full mb-auto">
      <div class="flex flex-col">
        <img class="flex-none w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/men/20.jpg" alt="avatar" loading="lazy" />
        <div class="mt-2">
          <h2 class="font-semibold text-base">Hendrik</h2>
          <p class="text-gray-500">Software Developer</p>
        </div>
      </div>
      <button class="z-[1] w-9 h-9 absolute top-0 right-0 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 14 4" fill="none">
          <path d="M10.8889 2C10.8889 2.39782 11.0528 2.77936 11.3445 3.06066C11.6362 3.34196 12.0319 3.5 12.4444 3.5C12.857 3.5 13.2527 3.34196 13.5444 3.06066C13.8361 2.77936 14 2.39782 14 2C14 1.60218 13.8361 1.22064 13.5444 0.93934C13.2527 0.658035 12.857 0.5 12.4444 0.5C12.0319 0.5 11.6362 0.658035 11.3445 0.93934C11.0528 1.22064 10.8889 1.60217 10.8889 2ZM5.44444 2C5.44444 2.39782 5.60833 2.77935 5.90006 3.06066C6.19178 3.34196 6.58744 3.5 7 3.5C7.41256 3.5 7.80822 3.34196 8.09994 3.06066C8.39167 2.77935 8.55556 2.39782 8.55556 2C8.55556 1.60217 8.39167 1.22064 8.09994 0.93934C7.80822 0.658035 7.41256 0.499999 7 0.499999C6.58744 0.499999 6.19178 0.658035 5.90006 0.939339C5.60833 1.22064 5.44444 1.60217 5.44444 2ZM-1.31134e-07 2C-1.65913e-07 2.39782 0.163889 2.77935 0.455612 3.06066C0.747335 3.34196 1.143 3.5 1.55556 3.5C1.96811 3.5 2.36378 3.34196 2.6555 3.06066C2.94722 2.77935 3.11111 2.39782 3.11111 2C3.11111 1.60217 2.94722 1.22064 2.6555 0.939339C2.36378 0.658035 1.96811 0.499999 1.55556 0.499999C1.143 0.499999 0.747335 0.658034 0.455612 0.939339C0.163889 1.22064 -9.63552e-08 1.60217 -1.31134e-07 2Z" fill="currentColor"/>
        </svg>
      </button>
    </header>
    <section class="w-full mt-auto">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 111 71" fill="none">
        <path d="M0 39.4873C0 37.2782 1.79086 35.4873 4 35.4873H14C16.2091 35.4873 18 37.2782 18 39.4873V69.8646H0V39.4873Z" class="fill-gray-200 dark:fill-gray-700" />
        <path d="M23 24.2974C23 22.0882 24.7909 20.2974 27 20.2974H37C39.2091 20.2974 41 22.0882 41 24.2974V69.8646H23V24.2974Z" class="fill-gray-200 dark:fill-gray-700" />
        <path d="M46 50.6797C46 48.4705 47.7909 46.6797 50 46.6797H60C62.2091 46.6797 64 48.4705 64 50.6797V69.8644H46V50.6797Z" class="fill-gray-200 dark:fill-gray-700" />
        <path d="M69 4.31055C69 2.10141 70.7909 0.310547 73 0.310547H84C86.2091 0.310547 88 2.10141 88 4.31055V70.1553H69V4.31055Z" fill="#153fec"/>
        <path d="M93 15.5757C93 13.3665 94.7909 11.5757 97 11.5757H107C109.209 11.5757 111 13.3665 111 15.5757V70.1551H93V15.5757Z" class="fill-gray-200 dark:fill-gray-700" />
      </svg>
    </section>
  </article>
  <section class="grid grid-cols-1 col-span-5">
    <article class="border break-inside flex items-center justify-between rounded-xl p-2 mb-3 text-sm bg-green-100 border-green-100 dark:bg-green-600/30 dark:border-green-600/10 dark:text-green-400" data-filter="social">
      <header class="relative w-full">
        <div class="flex flex-col">
          <img class="flex-none w-9 h-9 rounded-full" src="https://randomuser.me/api/portraits/women/21.jpg" alt="avatar" loading="lazy" />
          <div class="mt-2">
            <h2 class="font-semibold text-base">Catherine</h2>
            <p class="text-black/60 dark:text-green-600">Director</p>
          </div>
        </div>
        <button class="w-7 h-7 absolute top-0 right-0 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
          <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 4" fill="none">
            <path d="M10.8889 2C10.8889 2.39782 11.0528 2.77936 11.3445 3.06066C11.6362 3.34196 12.0319 3.5 12.4444 3.5C12.857 3.5 13.2527 3.34196 13.5444 3.06066C13.8361 2.77936 14 2.39782 14 2C14 1.60218 13.8361 1.22064 13.5444 0.93934C13.2527 0.658035 12.857 0.5 12.4444 0.5C12.0319 0.5 11.6362 0.658035 11.3445 0.93934C11.0528 1.22064 10.8889 1.60217 10.8889 2ZM5.44444 2C5.44444 2.39782 5.60833 2.77935 5.90006 3.06066C6.19178 3.34196 6.58744 3.5 7 3.5C7.41256 3.5 7.80822 3.34196 8.09994 3.06066C8.39167 2.77935 8.55556 2.39782 8.55556 2C8.55556 1.60217 8.39167 1.22064 8.09994 0.93934C7.80822 0.658035 7.41256 0.499999 7 0.499999C6.58744 0.499999 6.19178 0.658035 5.90006 0.939339C5.60833 1.22064 5.44444 1.60217 5.44444 2ZM-1.31134e-07 2C-1.65913e-07 2.39782 0.163889 2.77935 0.455612 3.06066C0.747335 3.34196 1.143 3.5 1.55556 3.5C1.96811 3.5 2.36378 3.34196 2.6555 3.06066C2.94722 2.77935 3.11111 2.39782 3.11111 2C3.11111 1.60217 2.94722 1.22064 2.6555 0.939339C2.36378 0.658035 1.96811 0.499999 1.55556 0.499999C1.143 0.499999 0.747335 0.658034 0.455612 0.939339C0.163889 1.22064 -9.63552e-08 1.60217 -1.31134e-07 2Z" fill="currentColor"></path>
          </svg>
        </button>
      </header>
    </article>
    <div class="flex flex-col">
      <article class="border break-inside flex items-center justify-between rounded-xl p-2 mb-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
        <img class="flex-none w-7 h-7 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/20.jpg" alt="avatar" loading="lazy" />
        <div class="flex-col items-start flex-auto">
          <a href="#" class="text-xs font-medium block">Jhon Mills</a>
        </div>
      </article>
      <article class="border break-inside flex items-center justify-between rounded-xl p-2 mb-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
        <img class="flex-none w-7 h-7 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/60.jpg" alt="avatar" loading="lazy" />
        <div class="flex-col items-start flex-auto">
          <a href="#" class="text-xs font-medium block">Alejandra</a>
        </div>
      </article>
    </div>
  </section>
</section>

<article class="border shadow-sm break-inside rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-between items-center w-full">
    <div class="flex flex-col justify-center items-center py-1 px-3 border rounded dark:border-gray-900">
      <span class="font-medium">Jun</span>
      <span class="text-xs font-medium text-pink-500">23</span>
    </div>
    <img class="flex-none w-10 h-10 rounded-xl" src="https://randomuser.me/api/portraits/women/21.jpg" alt="avatar" loading="lazy" />
    <hr class="border h-6 border-gray-200 dark:border-gray-800">
    <div class="flex flex-col justify-center items-start">
      <span class="text-base font-medium">Wednesday</span>
      <span class="text-gray-400">08:00 PM - 18:30 PM</span>
    </div>
  </div>
</article>

<article class="relative border overflow-hidden shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute left-1/2 top-0 w-14 h-14 bg-rose-500/30 blur-2xl"></div>
  <div class="absolute left-0 top-0 w-14 h-14 bg-green-500/30 blur-2xl"></div>
  <div class="flex justify-between items-center w-full relative z-[1]">
    <div class="flex flex-col justify-center items-center w-12 h-12 rounded-full text-white bg-gray-900 dark:text-black dark:bg-gray-100">
      <span class="font-medium">Jun</span>
      <span class="text-xs font-medium">23</span>
    </div>
    <hr class="border h-6 border-gray-300 dark:border-gray-800">
    <div class="flex flex-col justify-center items-start">
      <span class="text-base font-medium">Thursday</span>
      <span class="text-xs text-gray-700 dark:text-gray-200">08:00 PM - 18:30 PM</span>
    </div>
    <button class="px-2 h-7 text-xs font-medium transition-colors duration-300 text-white bg-rose-500 rounded-md hover:bg-rose-600">
      Details
    </button>
  </div>
</article>

<article class="border shadow-md break-inside flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center gap-3">
    <span class="text-base font-medium">01</span>
    <div class="flex items-center gap-4">
      <img class="flex-none w-12 h-12 rounded-2xl" src="https://randomuser.me/api/portraits/women/82.jpg" alt="avatar" loading="lazy" />
      <div class="flex-auto">
        <span class="text-sm text-gray-600 dark:text-gray-300">September 2023</span>
        <h2 class="text-base font-medium block">Caroline</h2>
      </div>
    </div>
  </header>
  <svg width="22" height="22" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" class="fill-gray-900 dark:fill-gray-100">
    <path clip-rule="evenodd" fill-rule="evenodd" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12Zm13.36-1.814a.75.75 0 1 0-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 0 0-1.06 1.06l2.25 2.25a.75.75 0 0 0 1.14-.094l3.75-5.25Z"></path>
  </svg>
</article>

<article class="border shadow-md break-inside relative overflow-hidden flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute left-1/2 top-0 w-14 h-14 bg-rose-500/30 blur-2xl"></div>
  <header class="flex items-center gap-3">
    <span class="text-base font-medium">02</span>
    <div class="flex items-center gap-4">
      <img class="flex-none w-12 h-12 rounded-2xl" src="https://randomuser.me/api/portraits/women/24.jpg" alt="avatar" loading="lazy" />
      <div class="flex-auto">
        <span class="text-sm text-gray-600 dark:text-gray-300">September 2023</span>
        <h2 class="text-base font-medium block">Stephany</h2>
      </div>
    </div>
  </header>
  <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
  </svg>
</article>

<article class="border shadow-sm break-inside flex items-start justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-start gap-4">
    <div class="flex-none w-10 h-10 rounded-full flex items-center justify-center font-semibold text-base text-amber-700 bg-amber-200">AB</div>
    <div class="flex-auto">
      <h2 class="text-base font-medium block">Annette Black</h2>
      <p class="text-xs text-gray-600 dark:text-gray-300">Hi there! I'm a designer and developer from San Francisco.</p>
    </div>
  </header>
  <section class="flex flex-col items-center justify-between h-full gap-3 pt-1">
    <span class="text-xs font-medium text-gray-600 dark:text-gray-300">Today</span>
    <span class="flex flex-none items-center justify-center font-medium w-5 h-5 text-xs rounded-full transition-colors bg-rose-500 text-white"> 2 </span>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl gap-4 p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center gap-4">
    <img class="flex-none rounded-full w-12 h-12" src="https://randomuser.me/api/portraits/men/76.jpg" alt="avatar" loading="lazy" />
    <div class="flex-auto">
      <h2 class="font-medium block">Philip Johnson</h2>
      <p class="text-xs text-gray-600 dark:text-gray-300">Hi there! I'm a dog trainer from Oakland.</p>
    </div>
  </header>
  <section class="flex flex-col items-end justify-between h-full gap-1">
    <span class="text-xs font-medium mt-1 text-gray-600 dark:text-gray-300">Today</span>
    <button class="flex flex-none items-center justify-center font-medium w-7 h-7 text-xs rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900 text-gray-600 dark:text-gray-500">
      <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M11.294 0.983997L15.016 4.706C15.2153 4.90534 15.3634 5.14986 15.4479 5.41876C15.5324 5.68766 15.5506 5.97299 15.5012 6.25046C15.4517 6.52794 15.3359 6.78936 15.1637 7.01249C14.9915 7.23561 14.7679 7.41383 14.512 7.532L13.185 8.145C12.7616 8.3409 12.388 8.63018 12.0924 8.99112C11.7967 9.35205 11.5867 9.77527 11.478 10.229L10.894 12.683C10.577 14.015 8.922 14.483 7.954 13.515L5.75 11.311L1.78 15.28C1.7104 15.3496 1.62777 15.4048 1.53683 15.4425C1.44589 15.4801 1.34843 15.4995 1.25 15.4995C1.15157 15.4995 1.0541 15.4801 0.963165 15.4425C0.872227 15.4048 0.789599 15.3496 0.719999 15.28C0.650398 15.2104 0.595188 15.1278 0.55752 15.0368C0.519853 14.9459 0.500465 14.8484 0.500465 14.75C0.500465 14.6516 0.519853 14.5541 0.55752 14.4632C0.595188 14.3722 0.650398 14.2896 0.719999 14.22L4.689 10.25L2.485 8.046C1.517 7.078 1.985 5.423 3.317 5.106L5.771 4.522C6.22499 4.41394 6.64849 4.20413 7.00952 3.90842C7.37054 3.6127 7.65965 3.23882 7.855 2.815L8.468 1.488C8.58616 1.23211 8.76439 1.00854 8.98751 0.836323C9.21063 0.664104 9.47205 0.548328 9.74953 0.498841C10.027 0.449354 10.3123 0.467622 10.5812 0.552091C10.8501 0.63656 11.0947 0.78473 11.294 0.983997ZM6.283 9.723L9.015 12.454C9.04646 12.4855 9.08574 12.5079 9.1288 12.5192C9.17185 12.5304 9.21711 12.5299 9.25992 12.5177C9.30272 12.5056 9.34151 12.4823 9.37229 12.4502C9.40307 12.418 9.42472 12.3783 9.435 12.335L10.019 9.881C10.1801 9.20638 10.4921 8.57709 10.9315 8.04048C11.371 7.50387 11.9264 7.07392 12.556 6.783L13.884 6.17C13.9206 6.15313 13.9526 6.12766 13.9772 6.09576C14.0019 6.06387 14.0184 6.02648 14.0255 5.9868C14.0326 5.94712 14.03 5.90632 14.0178 5.86787C14.0057 5.82942 13.9845 5.79447 13.956 5.766L10.234 2.044C10.2055 2.01547 10.1706 1.99425 10.1321 1.98215C10.0937 1.97004 10.0529 1.96742 10.0132 1.97449C9.97351 1.98156 9.93613 1.99812 9.90423 2.02276C9.87233 2.0474 9.84686 2.07939 9.83 2.116L9.217 3.444C8.9262 4.0737 8.49629 4.6292 7.95966 5.06865C7.42303 5.50811 6.79367 5.82005 6.119 5.981L3.665 6.565C3.62171 6.57528 3.58196 6.59693 3.54983 6.6277C3.51771 6.65848 3.49438 6.69727 3.48225 6.74008C3.47012 6.78288 3.46964 6.82814 3.48084 6.8712C3.49205 6.91425 3.51454 6.95354 3.546 6.985L6.277 9.717L6.283 9.723Z" fill="currentColor"/>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-3">
    <img class="flex-none w-10 h-10 rounded-full" src="https://randomuser.me/api/portraits/women/44.jpg" alt="avatar" loading="lazy" />
    <div class="flex-auto">
      <a href="#" class="text-base font-semibold block">Yolanda</a>
      <span class="text-sm text-gray-600 dark:text-gray-300">Web Development</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-8 h-8 rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="20" height="20" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6 12 3.269 3.125A59.769 59.769 0 0 1 21.485 12 59.768 59.768 0 0 1 3.27 20.875L5.999 12Zm0 0h7.5"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <figure class="relative w-10 h-10">
      <img class="flex-none w-full rounded-full" src="https://randomuser.me/api/portraits/men/14.jpg" alt="avatar" loading="lazy" />
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Frederisck</a>
      <span class="text-sm text-gray-600 dark:text-gray-300">Industrial Designer</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-10 h-10 rounded-full transition-colors hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg fill="none" stroke-width="1.5" width="24" height="24" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.827 6.175A2.31 2.31 0 0 1 5.186 7.23c-.38.054-.757.112-1.134.175C2.999 7.58 2.25 8.507 2.25 9.574V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18V9.574c0-1.067-.75-1.994-1.802-2.169a47.865 47.865 0 0 0-1.134-.175 2.31 2.31 0 0 1-1.64-1.055l-.822-1.316a2.192 2.192 0 0 0-1.736-1.039 48.774 48.774 0 0 0-5.232 0 2.192 2.192 0 0 0-1.736 1.039l-.821 1.316Z"></path>
      <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 12.75a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0ZM18.75 10.5h.008v.008h-.008V10.5Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center gap-4">
    <img class="flex-none w-10 h-10 rounded-full" src="https://randomuser.me/api/portraits/women/81.jpg" alt="avatar" loading="lazy" />
    <div class="flex-auto">
      <a href="#" class="text-base font-medium block">Marina Flick</a>
      <span class="text-sm text-gray-600 dark:text-gray-400">Technical Director</span>
    </div>
  </div>
  <button class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-200 hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="20" height="20" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"></path>
    </svg>
  </button>
</article>

<article class="flex items-center justify-between rounded-md bg-white p-4 mb-3 shadow-black/5 ring-1 ring-slate-700/10 dark:text-white dark:bg-gray-950 dark:ring-white/10" data-filter="social">
  <section class="flex items-center gap-1">
    <button class="inline-flex items-center justify-center w-9 h-9 transition-colors duration-200 rounded-full hover:bg-black/5 dark:hover:bg-white/10">
      <svg width="24" height="24" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
      </svg>
    </button>
    <svg class="ml-6 h-10 w-10 flex-none" viewBox="0 0 40 40" fill="none">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M10.8322 6.12083C11.1486 5.56355 11.74 5.21924 12.3808 5.21924H27.1431C27.7322 5.21924 28.2831 5.51055 28.6148 5.99738L37.4718 18.9974C37.8542 19.5587 37.884 20.2887 37.5487 20.8793L30.1679 33.8793C29.8515 34.4366 29.2601 34.7809 28.6192 34.7809L12.3808 34.7809C11.74 34.7809 11.1486 34.4366 10.8322 33.8793L3.45137 20.8793C3.14178 20.334 3.14178 19.6661 3.45137 19.1208L10.8322 6.12083ZM12.3808 10.607L17.7138 20.0001L12.3808 29.3931L7.04787 20.0001L12.3808 10.607ZM15.4397 31.2192L27.5825 31.2192L32.9411 21.7809H20.7984L15.4397 31.2192ZM20.7984 18.2192H32.6319L26.2015 8.78092H15.4397L20.7984 18.2192Z" fill="#38BDF8"></path>
    </svg>
  </section>
  <section class="flex items-center gap-1 ml-6">
    <span class="text-[0.8125rem] font-medium text-gray-700">v3.0</span>
    <svg class="ml-2 h-1 w-1.5 overflow-visible fill-gray-400 stroke-gray-400">
      <path d="M0 0H6L3 4Z" stroke-width="1" stroke-linejoin="round"></path>
    </svg>
    <svg viewBox="0 0 16 16" class="ml-6 h-6 w-6 fill-gray-800 dark:fill-gray-300">
      <path d="M8 0C3.58 0 0 3.58 0 8C0 11.54 2.29 14.53 5.47 15.59C5.87 15.66 6.02 15.42 6.02 15.21C6.02 15.02 6.01 14.39 6.01 13.72C4 14.09 3.48 13.23 3.32 12.78C3.23 12.55 2.84 11.84 2.5 11.65C2.22 11.5 1.82 11.13 2.49 11.12C3.12 11.11 3.57 11.7 3.72 11.94C4.44 13.15 5.59 12.81 6.05 12.6C6.12 12.08 6.33 11.73 6.56 11.53C4.78 11.33 2.92 10.64 2.92 7.58C2.92 6.71 3.23 5.99 3.74 5.43C3.66 5.23 3.38 4.41 3.82 3.31C3.82 3.31 4.49 3.1 6.02 4.13C6.66 3.95 7.34 3.86 8.02 3.86C8.7 3.86 9.38 3.95 10.02 4.13C11.55 3.09 12.22 3.31 12.22 3.31C12.66 4.41 12.38 5.23 12.3 5.43C12.81 5.99 13.12 6.7 13.12 7.58C13.12 10.65 11.25 11.33 9.47 11.53C9.76 11.78 10.01 12.26 10.01 13.01C10.01 14.08 10 14.94 10 15.21C10 15.42 10.15 15.67 10.55 15.59C13.71 14.53 16 11.53 16 8C16 3.58 12.42 0 8 0Z"></path>
    </svg>
  </section>
</article>

<article class="border shadow-sm relative break-inside rounded-xl overflow-hidden p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute top-0 left-1/2 w-12 h-12 bg-rose-500/30 blur-2xl"></div>
  <section class="relative z-[1] flex items-center justify-between">
    <div class="flex items-center gap-4">
      <a href="#">
        <img class="flex-none w-12 h-12 rounded-full ring-2 ring-pink-500 border-2 border-white dark:border-gray-700" src="https://randomuser.me/api/portraits/men/82.jpg" alt="avatar" loading="lazy" />
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

<article class="border shadow-sm relative break-inside rounded-xl overflow-hidden p-4 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="absolute top-0 left-1/2 w-12 h-12 bg-rose-500/30 blur-2xl"></div>
  <section class="relative z-[1] flex items-center justify-between">
    <div class="flex items-center gap-4">
      <a href="#" class="inline-block relative overflow-hidden w-16 h-16 rounded-full p-[2px]">
        <div class="w-full h-full absolute top-0 left-0 z-0 bg-gradient-to-tr from-rose-500 to-indigo-500"></div>
        <img class="flex-none rounded-full w-full h-full object-cover relative z-[1] border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/30.jpg" alt="avatar" loading="lazy" />
      </a>
      <div class="flex-auto">
        <a href="#" class="font-medium block">Mtheus</a>
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
      <img class="flex-none w-12 h-12 rounded-full ring-2 ring-indigo-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar" loading="lazy" />
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
    <img class="flex-none w-10 h-10 rounded-full ring-1 ring-gray-300 border-2 border-white dark:border-gray-950 dark:ring-gray-400" src="https://randomuser.me/api/portraits/men/85.jpg" alt="avatar" loading="lazy" />
    <div class="flex-auto">
      <h2 class="font-medium">Alexander</h2>
      <span class="text-xs block -mt-0.5 text-gray-600 dark:text-gray-400">Last seen 2 hours ago</span>
    </div>
  </a>
  <button class="flex flex-none items-center justify-center w-10 h-10 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="22" height="22" viewBox="0 0 24 24" stroke-width="1.5" fill="none" xmlns="http://www.w3.org/2000/svg" ><path d="M14.3632 5.65156L15.8431 4.17157C16.6242 3.39052 17.8905 3.39052 18.6716 4.17157L20.0858 5.58579C20.8668 6.36683 20.8668 7.63316 20.0858 8.41421L18.6058 9.8942M14.3632 5.65156L4.74749 15.2672C4.41542 15.5993 4.21079 16.0376 4.16947 16.5054L3.92738 19.2459C3.87261 19.8659 4.39148 20.3848 5.0115 20.33L7.75191 20.0879C8.21972 20.0466 8.65806 19.8419 8.99013 19.5099L18.6058 9.8942M14.3632 5.65156L18.6058 9.8942" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path></svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-col justify-between rounded-xl py-3 mb-3 text-sm divide-y dark:divide-gray-900 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center justify-between px-3 pb-2">
    <div class="flex items-center gap-2">
      <h2 class="font-medium text-base">Details</h2>
      <span class="text-xs text-gray-500">3 min ago</span>
    </div>
    <button class="flex flex-none items-center justify-center w-8 h-8 transition-all rounded-full p-1 hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="32" height="32" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" fill="currentColor"></path>
      </svg>
    </button>
  </header>
  <section class="flex justify-between items-center px-3 pt-2">
    <div class="flex items-center gap-3">
      <img class="flex-none w-10 h-10 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/60.jpg" alt="avatar" loading="lazy" />
      <div class="flex-col items-start flex-auto">
        <a href="#" class="text-base font-medium block">Marc Jacobs</a>
        <span class="block text-xs text-gray-600 dark:text-gray-400">Doctor</span>
      </div>
    </div>
    <button class="flex items-center justify-center cursor-pointer rounded h-6 px-3 text-xs bg-gray-950 text-white dark:bg-gray-100 dark:text-black">View all</button>
  </section>
</article>

<article class="border shadow-sm break-inside flex justify-between flex-col p-3 mb-3 text-sm gap-4 rounded-lg bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center justify-between w-full gap-2">
    <div class="flex-1 flex justify-start items-center gap-3">
      <figure class="relative w-10 h-10 flex-none">
        <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/men/65.jpg" alt="avatar" loading="lazy" />
        <figcaption class="sr-only">Avatar</figcaption>
        <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-cyan-500 border-2 border-white dark:border-gray-950"></span>
      </figure>
      <h2 class="text-sm">
        Improve large organization
        <br />
        onboarding
      </h2>
    </div>
    <button class="flex-none flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </div>
  <div class="flex justify-between items-center gap-2">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z"></path>
      </svg>
      <span>24</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z"></path>
      </svg>
      <span>6</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <span>12</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-gray-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
      </svg>
      <span>6</span>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside flex justify-between divide-y dark:divide-gray-900 flex-col p-3 mb-3 text-sm gap-4 rounded-lg bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-start items-start gap-2">
    <figure class="relative w-10 h-10 flex-none">
      <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/men/71.jpg" alt="avatar" loading="lazy" />
      <figcaption class="sr-only">Avatar</figcaption>
      <span class="absolute right-0 bottom-0 inline-block w-3.5 h-3.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
    </figure>
    <section class="ml-2">
      <h2 class="flex items-center gap-1 font-medium text-blue-700 dark:text-white">
        <span>Frank Ocean</span>
        <svg width="14" height="14" class="ionicon" viewBox="0 0 512 512">
          <path d="M256 48C141.31 48 48 141.31 48 256s93.31 208 208 208 208-93.31 208-208S370.69 48 256 48zm108.25 138.29l-134.4 160a16 16 0 01-12 5.71h-.27a16 16 0 01-11.89-5.3l-57.6-64a16 16 0 1123.78-21.4l45.29 50.32 122.59-145.91a16 16 0 0124.5 20.58z" fill="currentColor"/>
        </svg>
      </h2>
      <p class="text-xs text-gray-600 dark:text-gray-400"> I'm a singer-songwriter and rapper from New Orleans... </p>
    </section>
  </div>
  <div class="flex justify-between items-center gap-2 pt-4">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-cyan-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 0 0 .75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 0 0-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0 1 12 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 0 1-.673-.38m0 0A2.18 2.18 0 0 1 3 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 0 1 3.413-.387m7.5 0V5.25A2.25 2.25 0 0 0 13.5 3h-3a2.25 2.25 0 0 0-2.25 2.25v.894m7.5 0a48.667 48.667 0 0 0-7.5 0M12 12.75h.008v.008H12v-.008Z"></path>
      </svg>
      <span>9</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-green-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 0 1 3 19.875v-6.75ZM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V8.625ZM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 0 1-1.125-1.125V4.125Z"></path>
      </svg>
      <span>32</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-amber-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 0 1 3 3h-15a3 3 0 0 1 3-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 0 1-.982-3.172M9.497 14.25a7.454 7.454 0 0 0 .981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 0 0 7.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 0 0 2.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 0 1 2.916.52 6.003 6.003 0 0 1-5.395 4.972m0 0a6.726 6.726 0 0 1-2.749 1.35m0 0a6.772 6.772 0 0 1-3.044 0"></path>
      </svg>
      <span>66</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md bg-rose-100 dark:bg-gray-900 dark:text-white">
      <svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
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
    <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/67.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium text-sm">
      Improve large organization
      <br />
      onboarding
    </h2>
  </section>
  <div class="flex justify-between items-center gap-2 px-4 pt-3">
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" width="18" height="18">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6A2.25 2.25 0 0 1 6 3.75h2.25A2.25 2.25 0 0 1 10.5 6v2.25a2.25 2.25 0 0 1-2.25 2.25H6a2.25 2.25 0 0 1-2.25-2.25V6ZM3.75 15.75A2.25 2.25 0 0 1 6 13.5h2.25a2.25 2.25 0 0 1 2.25 2.25V18a2.25 2.25 0 0 1-2.25 2.25H6A2.25 2.25 0 0 1 3.75 18v-2.25ZM13.5 6a2.25 2.25 0 0 1 2.25-2.25H18A2.25 2.25 0 0 1 20.25 6v2.25A2.25 2.25 0 0 1 18 10.5h-2.25a2.25 2.25 0 0 1-2.25-2.25V6ZM13.5 15.75a2.25 2.25 0 0 1 2.25-2.25H18a2.25 2.25 0 0 1 2.25 2.25V18A2.25 2.25 0 0 1 18 20.25h-2.25A2.25 2.25 0 0 1 13.5 18v-2.25Z" />
      </svg>
      <span>24</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" width="18" height="18">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5M9 11.25v1.5M12 9v3.75m3-6v6" />
      </svg>
      <span>6</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" width="18" height="18">
        <path stroke-linecap="round" stroke-linejoin="round" d="m21 7.5-9-5.25L3 7.5m18 0-9 5.25m9-5.25v9l-9 5.25M3 7.5l9 5.25M3 7.5v9l9 5.25m0-9v9" />
      </svg>
      <span>12</span>
    </section>
    <section class="flex flex-1 items-center gap-2 py-1 px-2 rounded-md border dark:border-gray-900 dark:text-white">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" width="18" height="18">
        <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 0 0 8.716-6.747M12 21a9.004 9.004 0 0 1-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 0 1 7.843 4.582M12 3a8.997 8.997 0 0 0-7.843 4.582m15.686 0A11.953 11.953 0 0 1 12 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0 1 21 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0 1 12 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 0 1 3 12c0-1.605.42-3.113 1.157-4.418" />
      </svg>
      <span>8</span>
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
    <img class="flex-none mt-1 w-12 h-12 rounded-full ring-2 ring-emerald-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar" loading="lazy" />
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
      <a href="#" class="text-base font-medium block">Team meeting</a>
      <span class="text-xs text-gray-600 dark:text-gray-400">Engineering</span>
    </div>
    <button class="rounded-full flex items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="26" height="26" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="flex items-center justify-between mt-3">
    <div class="col-start-2 row-start-1 row-end-3">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <span class="flex items-center justify-center font-semibold w-6 h-6 rounded-full bg-indigo-200 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950">AT</span>
        </a>
      </dd>
    </div>
    <button class="flex items-center justify-center cursor-pointer rounded-full h-6 px-3 text-xs bg-indigo-600 text-white">View all</button>
  </section>
</article>

<article class="border shadow-sm flex flex-col break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex justify-between items-center">
    <div class="block">
      <dt class="sr-only">Users</dt>
      <dd class="flex justify-start -space-x-1.5">
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/48.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/15.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/37.jpg" alt="avatar" loading="lazy" />
        </a>
        <a href="#" class="inline-block -m-1">
          <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/78.jpg" alt="avatar" loading="lazy" />
        </a>
      </dd>
    </div>
    <div class="flex justify-center items-center rounded-md px-2 py-1 bg-green-100 gap-1 font-medium dark:bg-green-500/20">
      <span class="text-xs font-medium text-green-700 dark:text-green-400">23%</span>
      <svg width="14" height="14" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M1.57835 7.65466H14.1787C14.3063 7.6544 14.4313 7.6309 14.5404 7.5867C14.6495 7.5425 14.7384 7.47927 14.7977 7.40382C14.8569 7.32837 14.8842 7.24356 14.8767 7.15851C14.8692 7.07346 14.827 6.9914 14.7548 6.92115L8.45465 0.84365C8.19354 0.591667 7.56492 0.591667 7.30311 0.84365L1.00293 6.92115C0.93001 6.99125 0.887245 7.07336 0.879287 7.15855C0.871328 7.24374 0.898481 7.32876 0.957793 7.40437C1.01711 7.47997 1.10631 7.54328 1.21572 7.58741C1.32512 7.63154 1.45054 7.6548 1.57835 7.65466Z" fill="currentColor" class="fill-green-500 dark:fill-green-400"></path>
      </svg>
    </div>
    <div class="flex items-center gap-2">
      <button class="inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
        <svg width="22" height="22" viewBox="0 0 24 24" stroke-width="2" fill="none" xmlns="http://www.w3.org/2000/svg" color="currentColor"><path d="M14.3632 5.65156L15.8431 4.17157C16.6242 3.39052 17.8905 3.39052 18.6716 4.17157L20.0858 5.58579C20.8668 6.36683 20.8668 7.63316 20.0858 8.41421L18.6058 9.8942M14.3632 5.65156L4.74749 15.2672C4.41542 15.5993 4.21079 16.0376 4.16947 16.5054L3.92738 19.2459C3.87261 19.8659 4.39148 20.3848 5.0115 20.33L7.75191 20.0879C8.21972 20.0466 8.65806 19.8419 8.99013 19.5099L18.6058 9.8942M14.3632 5.65156L18.6058 9.8942" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg>
      </button>
      <button class="inline-flex items-center justify-center w-9 h-9 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
        <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
        </svg>
      </button>
    </div>
  </div>
</article>



<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img class="flex-none w-14 object-cover" src="https://randomuser.me/api/portraits/women/45.jpg" alt="avatar" loading="lazy" />
  <div class="flex-auto">
    <a href="#" class="text-base font-semibold block">Adrianne</a>
    <span class="text-xs block text-gray-600 dark:text-gray-400">Frontend Development</span>
  </div>
</article>

<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <img class="flex-none w-14 object-cover" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
    <div class="flex-auto">
      <a href="#" class="text-sm font-medium block">Matheus Duarte</a>
      <span class="text-xs text-gray-600 dark:text-gray-400">Art Director</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center space-x-4 rounded-xl overflow-hidden pr-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <div class="flex items-center justify-center w-14 h-14 font-semibold text-lg bg-purple-100 dark:bg-purple-600/50">
      CM
    </div>
    <div class="flex-auto">
      <a href="#" class="font-medium block">Carolina Melo</a>
      <span class="text-xs text-gray-600 dark:text-gray-400">UX/UI Designer</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
    <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="break-inside flex items-center space-x-4 rounded overflow-hidden pr-4 mb-3 text-sm bg-purple-100 dark:bg-purple-500/20 dark:text-white" data-filter="social">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <div class="flex items-center justify-center w-14 h-14 font-semibold text-lg bg-purple-200 dark:bg-purple-600/50">
      AB
    </div>
    <div class="flex-auto">
      <a href="#" class="font-medium block">Anthony Brown</a>
      <span class="text-xs text-gray-600 dark:text-gray-400">Engineer</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-black/10 dark:hover:bg-white/10">
    <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl overflow-hidden py-4 mb-3 gap-4 text-sm divide-y dark:divide-gray-800 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex justify-between items-center px-3">
    <button type="button" class="h-8 px-3 font-medium text-base transition-colors duration-200 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">September</button>
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
  <section class="flex items-center gap-1 pt-3 px-4">
    <button class="flex items-center justify-center h-7 w-7 hover:bg-gray-100 rounded-md dark:hover:bg-gray-900">
      <svg width="28" height="28" viewBox="0 0 24 24">
        <path fill="currentColor" d="M15.41,16.58L10.83,12L15.41,7.41L14,6L8,12L14,18L15.41,16.58Z"></path>
      </svg>
    </button>
    <button class="flex-auto text-center rounded-md px-1 h-6 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="block">2021</span>
    </button>
    <button class="flex-auto text-center rounded-md px-1 h-6 transition-colors duration-200 hover:bg-rose-600 bg-rose-500 text-white dark:text-white dark:hover:bg-rose-600">
      <span class="block">2022</span>
    </button>
    <button class="flex-auto text-center rounded-md px-1 h-6 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="block">2023</span>
    </button>
    <button class="flex-auto text-center rounded-md px-1 h-6 transition-colors duration-200 hover:bg-gray-200 bg-transparent text-black dark:text-white dark:hover:bg-gray-900">
      <span class="block">2024</span>
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
    <img class="flex-none w-16 object-cover" src="https://randomuser.me/api/portraits/men/46.jpg" alt="avatar" loading="lazy" />
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
      <svg  width="22" height="22" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M9.143 17.082a24.248 24.248 0 0 0 3.844.148m-3.844-.148a23.856 23.856 0 0 1-5.455-1.31 8.964 8.964 0 0 0 2.3-5.542m3.155 6.852a3 3 0 0 0 5.667 1.97m1.965-2.277L21 21m-4.225-4.225a23.81 23.81 0 0 0 3.536-1.003A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6.53 6.53m10.245 10.245L6.53 6.53M3 3l3.53 3.53"></path>
      </svg>
    </button>
  </section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center space-x-3">
    <div class="flex flex-none justify-center items-center rounded-lg font-medium border border-gray-300 px-2 h-9 gap-1 text-sm dark:border-gray-900">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"></path>
      </svg>
      <span>Feb, 24</span>
    </div>
    <p class="text-xs">This is a notification from the system</p>
  </header>
  <button class="w-9 h-9 flex flex-none items-center justify-center rounded-full transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M10 18.75C7.67936 18.75 5.45376 17.8281 3.81282 16.1872C2.17187 14.5462 1.25 12.3206 1.25 10C1.25 7.67936 2.17187 5.45376 3.81282 3.81282C5.45376 2.17187 7.67936 1.25 10 1.25C12.3206 1.25 14.5462 2.17187 16.1872 3.81282C17.8281 5.45376 18.75 7.67936 18.75 10C18.75 12.3206 17.8281 14.5462 16.1872 16.1872C14.5462 17.8281 12.3206 18.75 10 18.75ZM10 20C12.6522 20 15.1957 18.9464 17.0711 17.0711C18.9464 15.1957 20 12.6522 20 10C20 7.34784 18.9464 4.8043 17.0711 2.92893C15.1957 1.05357 12.6522 0 10 0C7.34784 0 4.8043 1.05357 2.92893 2.92893C1.05357 4.8043 0 7.34784 0 10C0 12.6522 1.05357 15.1957 2.92893 17.0711C4.8043 18.9464 7.34784 20 10 20Z" fill="currentColor"></path>
      <path d="M13.7125 6.2125C13.7036 6.22113 13.6952 6.23031 13.6875 6.24L9.34625 11.7712L6.73 9.15375C6.55228 8.98815 6.31722 8.898 6.07435 8.90228C5.83147 8.90657 5.59974 9.00496 5.42797 9.17672C5.25621 9.34849 5.15782 9.58022 5.15353 9.8231C5.14925 10.066 5.2394 10.301 5.405 10.4788L8.7125 13.7875C8.8016 13.8764 8.90771 13.9465 9.02448 13.9936C9.14125 14.0406 9.26631 14.0637 9.39218 14.0613C9.51806 14.059 9.64217 14.0313 9.75712 13.98C9.87207 13.9286 9.9755 13.8547 10.0612 13.7625L15.0513 7.525C15.2212 7.34666 15.3141 7.10862 15.3099 6.86234C15.3057 6.61605 15.2047 6.38131 15.0288 6.20887C14.8529 6.03643 14.6162 5.94014 14.3699 5.94081C14.1236 5.94149 13.8874 6.03909 13.7125 6.2125Z" fill="currentColor"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <header class="flex items-center space-x-3">
    <div class="flex flex-none justify-center items-center rounded-lg font-medium border border-gray-300 px-2 h-9 gap-1 text-sm dark:border-gray-900">
      <svg width="18" height="18" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"></path>
      </svg>
      <span>Jan, 06</span>
    </div>
    <p class="text-xs line-through">This is a notification from the system</p>
  </header>
  <button class="w-9 h-9 flex flex-none items-center justify-center rounded-full transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
    <svg width="20" height="20" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="m14.74 9-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 0 1-2.244 2.077H8.084a2.25 2.25 0 0 1-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 0 0-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 0 1 3.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 0 0-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 0 0-7.5 0"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex items-center justify-center space-x-2">
    <svg width="20" height="20" viewBox="0 0 24 24">
      <path fill="currentColor" d="M12,20A8,8 0 0,0 20,12A8,8 0 0,0 12,4A8,8 0 0,0 4,12A8,8 0 0,0 12,20M12,2A10,10 0 0,1 22,12A10,10 0 0,1 12,22C6.47,22 2,17.5 2,12A10,10 0 0,1 12,2M12.5,7V12.25L17,14.92L16.25,16.15L11,13V7H12.5Z"></path>
    </svg>
    <div class="font-medium text-sm rounded-md flex items-center justify-center h-6 px-2 bg-blue-100 text-blue-600 dark:bg-blue-500 dark:text-white">04:32</div>
  </div>
  <div class="font-medium text-sm flex-1 justify-center items-center flex gap-3">
    <div class="border border-gray-300 h-4 rounded-sm dark:border-gray-500 dark:bg-gray-500"></div>
    <span>Installation...</span>
    <div class="border border-gray-300 h-4 rounded-sm dark:border-gray-500 dark:bg-gray-500"></div>
  </div>
  <button class="w-8 h-8 flex-none flex justify-center items-center rounded-full transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
    <svg width="22" height="22" viewBox="0 0 24 24">
      <path fill="currentColor" d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M9,9H15V15H9"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 gap-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <a href="https://github.com/frankuxui" class="flex items-center gap-2">
    <img class="w-8 h-8 rounded-full" src="https://avatars.githubusercontent.com/u/35234895?v=4" alt="frankuxui">
    <span class="font-medium">@frankuxui</span>
  </a>
  <div class="flex items-center space-x-2 justify-between">
    <span>12 Followers</span>
    <svg width="22" height="22" viewBox="0 0 24 24">
      <path fill="currentColor" d="M7.8,2H16.2C19.4,2 22,4.6 22,7.8V16.2A5.8,5.8 0 0,1 16.2,22H7.8C4.6,22 2,19.4 2,16.2V7.8A5.8,5.8 0 0,1 7.8,2M7.6,4A3.6,3.6 0 0,0 4,7.6V16.4C4,18.39 5.61,20 7.6,20H16.4A3.6,3.6 0 0,0 20,16.4V7.6C20,5.61 18.39,4 16.4,4H7.6M17.25,5.5A1.25,1.25 0 0,1 18.5,6.75A1.25,1.25 0 0,1 17.25,8A1.25,1.25 0 0,1 16,6.75A1.25,1.25 0 0,1 17.25,5.5M12,7A5,5 0 0,1 17,12A5,5 0 0,1 12,17A5,5 0 0,1 7,12A5,5 0 0,1 12,7M12,9A3,3 0 0,0 9,12A3,3 0 0,0 12,15A3,3 0 0,0 15,12A3,3 0 0,0 12,9Z"></path>
    </svg>
  </div>
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
    <div class="relative flex-none w-10 h-10 rounded-full flex items-center justify-center text-base font-semibold bg-blue-200 text-blue-500 dark:bg-blue-600/50 dark:text-white">
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

<section class="break-inside grid grid-cols-2 mb-3 gap-3">
  <div class="flex flex-col gap-3">
    <article class="border shadow-sm break-inside rounded-xl p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
      <header class="w-full flex items-center justify-between">
        <h2 class="text-sm font-bold">Members</h2>
        <span class="flex items-center justify-center w-5 h-5 text-[11px] rounded-full font-medium bg-amber-200 text-black">5</span>
      </header>
      <section class="flex items-center justify-between mt-2">
        <div class="block">
          <dt class="sr-only">Users</dt>
          <dd class="flex justify-start -space-x-1.5">
            <a href="#" class="inline-block -ml-1">
              <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/12.jpg" alt="avatar" loading="lazy" />
            </a>
            <a href="#" class="inline-block -ml-1">
              <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/13.jpg" alt="avatar" loading="lazy" />
            </a>
            <a href="#" class="inline-block -ml-1">
              <span class="flex items-center justify-center text-[11px] font-medium w-6 h-6 rounded-full bg-rose-200 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950">+3</span>
            </a>
          </dd>
        </div>
        <button class="rounded-full flex items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
          <svg width="16" height="16" fill="none" stroke-width="3" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"></path>
          </svg>
        </button>
      </section>
    </article>
    <article class="border shadow-sm break-inside rounded-xl p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
      <header class="w-full flex items-center justify-between">
        <h2 class="text-sm font-bold">Members</h2>
        <span class="flex items-center justify-center w-5 h-5 text-[11px] rounded-full font-medium bg-green-200 text-black">2</span>
      </header>
      <section class="flex items-center justify-between mt-2">
        <div class="block">
          <dt class="sr-only">Users</dt>
          <dd class="flex justify-start -space-x-1.5">
            <a href="#" class="inline-block -ml-1">
              <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/14.jpg" alt="avatar" loading="lazy" />
            </a>
            <a href="#" class="inline-block -ml-1">
              <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/15.jpg" alt="avatar" loading="lazy" />
            </a>
          </dd>
        </div>
        <button class="rounded-full flex items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
          <svg width="16" height="16" fill="none" stroke-width="3" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"></path>
          </svg>
        </button>
      </section>
    </article>
  </div>
  <article class="border shadow-sm break-inside flex flex-col justify-between rounded-xl p-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center justify-between">
      <span class="h-6 px-2 text-xs font-medium rounded-md flex items-center justify-center bg-green-100 text-green-600 dark:bg-green-500/30 dark:text-green-300">NEW</span>
      <button class="inline-flex items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-gray-100 dark:hover:bg-gray-900">
        <svg width="28" height="28" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
        </svg>
      </button>
    </header>
    <section class="mt-3">
      <h2 class="text-lg font-bold leading-6">Project members</h2>
      <p class="text-[11px] mt-1 text-gray-500">03:00 PM - 05:00 PM</p>
    </section>
    <div class="flex items-center justify-between mt-auto">
      <div class="block">
        <dt class="sr-only">Users</dt>
        <dd class="flex justify-start -space-x-1.5">
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/48.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/15.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-white dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/37.jpg" alt="avatar" loading="lazy" />
          </a>
        </dd>
      </div>
      <button class="rounded-full flex items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
        <svg width="16" height="16" fill="none" stroke-width="3" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"></path>
        </svg>
      </button>
    </div>
  </article>
</section>

<section class="grid grid-cols-4 gap-3 mb-3">
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/76.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Jhon</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/women/76.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Tina</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/78.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Jhonas</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/79.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Mathiaz</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/16.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Fabio</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/46.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Miller</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/women/86.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Jessy</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col justify-start items-center rounded-xl p-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <img class="flex-none rounded-full w-8 h-8" src="https://randomuser.me/api/portraits/men/36.jpg" alt="avatar" loading="lazy" />
    <h2 class="text-xs font-medium mt-1">Jack</h2>
  </article>
</section>

<section class="break-inside grid grid-cols-2 mb-3 gap-3" >
  <article class="border relative overflow-hidden shadow-sm break-inside flex flex-col justify-between rounded-xl p-3 text-sm bg-rose-600 border-rose-600 text-white" data-filter="social">
    <div class="absolute right-0 top-0 w-14 h-14 bg-yellow-500/60 blur-2xl"></div>
    <div class="absolute left-0 bottom-0 w-14 h-14 bg-yellow-500/80 blur-2xl"></div>
    <header class="relative flex items-center justify-between">
      <span class="h-5 px-2 text-[11px] font-semibold rounded flex items-center justify-center bg-white text-rose-700">NOW</span>
      <button class="rounded-full flex items-center justify-center w-8 h-8 transition-all hover:bg-white/30">
        <svg width="16" height="16" fill="none" stroke-width="3" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"></path>
        </svg>
      </button>
    </header>
    <section class="relative mt-3">
      <h2 class="text-base font-bold">Authors meeting at the library</h2>
      <p class="text-xs mt-1 text-white/80">Three authors will be present at the...</p>
    </section>
    <div class="relative flex items-center justify-between mt-3">
      <div class="block">
        <dt class="sr-only">Users</dt>
        <dd class="flex justify-start -space-x-1.5">
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-rose-600" src="https://randomuser.me/api/portraits/women/48.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-rose-600" src="https://randomuser.me/api/portraits/men/15.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-6 h-6 rounded-full ring-2 ring-rose-600" src="https://randomuser.me/api/portraits/women/37.jpg" alt="avatar" loading="lazy" />
          </a>
        </dd>
      </div>
      <button class="inline-flex items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-white/30">
        <svg width="28" height="28" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
        </svg>
      </button>
    </div>
  </article>
  <div class="flex flex-col gap-3">
    <article class="border shadow-sm break-inside flex flex-col items-start justify-between gap-2 rounded-xl p-3 flex-1 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
      <header class="flex items-start gap-2">
        <img class="w-10 h-10 rounded-full" src="https://randomuser.me/api/portraits/men/41.jpg" alt="avatar" loading="lazy" />
        <h2 class="text-sm font-bold">
          Jhonatan
          <br />
          Smith
        </h2>
      </header>
      <div class="flex items-center justify-between w-full">
        <span class="flex items-center justify-center px-2 h-5 text-[11px] rounded font-medium bg-amber-100 text-black">Missing</span>
        <button class="inline-flex items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-black/10 dark:hover:bg-white/10">
          <svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
          </svg>
        </button>
      </div>
    </article>
    <article class="border shadow-sm break-inside flex flex-col items-start justify-between gap-2 rounded-xl p-3 flex-1 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
      <header class="flex items-start gap-2">
        <img class="w-10 h-10 rounded-full" src="https://randomuser.me/api/portraits/women/40.jpg" alt="avatar" loading="lazy" />
        <h2 class="text-sm font-bold">
          Marianna
          <br />
          Green
        </h2>
      </header>
      <div class="flex items-center justify-between w-full">
        <span class="flex items-center justify-center px-2 h-5 text-[11px] rounded font-medium bg-green-100 text-black">Online</span>
        <button class="inline-flex items-center justify-center w-7 h-7 transition-all rounded-full hover:bg-black/10 dark:hover:bg-white/10">
          <svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
          </svg>
        </button>
      </div>
    </article>
  </div>
</section>

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

<section class="grid grid-cols-3 gap-3" >
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Favorite</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Bookmark</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="m2.25 12 8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"></path>
    </svg>
    <h2 class="font-medium text-sm">Home</h2>
  </article>
</section>

<section class="grid grid-cols-3 gap-3">
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900"  data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Phone</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"></path>
    </svg>
    <h2 class="font-medium text-sm">Mail</h2>
  </article>
  <article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg width='26' height='26' fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M12 20.25c4.97 0 9-3.694 9-8.25s-4.03-8.25-9-8.25S3 7.444 3 12c0 2.104.859 4.023 2.273 5.48.432.447.74 1.04.586 1.641a4.483 4.483 0 0 1-.923 1.785A5.969 5.969 0 0 0 6 21c1.282 0 2.47-.402 3.445-1.087.81.22 1.668.337 2.555.337Z"></path>
    </svg>
    <h2 class="font-medium text-sm">Chat</h2>
  </article>
</section>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg class="flex-none" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 9v11a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V9"/><path d="M9 22V12h6v10M2 10.6L12 2l10 8.6"/></svg>
    <h2 class="font-medium text-sm">Home</h2>
  </article>
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg class="flex-none" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"></circle><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z"></path></svg>
    <h2 class="font-medium text-sm">Settings</h2>
  </article>
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg class="flex-none" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
    <h2 class="font-medium text-sm">Phone</h2>
  </article>
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg class="flex-none" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s-8-4.5-8-11.8A8 8 0 0 1 12 2a8 8 0 0 1 8 8.2c0 7.3-8 11.8-8 11.8z"/><circle cx="12" cy="10" r="3"/></svg>
    <h2 class="font-medium text-sm">Location</h2>
  </article>
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><path d="M20.4 14.5L16 10 4 20"/></svg>
    <h2 class="font-medium text-sm">Pictures</h2>
  </article>
  <article class="border shadow-sm break-inside relative overflow-hidden rounded-xl flex items-center p-3 gap-2 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="7" height="7"></rect><rect x="14" y="3" width="7" height="7"></rect><rect x="14" y="14" width="7" height="7"></rect><rect x="3" y="14" width="7" height="7"></rect></svg>
    <h2 class="font-medium text-sm">Components</h2>
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
    <img class="flex-none w-11 h-11 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/45.jpg" alt="avatar" loading="lazy" />
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
        <p class="text-xs text-gray-600 dark:text-gray-400"> Hi, I've been calling you and your phone doesn't ring... </p>
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

<section class="grid grid-cols-2 gap-4 mb-3">
  <article class="border shadow-sm break-inside flex items-center justify-between rounded-full gap-2 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-2">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect><path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg>
      <h2 class="font-medium">Private</h2>
    </header>
    <input type="checkbox" checked="" class="h-[16px] px-[3px] w-[30px] relative flex-none cursor-pointer appearance-none rounded-full bg-gray-300 dark:bg-gray-700 before:transition-transform before:duration-200 before:pointer-events-none before:absolute before:top-1/2 before:-translate-y-1/2 before:h-3 before:w-3 before:rounded-full before:bg-transparent before:content-[''] before:transform before:translate-x-0 before:bg-white focus:bg-gray-400 dark:focus:bg-gray-600 focus:checked:bg-indigo-600 checked:bg-indigo-600 checked:before:translate-x-full checked:before:bg-white">
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <img class="flex-none w-5 h-5 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/60.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Albert G.</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <input type="checkbox" class="checkbox checkbox-sm" />
    <h2 class="ml-1 font-medium">Mariana</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="w-1 h-full rounded-full bg-rose-600"></div>
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <img class="flex-none w-5 h-5 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/65.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Angel.</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="w-1 h-full rounded-full bg-cyan-500"></div>
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <img class="flex-none w-5 h-5 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/65.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Jhonny</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="w-1 h-full rounded-full bg-emerald-500"></div>
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <img class="flex-none w-5 h-5 rounded-full object-cover" src="https://randomuser.me/api/portraits/men/65.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Jenrry</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="w-1 h-full rounded-full bg-indigo-500"></div>
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <img class="flex-none w-5 h-5 rounded-full object-cover" src="https://randomuser.me/api/portraits/women/15.jpg" alt="avatar" loading="lazy" />
    <h2 class="font-medium">Marina</h2>
  </article>
  <article class="border shadow-sm break-inside flex items-center justify-start rounded-xl gap-1 p-2.5 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="w-1 h-full rounded-full bg-amber-400"></div>
    <button>
      <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24"><path d="M7,19V17H9V19H7M11,19V17H13V19H11M15,19V17H17V19H15M7,15V13H9V15H7M11,15V13H13V15H11M15,15V13H17V15H15M7,11V9H9V11H7M11,11V9H13V11H11M15,11V9H17V11H15M7,7V5H9V7H7M11,7V5H13V7H11M15,7V5H17V7H15Z" fill="currentColor"/></svg>
    </button>
    <input type="checkbox" class="checkbox checkbox-sm" />
    <h2 class="font-medium">Jonaz</h2>
  </article>
</section>

<article class="border shadow-sm break-inside overflow-hidden flex items-center justify-start rounded-2xl gap-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <img src="https://images.pexels.com/photos/3183150/pexels-photo-3183150.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="avatar" class="w-full h-full max-w-[5rem] min-h-[5rem] object-cover rounded-2xl" />
  <div class="flex justify-between items-center flex-1 p-2.5">
    <div class="flex flex-col flex-none">
      <div class="flex items-center gap-2 text-xs">
        <span class="font-medium">Next week</span>
        <span class="font-medium text-rose-600">09:00 AM</span>
      </div>
      <div class="flex flex-col">
        <h2 class="font-medium text-base">Meeting</h2>
        <p class="text-xs">Loke at the new features</p>
      </div>
    </div>
    <button class="flex flex-none items-center justify-center w-6 h-6 transition-all rounded-full bg-slate-200 dark:bg-gray-800">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 18l6-6-6-6"/></svg>
    </button>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-md p-3 gap-2 mb-3 text-sm ring-2 ring-indigo-600 border-indigo-600 bg-indigo-50 dark:bg-indigo-600/20 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex flex-col gap-2">
    <section class="flex items-center justify-between">
      <div class="flex items-center justify-start gap-2">
        <h2 class="text-base font-medium">Pablo Garcia</h2>
        <span class="px-2 py-1 text-xs font-medium rounded-md bg-black/10 dark:bg-white/10">Asistente</span>
      </div>
      <span class="text-xs text-gray-700 dark:text-gray-400">06:30 PM</span>
    </section>
    <section class="flex items-center justify-between">
      <div class="flex items-start gap-2">
        <img src="https://randomuser.me/api/portraits/men/67.jpg" alt="Pablo Garcia" class="w-7 h-7 rounded-full" />
        <p class="text-xs dark:text-gray-400">Lorem ipsum dolor sit amet, consectr adipiscing elit. Nulla nec.</p>
      </div>
      <button class="flex items-center justify-center flex-none rounded-full transition-colors duration-200 w-8 h-8 hover:bg-black/10 dark:hover:bg-white/10">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
          <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h3.75M9 15h3.75M9 18h3.75m3 .75H18a2.25 2.25 0 0 0 2.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 0 0-1.123-.08m-5.801 0c-.065.21-.1.433-.1.664 0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75 2.25 2.25 0 0 0-.1-.664m-5.8 0A2.251 2.251 0 0 1 13.5 2.25H15c1.012 0 1.867.668 2.15 1.586m-5.8 0c-.376.023-.75.05-1.124.08C9.095 4.01 8.25 4.973 8.25 6.108V8.25m0 0H4.875c-.621 0-1.125.504-1.125 1.125v11.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V9.375c0-.621-.504-1.125-1.125-1.125H8.25ZM6.75 12h.008v.008H6.75V12Zm0 3h.008v.008H6.75V15Zm0 3h.008v.008H6.75V18Z" />
        </svg>
      </button>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-md p-3 gap-2 mb-3 text-sm ring-2 ring-green-600 border-green-600 bg-white dark:bg-gray-900 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex flex-col gap-2">
    <section class="flex items-center justify-between">
      <div class="flex items-center justify-start gap-2">
        <h2 class="text-base font-medium">Marianna G.</h2>
        <span class="px-2 py-1 text-xs font-medium rounded-md bg-green-200 text-green-700 dark:bg-green-600/20 dark:text-green-400">Proccessing</span>
      </div>
      <span class="text-xs text-gray-700 dark:text-gray-400">02:45 AM</span>
    </section>
    <section class="flex items-center justify-between">
      <div class="flex items-start gap-2">
        <img src="https://randomuser.me/api/portraits/women/56.jpg" alt="Pablo Garcia" class="w-7 h-7 rounded-full" />
        <p class="text-xs dark:text-gray-400">Lorem ipsum dolor sit amet, consectr adipiscing elit. Nulla nec.</p>
      </div>
      <button class="flex items-center justify-center flex-none rounded-full transition-colors duration-200 w-8 h-8 hover:bg-black/10 dark:hover:bg-white/10">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
          <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 8.25h9m-9 3H12m-9.75 1.51c0 1.6 1.123 2.994 2.707 3.227 1.129.166 2.27.293 3.423.379.35.026.67.21.865.501L12 21l2.755-4.133a1.14 1.14 0 0 1 .865-.501 48.172 48.172 0 0 0 3.423-.379c1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0 0 12 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018Z" />
        </svg>
      </button>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside relative overflow-hidden flex flex-col items-start rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="flex flex-col pb-4 group">
    <header class="flex items-center justify-start gap-3 pl-4 pt-4 pb-2 pr-12">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-6 h-6" src="https://randomuser.me/api/portraits/women/74.jpg" alt="Avatar" />
      </a>
      <div class="flex items-center gap-2 w-full flex-1">
        <a class="font-medium" href="#">Natalia</a>
        <span class="text-xs text-gray-500 dark:text-gray-300">3 minutes ago</span>
      </div>
      <button class="hidden absolute right-4 top-3 group-hover:flex items-center justify-center rounded-full w-8 h-8 transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" />
        </svg>
      </button>
    </header>
    <section class="relative px-4">
      <p class="text-xs"> Dolor sit ameteiusmod consectetur adipi scing elit. Nulla nec purus feugiat, vestibulum.</p>
      <footer class="flex items-center justify-between w-full mt-2">
        <div class="flex items-center justify-start gap-2">
          <a class="inline-flex items-center py-2 mr-3" href="#">
            <span class="mr-2">
              <svg class="fill-rose-600" width="18" height="18" viewBox="0 0 24 24">
                <path d="M12,21.35L10.55,20.03C5.4,15.36 2,12.27 2,8.5C2,5.41 4.42,3 7.5,3C9.24,3 10.91,3.81 12,5.08C13.09,3.81 14.76,3 16.5,3C19.58,3 22,5.41 22,8.5C22,12.27 18.6,15.36 13.45,20.03L12,21.35Z"></path>
              </svg>
            </span>
            <span class="font-bold">2</span>
          </a>
          <button class="py-1 px-2 text-sm font-medium hover:bg-gray-50 dark:hover:bg-gray-900 rounded-md" >Repply</button>
        </div>
        <a class="inline-flex items-center">
          <span class="-m-1 rounded-full border-2 border-white dark:border-slate-800">
            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 16 16" fill="none">
              <path fill="url(#a12)" d="M8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0Z"></path>
              <path fill="#fff" d="M12.162 7.338c.176.123.338.245.338.674 0 .43-.229.604-.474.725.1.163.132.36.089.546-.077.344-.392.611-.672.69.121.194.159.385.015.62-.185.295-.346.407-1.058.407H7.5c-.988 0-1.5-.546-1.5-1V7.665c0-1.23 1.467-2.275 1.467-3.13L7.361 3.47c-.005-.065.008-.224.058-.27.08-.079.301-.2.635-.2.218 0 .363.041.534.123.581.277.732.978.732 1.542 0 .271-.414 1.083-.47 1.364 0 0 .867-.192 1.879-.199 1.061-.006 1.749.19 1.749.842 0 .261-.219.523-.316.666ZM3.6 7h.8a.6.6 0 0 1 .6.6v3.8a.6.6 0 0 1-.6.6h-.8a.6.6 0 0 1-.6-.6V7.6a.6.6 0 0 1 .6-.6Z"></path>
              <defs>
                <linearGradient id="a12" x1="8" x2="8" y2="16" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#18AFFF"></stop>
                  <stop offset="1" stop-color="#0062DF"></stop>
                </linearGradient>
              </defs>
            </svg>
          </span>
          <span class="-m-1 rounded-full border-2 border-white dark:border-slate-800">
            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 16 16" fill="none">
              <path fill="url(#b1231)" d="M8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0Z"></path>
              <path fill="#fff" d="M10.473 4C8.275 4 8 5.824 8 5.824S7.726 4 5.528 4c-2.114 0-2.73 2.222-2.472 3.41C3.736 10.55 8 12.75 8 12.75s4.265-2.2 4.945-5.34c.257-1.188-.36-3.41-2.472-3.41Z"></path>
              <defs>
                <linearGradient id="b1231" x1="8" x2="8" y2="16" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#FF6680"></stop>
                  <stop offset="1" stop-color="#E61739"></stop>
                </linearGradient>
              </defs>
            </svg>
          </span>
          <span class="-m-1 rounded-full border-2 border-white dark:border-slate-800">
            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 16 16" fill="none">
              <path fill="url(#aa)" d="M16 8A8 8 0 1 1-.001 8 8 8 0 0 1 16 8"></path>
              <path fill="url(#bb)" d="M3 8.008C3 10.023 4.006 14 8 14c3.993 0 5-3.977 5-5.992C13 7.849 11.39 7 8 7c-3.39 0-5 .849-5 1.008Z"></path>
              <path fill="url(#cc)" d="M4.541 12.5c.804.995 1.907 1.5 3.469 1.5 1.563 0 2.655-.505 3.459-1.5-.551-.588-1.599-1.5-3.459-1.5s-2.917.912-3.469 1.5Z"></path>
              <path fill="#2A3755" d="M6.213 4.144c.263.188.502.455.41.788-.071.254-.194.369-.422.37-.78.012-1.708.256-2.506.613-.065.029-.197.088-.332.085-.124-.003-.251-.058-.327-.237-.067-.157-.073-.388.276-.598.545-.33 1.257-.48 1.909-.604-.41-.303-.85-.56-1.315-.768-.427-.194-.38-.457-.323-.6.127-.317.609-.196 1.078.026a9 9 0 0 1 1.552.925Zm3.577 0a8.955 8.955 0 0 1 1.55-.925c.47-.222.95-.343 1.078-.026.057.143.104.406-.323.6a7.028 7.028 0 0 0-1.313.768c.65.123 1.363.274 1.907.604.349.21.342.44.276.598-.077.18-.203.234-.327.237-.135.003-.267-.056-.332-.085-.797-.357-1.725-.6-2.504-.612-.228-.002-.351-.117-.422-.37-.091-.333.147-.6.41-.788v-.001Z"></path>
              <defs>
                <linearGradient id="aa" x1="8" x2="8" y1="1.64" y2="16" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#FEEA70"></stop>
                  <stop offset="1" stop-color="#F69B30"></stop>
                </linearGradient>
                <linearGradient id="bb" x1="8" x2="8" y1="7" y2="14" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#472315"></stop>
                  <stop offset="1" stop-color="#8B3A0E"></stop>
                </linearGradient>
                <linearGradient id="cc" x1="8.005" x2="8.005" y1="11" y2="13.457" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#FC607C"></stop>
                  <stop offset="1" stop-color="#D91F3A"></stop>
                </linearGradient>
              </defs>
            </svg>
          </span>
          <span class="font-bold ml-3">33</span>
        </a>
      </footer>
    </section>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl p-3 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <div class="w-32 h-32 absolute top-0 left-0 z-0 bg-gradient-to-br blur-2xl from-white to-gray-100 dark:from-transparent dark:to-gray-900"></div>
  <header class="flex flex-col w-full gap-2 relative">
    <div class="flex items-center justify-between w-full gap-2">
      <h2 class="font-medium">Wireframes</h2>
      <span class="text-xs border px-2 py-1 bg-white dark:bg-gray-900 dark:text-gray-500 text-gray-500 rounded dark:border-gray-800">January 12</span>
      <button class="ml-auto flex flex-none items-center justify-center w-8 h-8 rounded-full transition-colors hover:bg-gray-200 dark:hover:bg-gray-900">
        <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
        </svg>
      </button>
    </div>
    <div class="flex items-center justify-between w-full">
      <div class="flex items-center gap-2">
        <span class="rounded flex items-center justify-center w-6 h-6 border dark:border-gray-800 dark:text-gray-400">
          <svg width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 3v1.5M3 21v-6m0 0 2.77-.693a9 9 0 0 1 6.208.682l.108.054a9 9 0 0 0 6.086.71l3.114-.732a48.524 48.524 0 0 1-.005-10.499l-3.11.732a9 9 0 0 1-6.085-.711l-.108-.054a9 9 0 0 0-6.208-.682L3 4.5M3 15V4.5"></path>
          </svg>
        </span>
        <span class="rounded flex items-center justify-center w-6 h-6 border dark:border-gray-800 dark:text-gray-400">
          <svg width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.593 3.322c1.1.128 1.907 1.077 1.907 2.185V21L12 17.25 4.5 21V5.507c0-1.108.806-2.057 1.907-2.185a48.507 48.507 0 0 1 11.186 0Z"></path>
          </svg>
        </span>
        <span class="rounded flex items-center justify-center w-6 h-6 border dark:border-gray-800 dark:text-gray-400">
          <svg width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 20.25c4.97 0 9-3.694 9-8.25s-4.03-8.25-9-8.25S3 7.444 3 12c0 2.104.859 4.023 2.273 5.48.432.447.74 1.04.586 1.641a4.483 4.483 0 0 1-.923 1.785A5.969 5.969 0 0 0 6 21c1.282 0 2.47-.402 3.445-1.087.81.22 1.668.337 2.555.337Z"></path>
          </svg>
        </span>
      </div>
      <div class="col-start-2 row-start-1 row-end-3 flex-none">
        <dt class="sr-only">Users</dt>
        <dd class="flex justify-start -space-x-1.5">
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/46.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/men/45.jpg" alt="avatar" loading="lazy" />
          </a>
          <a href="#" class="inline-block -m-1">
            <img class="w-5 h-5 rounded-full bg-gray-100 ring-2 ring-white dark:bg-gray-600 dark:ring-gray-950" src="https://randomuser.me/api/portraits/women/47.jpg" alt="avatar" loading="lazy" />
          </a>
        </dd>
      </div>
    </div>
  </header>
</article>

<section class="grid grid-cols-2 gap-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col justify-between rounded-xl text-sm mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-1 px-3 pt-3 pb-1">
      <svg width="24" height="24" class="-mt-1 fill-amber-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path clip-rule="evenodd" fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z"></path>
      </svg>
      <h2 class="font-bold text-xl">3.5</h2>
      <span class="text-xs mt-1.5 text-gray-500">/5.0</span>
    </header>
    <p class="text-xs mt-2 px-3 border-y py-2 bg-gray-50 dark:bg-gray-900 dark:border-gray-800 dark:text-gray-400">Based on 3,000+ reviews</p>
    <footer class="flex items-center justify-start w-full gap-2 p-3">
      <figure class="relative flex-none w-8 h-8">
        <img class="flex-none w-full rounded-full object-cover" src="https://randomuser.me/api/portraits/men/27.jpg" alt="avatar" loading="lazy" />
        <figcaption class="sr-only">Michael</figcaption>
        <span class="absolute right-0 bottom-0 inline-block w-2.5 h-2.5 rounded-full bg-green-500 border-2 border-white dark:border-gray-950"></span>
      </figure>
      <div class="flex flex-col">
        <span class="font-medium">Michael</span>
        <span class="text-xs text-gray-500">Doctor</span>
      </div>
    </footer>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col justify-between rounded-xl text-sm mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center justify-between w-full gap-1 px-3 pt-3 pb-1">
      <span class="flex items-center justify-center border rounded px-2 py-1 font-medium text-xs bg-green-50 border-green-100 text-green-700 dark:bg-green-600/10 dark:border-green-500/20 dark:text-green-500">Verified</span>
      <button class="ml-auto flex flex-none items-center justify-center w-8 h-8 rounded-full transition-colors hover:bg-gray-200 dark:hover:bg-gray-900">
        <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
        </svg>
      </button>
    </header>
    <section class="flex items-center justify-start gap-2 mt-2 px-3 border-y py-2 bg-gray-50 dark:bg-gray-900 dark:border-gray-800 dark:text-gray-400">
      <img class="flex-none rounded-full w-8 h-8 object-cover" src="https://randomuser.me/api/portraits/women/32.jpg" alt="avatar" loading="lazy" />
      <div class="flex flex-col">
        <span class="font-medium">Alice</span>
        <span class="text-xs text-gray-500">Engineer</span>
      </div>
    </section>
    <footer class="flex items-center justify-start w-full mt-2 gap-2 p-3">
      <button class="flex items-center justify-center h-8 w-full rounded text-xs font-medium uppercase transition-colors duration-300 bg-gray-100 hover:bg-gray-200 dark:bg-gray-900 dark:hover:bg-gray-800 dark:text-gray-400">
        View profile
      </button>
    </footer>
  </article>
</section>

<section class="mb-3 break-inside border flex flex-col gap-0.5 rounded-xl shadow-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
  <article class="overflow-hidden relative flex p-3 flex-col gap-2 text-sm bg-gradient-to-r from-transparent via-indigo-50 to-transparent dark:via-indigo-500/10" data-filter="social">
    <header class="flex items-center gap-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-10 h-10" src="https://randomuser.me/api/portraits/men/57.jpg" alt="Avatar">
      </a>
      <div class="flex flex-col flex-1">
        <a class="inline-block font-bold mr-2 text-base" href="#">Guy Hawkins</a>
        <span class="text-xs text-gray-400">High fever</span>
      </div>
      <div class="flex flex-col justify-center items-center gap-1 flex-none">
        <span class="rounded-dull flex items-center justify-center font-medium text-sm rounded-full px-2 h-6 text-indigo-600 bg-indigo-200">Execute</span>
        <span class="text-xs">23:55 PM</span>
      </div>
    </header>
  </article>
  <article class="overflow-hidden relative flex p-3 flex-col gap-2 text-sm bg-gradient-to-r from-transparent via-rose-50 to-transparent dark:via-rose-500/10" data-filter="social">
    <header class="flex items-center gap-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-10 h-10" src="https://randomuser.me/api/portraits/women/57.jpg" alt="Avatar">
      </a>
      <div class="flex flex-col flex-1">
        <a class="inline-block font-bold mr-2 text-base text-rose-600" href="#">Eleanor Pena</a>
        <span class="text-xs text-gray-400">Sore throato</span>
      </div>
      <div class="flex flex-col justify-center items-center gap-1 flex-none">
        <span class="rounded-dull flex items-center justify-center font-medium text-sm rounded-full px-2 h-6 text-rose-600 bg-rose-200">Lost</span>
        <span class="text-xs">23:55 PM</span>
      </div>
    </header>
  </article>
  <article class="overflow-hidden relative flex p-3 flex-col gap-2 text-sm bg-gradient-to-r from-transparent via-emerald-50 to-transparent dark:via-emerald-500/10" data-filter="social">
    <header class="flex items-center gap-2">
      <a class="inline-block" href="#">
        <img class="rounded-full max-w-none w-10 h-10" src="https://randomuser.me/api/portraits/men/33.jpg" alt="Avatar">
      </a>
      <div class="flex flex-col flex-1">
        <a class="inline-block font-bold mr-2 text-base" href="#">Robert Fox</a>
        <span class="text-xs text-gray-400">44 min ago</span>
      </div>
      <div class="flex flex-col justify-center items-center gap-1 flex-none">
        <span class="rounded-dull flex items-center justify-center font-medium text-sm rounded-full px-2 h-6 text-emerald-600 bg-emerald-200">Earring</span>
        <span class="text-xs">23:55 PM</span>
      </div>
    </header>
  </article>
</section>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="shadow-md border break-inside dark:shadow-gray-700/5 overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <figure class="relative flex items-center justify-center">
      <img class="w-20 h-20" src="https://3dicons.sgp1.cdn.digitaloceanspaces.com/v1/dynamic/premium/video-camera-dynamic-premium.png" />
      <button class="absolute w-6 h-6 top-3 right-3 rounded-full flex items-center justify-center bg-white text-rose-600">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="m9.653 16.915-.005-.003-.019-.01a20.759 20.759 0 0 1-1.162-.682 22.045 22.045 0 0 1-2.582-1.9C4.045 12.733 2 10.352 2 7.5a4.5 4.5 0 0 1 8-2.828A4.5 4.5 0 0 1 18 7.5c0 2.852-2.044 5.233-3.885 6.82a22.049 22.049 0 0 1-3.744 2.582l-.019.01-.005.003h-.002a.739.739 0 0 1-.69.001l-.002-.001Z"></path>
        </svg>
      </button>
    </figure>
    <section class="flex flex-col gap-1 px-3 pb-3 mt-1">
      <header class="flex items-center justify-between w-full">
        <h2 class="text-base font-semibold"><span class="text-indigo-600">Photography</span> Event in New York</h2>
      </header>
      <p class="text-xs">Lorem ipsum dolor sitsws wdwwd.</p>
      <button class="font-medium h-8 px-4 w-full rounded-full mt-2 transition-colors duration-200 bg-gray-100 hover:bg-gray-200 dark:bg-gray-900 dark:hover:bg-gray-800">Join now</button>
    </section>
  </article>
  <article class="shadow-md border break-inside dark:shadow-gray-700/5 overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <figure class="relative flex items-center justify-center">
      <img class="w-20 h-20" src="https://3dicons.sgp1.cdn.digitaloceanspaces.com/v1/dynamic/color/figma-dynamic-color.png" />
      <button class="absolute w-6 h-6 top-3 right-3 rounded-full flex items-center justify-center bg-white text-rose-600">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="m9.653 16.915-.005-.003-.019-.01a20.759 20.759 0 0 1-1.162-.682 22.045 22.045 0 0 1-2.582-1.9C4.045 12.733 2 10.352 2 7.5a4.5 4.5 0 0 1 8-2.828A4.5 4.5 0 0 1 18 7.5c0 2.852-2.044 5.233-3.885 6.82a22.049 22.049 0 0 1-3.744 2.582l-.019.01-.005.003h-.002a.739.739 0 0 1-.69.001l-.002-.001Z"></path>
        </svg>
      </button>
    </figure>
    <section class="flex flex-col gap-1 px-3 pb-3 mt-1">
      <header class="flex items-center justify-between w-full">
        <h3 class="text-base font-semibold"><span class="text-rose-600">Figma experience</span> in San Francisco</h3>
      </header>
      <p class="text-xs">Lorem ipsum dolor sit ametasw.</p>
      <button class="font-medium h-8 px-4 w-full rounded-full mt-2 transition-colors duration-200 bg-gray-100 hover:bg-gray-200 dark:bg-gray-900 dark:hover:bg-gray-800">Join now</button>
    </section>
  </article>
</section>


<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="absolute w-20 h-20 top-0 right-0 -mt-10 -mr-10 bg-gradient-to-br from-rose-500 to-amber-500 rounded-full"></div>
    <div class="absolute left-1/2 top-0 w-14 h-14 bg-rose-500/40 blur-2xl"></div>
    <header class="relative">
      <h2 class="text-base font-semibold mb-2">Meetings</h2>
      <p class="text-gray-500 dark:text-gray-400">Social media widgets</p>
    </header>
    <section class="flex items-center justify-between w-full gap-2 mt-2">
      <button class="h-8 flex-1 px-2 flex items-center justify-center rounded-full font-medium bg-gray-200 dark:bg-gray-800">
        <span class="w-2 h-2 bg-rose-500 rounded-full mr-2"></span>
        <span>Offline</span>
      </button>
      <button class="flex-none h-8 w-8 flex items-center justify-center rounded-full bg-gray-200 dark:bg-gray-800">
        <svg width="24" height="24" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="M3 10a1.5 1.5 0 1 1 3 0 1.5 1.5 0 0 1-3 0ZM8.5 10a1.5 1.5 0 1 1 3 0 1.5 1.5 0 0 1-3 0ZM15.5 8.5a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3Z"></path>
        </svg>
      </button>
    </section>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <div class="absolute w-20 h-20 top-0 right-0 -mt-10 -mr-10 bg-gradient-to-br from-green-500 to-cyan-500 rounded-full"></div>
    <div class="absolute right-1/2 top-0 w-14 h-14 bg-green-500/40 blur-2xl"></div>
    <header class="relative">
      <h2 class="text-base font-semibold mb-2">Chat</h2>
      <p class="text-gray-500 dark:text-gray-400">Social media widgets</p>
    </header>
    <section class="flex items-center justify-between w-full gap-2 mt-2">
      <button class="h-8 flex-1 px-2 flex items-center justify-center rounded-full font-medium bg-gray-200 dark:bg-gray-800">
        <span class="w-2 h-2 bg-green-500 rounded-full mr-2"></span>
        <span>Online</span>
      </button>
      <button class="flex-none h-8 w-8 flex items-center justify-center rounded-full bg-gray-200 dark:bg-gray-800">
        <svg width="24" height="24" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="M3 10a1.5 1.5 0 1 1 3 0 1.5 1.5 0 0 1-3 0ZM8.5 10a1.5 1.5 0 1 1 3 0 1.5 1.5 0 0 1-3 0ZM15.5 8.5a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3Z"></path>
        </svg>
      </button>
    </section>
  </article>
</section>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-2 justify-start">
      <img class="w-9 h-9 rounded-full" src="https://randomuser.me/api/portraits/women/65.jpg" alt="avatar" loading="lazy" />
      <div class="flex flex-col">
        <h2 class="text-sm font-medium leading-snug">
          Alice
          <br>
          Anderson
        </h2>
      </div>
    </header>
    <p class="text-xs mt-2 text-gray-500 dark:text-gray-400">Personal assistant from company</p>
    <button class="flex-none w-full px-3 border h-7 text-xs flex items-center justify-center rounded-full transition-colors duration-200 bg-white hover:border-gray-300 dark:bg-gray-950 dark:border-gray-800 dark:hover:border-gray-700">
      Connect
    </button>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
    <header class="flex items-center gap-2 justify-start">
      <img class="w-9 h-9 rounded-full" src="https://randomuser.me/api/portraits/men/66.jpg" alt="avatar" loading="lazy" />
      <div class="flex flex-col">
        <h2 class="text-sm font-medium leading-snug">
          Armando
          <br>
          Ortega
        </h2>
      </div>
    </header>
    <p class="text-xs mt-2 text-gray-500 dark:text-gray-400">Personal assistant from company</p>
    <button class="flex-none w-full px-3 border h-7 text-xs flex items-center justify-center rounded-full transition-colors duration-200 bg-white hover:border-gray-300 dark:bg-gray-950 dark:border-gray-800 dark:hover:border-gray-700">
      Connect
    </button>
  </article>
</section>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-row items-start gap-3 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="social">
  <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 512 512" width="36" height="36">
    <path fill="#73A1FB" d="M160.325,256.018c0,52.754,42.919,95.67,95.675,95.67c52.753,0,95.668-42.917,95.668-95.67 c0-52.754-42.916-95.673-95.668-95.673C203.244,160.344,160.325,203.263,160.325,256.018z"></path><path fill="#DA143A" d="M476.299,129.73c0.745-1.311,0.732-2.921-0.039-4.219c-22.285-37.532-53.998-68.971-91.712-90.916 C345.679,11.975,301.226,0.019,256,0.019c-78.269,0-151.211,35.125-200.125,96.368c-1.079,1.35-1.22,3.221-0.356,4.717 l72.066,124.819c0.755,1.309,2.149,2.098,3.633,2.098c0.188,0,0.379-0.013,0.569-0.039c1.689-0.23,3.07-1.459,3.497-3.109 c14.21-55.059,63.851-93.513,120.716-93.513c3.529,0,7.173,0.161,10.836,0.473c0.119,0.012,0.24,0.017,0.359,0.017h205.456 C474.161,131.852,475.554,131.043,476.299,129.73z"></path>
    <path fill="#78B86D" d="M293.829,377.597c-1.042-1.348-2.792-1.927-4.442-1.471c-10.839,3.018-22.071,4.548-33.387,4.548 c-48.079,0-92.392-28.199-112.893-71.838c-0.05-0.107-0.106-0.212-0.165-0.316L40.139,130.465c-0.749-1.301-2.135-2.098-3.634-2.098 c-0.007,0-0.015,0-0.022,0c-1.507,0.008-2.896,0.823-3.634,2.135C11.36,168.633,0,212.036,0,256.018 c0,61.7,22.259,121.299,62.677,167.817c40.017,46.055,95.108,76.364,155.129,85.345c0.208,0.032,0.416,0.045,0.623,0.045 c1.482,0,2.876-0.789,3.633-2.098l72.085-124.857C294.999,380.791,294.873,378.945,293.829,377.597z"></path>
    <path fill="#F1CB30" d="M490.471,159.854H346.147c-1.706,0-3.242,1.032-3.884,2.61c-0.645,1.578-0.27,3.391,0.947,4.583 c24.148,23.673,37.447,55.269,37.447,88.97c0,25.513-7.698,50.065-22.264,71.005c-0.067,0.097-0.129,0.196-0.188,0.299 L255.223,505.686c-0.754,1.306-0.749,2.916,0.012,4.219c0.754,1.288,2.134,2.077,3.623,2.077c0.015,0,0.032,0,0.047,0 c67.769-0.755,131.362-27.717,179.064-75.914C485.708,387.83,512,323.887,512,256.018c0-32.259-5.929-63.716-17.623-93.5 C493.746,160.91,492.197,159.854,490.471,159.854z"></path>
  </svg>
  <div class="flex flex-col">
    <header class="flex items-center justify-between w-full">
      <h2 class="text-base font-medium">UX/UI Designer</h2>
      <span class="h-5 px-2 text-xs rounded-md flex items-center justify-center bg-green-100 text-green-600 dark:bg-green-500/30 dark:text-green-300">Pending</span>
    </header>
    <p class="text-xs mt-1">
      Minim dolor in amet nulla laboris enim dolore consequat proident.
    </p>
    <div class="flex items-center gap-2 text-xs mt-1">
      <span>September 22 - 2022</span>
      <svg xmlns="http://www.w3.org/2000/svg" class="flex-none ml-1" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <polyline points="20 6 9 17 4 12"></polyline>
      </svg>
    </div>
  </div>
</article>

<section class="mb-3 grid grid-cols-2 gap-3">
  <article class="shadow-md break-inside dark:shadow-gray-700/5 overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white" data-filter="social">
    <figure class="relative">
      <img class="w-full max-w-full h-full max-h-[5rem] object-cover" src="https://images.pexels.com/photos/3760956/pexels-photo-3760956.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Sound On" alt="portada" data-author-profile="https://www.pexels.com/es-es/@sound-on/"/>
      <button class="absolute w-6 h-6 top-3 right-3 rounded-full flex items-center justify-center bg-white text-rose-600">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="m9.653 16.915-.005-.003-.019-.01a20.759 20.759 0 0 1-1.162-.682 22.045 22.045 0 0 1-2.582-1.9C4.045 12.733 2 10.352 2 7.5a4.5 4.5 0 0 1 8-2.828A4.5 4.5 0 0 1 18 7.5c0 2.852-2.044 5.233-3.885 6.82a22.049 22.049 0 0 1-3.744 2.582l-.019.01-.005.003h-.002a.739.739 0 0 1-.69.001l-.002-.001Z"></path>
        </svg>
      </button>
    </figure>
    <section class="flex flex-col gap-1 px-3 pb-3 mt-1">
      <header class="flex items-center justify-between w-full">
        <h3 class="text-sm font-medium">Maria Doe</h3>
        <span class="flex items-center gap-1 text-amber-500">
          <svg width="14" height="14" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path clip-rule="evenodd" fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z"></path>
          </svg>
          <span class="text-xs mt-0.5 font-medium text-black dark:text-gray-300">4.5</span>
        </span>
      </header>
      <p class="text-xs">Lorem ipsum dolor sit amet, con seccgel.</p>
    </section>
  </article>
  <article class="shadow-md break-inside dark:shadow-gray-700/5 overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white" data-filter="social">
    <figure class="relative">
      <img class="w-full max-w-full h-full max-h-[5rem] object-cover" src="https://images.pexels.com/photos/3658708/pexels-photo-3658708.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" data-author="Craig Adderley" alt="portada" data-author-profile="https://www.pexels.com/es-es/@thatguycraig000/" />
      <button class="absolute w-6 h-6 top-3 right-3 rounded-full flex items-center justify-center bg-white text-rose-600">
        <svg width="16" height="16" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <path d="m9.653 16.915-.005-.003-.019-.01a20.759 20.759 0 0 1-1.162-.682 22.045 22.045 0 0 1-2.582-1.9C4.045 12.733 2 10.352 2 7.5a4.5 4.5 0 0 1 8-2.828A4.5 4.5 0 0 1 18 7.5c0 2.852-2.044 5.233-3.885 6.82a22.049 22.049 0 0 1-3.744 2.582l-.019.01-.005.003h-.002a.739.739 0 0 1-.69.001l-.002-.001Z"></path>
        </svg>
      </button>
    </figure>
    <section class="flex flex-col gap-1 px-3 pb-3 mt-1">
      <header class="flex items-center justify-between w-full">
        <h3 class="text-sm font-medium">Jhonas Karl</h3>
        <span class="flex items-center gap-1 text-amber-500">
          <svg width="14" height="14" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path clip-rule="evenodd" fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z"></path>
          </svg>
          <span class="text-xs mt-0.5 font-medium text-black dark:text-gray-300">4.5</span>
        </span>
      </header>
      <p class="text-xs">Lorem ipsum dolor sit ametaau.</p>
    </section>
  </article>
</section>
