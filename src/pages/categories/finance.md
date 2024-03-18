---
layout: "../../layouts/ExpoLayout.astro"
slug: 'finance'
category: 'Finance'
tags: ['finance']
title: 'Widget components with tailwind CSS'
visible: true
---

<article class="border shadow-sm break-inside relative rounded-xl flex items-center justify-between overflow-hidden p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center gap-3">
		<div class="flex-none w-10 h-10 flex items-center justify-center rounded-full text-white bg-emerald-600">
			<span class="font-bold text-xl">B</span>
		</div>
		<div class="flex w-full flex-col">
			<h2 class="font-medium text-base">Balance</h2>
			<p class="text-xs text-gray-500">Last 30 days</p>
		</div>
	</header>
	<div class="flex items-center gap-2 flex-none">
		<svg class="text-green-600" width="61" height="26" viewBox="0 0 71 26" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M1.84302 25C2.10589 23.2857 2.63376 21.7799 3.37603 20.2188C4.66585 17.506 6.18161 14.8883 8.36827 12.846C8.73909 12.4997 9.74038 11.2944 10.2746 11.9856C11.2468 13.2436 11.5995 15.0509 12.2755 16.4783C12.4112 16.765 12.4558 17.3189 12.7632 17.2924C12.9788 17.2738 12.919 16.8745 12.9922 16.6638C13.4176 15.4388 14.1866 14.245 15.2021 13.4591C15.8166 12.9836 17.28 11.8409 18.0591 12.4699C18.9592 13.1966 19.1947 14.393 19.5324 15.4479C19.6915 15.9449 19.933 16.4229 20.1197 16.9111C20.2635 17.2872 20.3337 17.3458 20.5925 16.9832C21.4439 15.7909 22.9324 14.659 24.221 15.9322C24.5822 16.2891 24.8087 16.6538 25.316 16.3238C25.819 15.9965 25.8846 16.2426 26.1024 16.7823C26.3462 17.3863 26.6523 19.1571 27.4314 18.2558C27.5407 18.1293 28.4257 16.9081 28.6209 17.0141C29.1285 17.29 29.4078 18.3465 29.5965 18.8483C29.701 19.1262 30.0425 20.4324 30.3829 20.5331C30.4062 20.54 31.1835 17.5795 31.4082 17.2305C31.7074 16.7661 32.0531 16.3254 32.3838 15.8858C32.4852 15.751 32.9464 14.9916 33.2001 14.9121C33.2405 14.8994 33.3056 15.0713 33.3394 15.0872C33.4324 15.131 33.4707 14.9194 33.5037 14.8193C34.2366 12.5976 36.6071 8.26428 37.7531 8.26428C39.2812 8.26428 41.0354 15.9883 41.1066 15.4479C41.2045 14.705 43.3392 11.2347 43.9511 10.7955C44.7929 10.1911 45.0203 11.3227 45.4442 11.9444C45.951 12.6876 46.0957 12.2816 46.6736 11.7126C46.863 11.5261 48.1415 10.0445 48.3958 10.6048C48.8782 11.668 48.6878 13.0269 49.2569 14.0465C49.3655 14.2412 49.4946 14.5051 49.6252 14.6854C49.6934 14.7795 49.6849 14.3521 49.6849 14.2938C49.6849 14.0011 49.9091 14.5355 49.9188 14.5566C50.1151 14.9805 50.3121 15.4245 50.3121 15.9013C50.3121 15.9977 50.268 15.6829 50.332 15.6128C50.6832 15.2278 51.7191 16.8619 51.8152 17.1069C51.9673 17.4946 52.2752 18.4823 52.8007 18.5186C53.0307 18.5344 53.2542 17.6475 53.2785 17.5809C53.7287 16.3481 54.0777 15.085 54.493 13.8404C54.8921 12.6443 55.4335 11.6167 56.0559 10.543C56.3008 10.1204 56.3487 10.8085 56.4043 11.0428C56.4582 11.2702 56.5661 12.044 56.7328 11.4343C57.2918 9.38967 57.6903 7.30464 58.1961 5.2466C58.2985 4.82988 58.4156 4.41543 58.5395 4.00493C58.6137 3.75939 58.7436 4.11069 58.8033 4.22647C59.6182 5.80551 60.0344 7.56383 60.844 9.14679C61.1406 9.7266 61.0502 9.52833 61.1228 8.98192C61.2819 7.78377 61.4579 6.46232 61.8495 5.31873C62.03 4.79136 62.4806 6.03308 62.5164 6.11216C62.8185 6.77908 63.0977 7.45513 63.4223 8.1112C63.4726 8.21289 63.9155 9.30092 64.139 9.32196C64.1588 9.32383 64.5743 7.54237 64.6119 7.42081C64.9229 6.4135 65.4358 5.74578 65.9806 4.88595C66.0777 4.73275 66.1627 4.43125 66.3191 4.31921C66.5398 4.16104 66.683 4.14979 66.8218 3.88643C66.947 3.64872 68.2977 0.934385 68.519 1.00121C68.6776 1.04909 68.6389 1.14287 68.6982 1.25882C68.762 1.38358 68.9822 1.42638 69.0815 1.53704C69.4438 1.94089 69.843 2.02158 69.843 2.64991" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
		</svg>
		<span class="font-bold text-base">€ 654</span>
	</div>
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center justify-between">
		<h2 class="font-medium text-base">Credit available</h2>
		<span class="flex items-center justify-center px-2 py-1 rounded-md font-medium bg-amber-100 dark:text-amber-500 dark:bg-amber-100/20">€ 654</span>
	</header>
</article>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-1 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <div class="absolute left-0 top-0 w-14 h-14 bg-rose-500 opacity-40 blur-2xl"></div>
    <button class="absolute top-3 right-3 inline-flex items-center justify-center w-8 h-8 transition-all rounded-full hover:bg-black/5 dark:hover:bg-gray-900">
      <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
    <section class="flex flex-col gap-1">
      <img class="rounded-full max-w-none w-10 h-10" src="https://randomuser.me/api/portraits/men/97.jpg" alt="Avatar" />
      <h2 class="font-bold text-base">Mathias Felix</h2>
    </section>
    <section class="w-full">
      <h3 class="font-bold text-sm">Є9834.72</h3>
      <p class="text-xs mt-0.5">Statement of earnings</p>
    </section>
    <section class="w-full">
      <svg class="w-full text-rose-500" viewBox="0 0 145 36" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M0 35.9933C0.560537 33.6796 1.68615 31.6473 3.26892 29.5403C6.01928 25.8791 9.2514 22.3461 13.9141 19.5898C14.7049 19.1223 16.84 17.4956 17.9791 18.4285C20.0522 20.1264 20.8043 22.5656 22.2456 24.492C22.5352 24.879 22.6303 25.6265 23.2858 25.5907C23.7454 25.5656 23.6179 25.0268 23.774 24.7424C24.6811 23.0891 26.3208 21.4779 28.4863 20.4172C29.7966 19.7755 32.917 18.2331 34.5784 19.0821C36.4977 20.063 36.9999 21.6776 37.72 23.1013C38.0592 23.7721 38.5742 24.4172 38.9723 25.0761C39.279 25.5837 39.4286 25.6628 39.9806 25.1735C41.796 23.5643 44.9701 22.0366 47.7178 23.755C48.488 24.2367 48.9709 24.7289 50.0527 24.2834C51.1253 23.8417 51.2652 24.1739 51.7296 24.9023C52.2494 25.7175 52.9022 28.1075 54.5634 26.891C54.7966 26.7202 56.6838 25.072 57.1 25.2152C58.1823 25.5875 58.7779 27.0135 59.1802 27.6907C59.403 28.0657 60.1313 29.8287 60.8571 29.9645C60.9069 29.9738 62.5642 25.9782 63.0435 25.5073C63.6813 24.8804 64.4185 24.2857 65.1237 23.6924C65.34 23.5104 66.3235 22.4855 66.8643 22.3781C66.9505 22.361 67.0893 22.5931 67.1615 22.6146C67.3598 22.6736 67.4413 22.3881 67.5117 22.253C67.7699 21.7576 68.2817 20.5396 68.4457 20.16C69.5291 17.651 70.591 15.1805 72.691 12.9421C73.7644 11.7981 75.5041 10.4654 77.5838 10.0703C79.2454 9.75459 80.9653 11.4363 81.6593 12.1703C82.5062 13.0658 83.2608 14.1834 84.3551 14.9656C85.4969 15.7817 85.493 17.3581 86.2868 18.3312C86.3917 18.4598 87.6371 19.5063 87.6877 19.2629C87.8964 18.2603 88.4845 17.4151 89.7892 16.8222C91.5844 16.0065 92.0692 17.5338 92.9732 18.3729C94.0539 19.3759 94.3624 18.828 95.5947 18.06C95.9984 17.8084 98.7248 15.8087 99.2669 16.5649C100.296 17.9999 99.8895 19.8338 101.103 21.2099C101.335 21.4727 101.61 21.8289 101.888 22.0722C102.034 22.1993 102.016 21.6224 102.016 21.5437C102.016 21.1487 102.494 21.8699 102.515 21.8983C102.933 22.4705 103.353 23.0698 103.353 23.7132C103.353 23.8434 103.259 23.4184 103.396 23.3238C104.144 22.8043 106.353 25.0098 106.558 25.3404C106.883 25.8636 107.539 27.1967 108.66 27.2457C109.15 27.2671 109.627 26.07 109.679 25.9801C110.639 24.3163 111.383 22.6116 112.268 20.9318C113.119 19.3175 114.274 17.9306 115.601 16.4815C116.123 15.9111 116.225 16.8398 116.344 17.156C116.459 17.463 116.689 18.5072 117.044 17.6845C118.236 14.9249 119.086 12.1108 120.165 9.33321C120.383 8.77079 120.633 8.21143 120.897 7.65739C121.055 7.32601 121.332 7.80013 121.46 7.95639C123.197 10.0875 124.085 12.4606 125.811 14.5971C126.443 15.3796 126.251 15.112 126.405 14.3746C126.745 12.7575 127.12 10.974 127.955 9.43056C128.34 8.7188 129.301 10.3947 129.377 10.5014C130.021 11.4015 130.617 12.3139 131.309 13.1994C131.416 13.3367 132.36 14.8051 132.837 14.8335C132.879 14.836 133.765 12.4317 133.845 12.2676C134.508 10.9081 135.602 10.0069 136.764 8.84645C136.971 8.63969 137.152 8.23277 137.486 8.08156C137.956 7.86809 138.262 7.8529 138.558 7.49746C138.825 7.17664 141.705 3.51325 142.177 3.60344C142.515 3.66807 142.432 3.79463 142.559 3.95112C142.695 4.1195 143.164 4.17727 143.376 4.32662C144.149 4.87168 145 4.98058 145 5.82859"
          stroke="currentColor" stroke-linecap="round" stroke-width="2" />
			</svg>
    </section>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-1 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <button class="absolute top-3 right-3 inline-flex items-center justify-center w-8 h-8 transition-all rounded-full hover:bg-black/5 dark:hover:bg-gray-900">
      <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
    <section class="flex flex-col gap-1">
      <img class="rounded-full max-w-none w-10 h-10" src="https://randomuser.me/api/portraits/women/97.jpg" alt="Avatar" />
      <h2 class="font-bold text-base">Marina Vargas</h2>
    </section>
    <section class="w-full">
      <h3 class="font-bold text-sm">Є4764.72</h3>
      <p class="text-xs mt-0.5">Statement of earnings</p>
    </section>
    <section class="w-full">
      <svg class="w-full text-indigo-500" viewBox="0 0 145 36" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M0 35.9933C0.560537 33.6796 1.68615 31.6473 3.26892 29.5403C6.01928 25.8791 9.2514 22.3461 13.9141 19.5898C14.7049 19.1223 16.84 17.4956 17.9791 18.4285C20.0522 20.1264 20.8043 22.5656 22.2456 24.492C22.5352 24.879 22.6303 25.6265 23.2858 25.5907C23.7454 25.5656 23.6179 25.0268 23.774 24.7424C24.6811 23.0891 26.3208 21.4779 28.4863 20.4172C29.7966 19.7755 32.917 18.2331 34.5784 19.0821C36.4977 20.063 36.9999 21.6776 37.72 23.1013C38.0592 23.7721 38.5742 24.4172 38.9723 25.0761C39.279 25.5837 39.4286 25.6628 39.9806 25.1735C41.796 23.5643 44.9701 22.0366 47.7178 23.755C48.488 24.2367 48.9709 24.7289 50.0527 24.2834C51.1253 23.8417 51.2652 24.1739 51.7296 24.9023C52.2494 25.7175 52.9022 28.1075 54.5634 26.891C54.7966 26.7202 56.6838 25.072 57.1 25.2152C58.1823 25.5875 58.7779 27.0135 59.1802 27.6907C59.403 28.0657 60.1313 29.8287 60.8571 29.9645C60.9069 29.9738 62.5642 25.9782 63.0435 25.5073C63.6813 24.8804 64.4185 24.2857 65.1237 23.6924C65.34 23.5104 66.3235 22.4855 66.8643 22.3781C66.9505 22.361 67.0893 22.5931 67.1615 22.6146C67.3598 22.6736 67.4413 22.3881 67.5117 22.253C67.7699 21.7576 68.2817 20.5396 68.4457 20.16C69.5291 17.651 70.591 15.1805 72.691 12.9421C73.7644 11.7981 75.5041 10.4654 77.5838 10.0703C79.2454 9.75459 80.9653 11.4363 81.6593 12.1703C82.5062 13.0658 83.2608 14.1834 84.3551 14.9656C85.4969 15.7817 85.493 17.3581 86.2868 18.3312C86.3917 18.4598 87.6371 19.5063 87.6877 19.2629C87.8964 18.2603 88.4845 17.4151 89.7892 16.8222C91.5844 16.0065 92.0692 17.5338 92.9732 18.3729C94.0539 19.3759 94.3624 18.828 95.5947 18.06C95.9984 17.8084 98.7248 15.8087 99.2669 16.5649C100.296 17.9999 99.8895 19.8338 101.103 21.2099C101.335 21.4727 101.61 21.8289 101.888 22.0722C102.034 22.1993 102.016 21.6224 102.016 21.5437C102.016 21.1487 102.494 21.8699 102.515 21.8983C102.933 22.4705 103.353 23.0698 103.353 23.7132C103.353 23.8434 103.259 23.4184 103.396 23.3238C104.144 22.8043 106.353 25.0098 106.558 25.3404C106.883 25.8636 107.539 27.1967 108.66 27.2457C109.15 27.2671 109.627 26.07 109.679 25.9801C110.639 24.3163 111.383 22.6116 112.268 20.9318C113.119 19.3175 114.274 17.9306 115.601 16.4815C116.123 15.9111 116.225 16.8398 116.344 17.156C116.459 17.463 116.689 18.5072 117.044 17.6845C118.236 14.9249 119.086 12.1108 120.165 9.33321C120.383 8.77079 120.633 8.21143 120.897 7.65739C121.055 7.32601 121.332 7.80013 121.46 7.95639C123.197 10.0875 124.085 12.4606 125.811 14.5971C126.443 15.3796 126.251 15.112 126.405 14.3746C126.745 12.7575 127.12 10.974 127.955 9.43056C128.34 8.7188 129.301 10.3947 129.377 10.5014C130.021 11.4015 130.617 12.3139 131.309 13.1994C131.416 13.3367 132.36 14.8051 132.837 14.8335C132.879 14.836 133.765 12.4317 133.845 12.2676C134.508 10.9081 135.602 10.0069 136.764 8.84645C136.971 8.63969 137.152 8.23277 137.486 8.08156C137.956 7.86809 138.262 7.8529 138.558 7.49746C138.825 7.17664 141.705 3.51325 142.177 3.60344C142.515 3.66807 142.432 3.79463 142.559 3.95112C142.695 4.1195 143.164 4.17727 143.376 4.32662C144.149 4.87168 145 4.98058 145 5.82859"
          stroke="currentColor" stroke-linecap="round" stroke-width="2" />
      </svg>
    </section>
  </article>
</section>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <header class="flex items-start justify-between">
		<div class="flex flex-col gap-1">
			<h2 class="font-medium text-lg leading-6"> Summary of financials </h2>
			<p>The best solution for your online payments</p>
		</div>
		<button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
			<svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
			</svg>
		</button>
	</header>
  <div class="relative w-full border-x flex items-start justify-start h-36 dark:border-gray-800 text-gray-500">
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-12 bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs text-black dark:text-white">Jan</span>
        <span class="text-xs text-green-500">2024</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-24 bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Feb</span>
        <span class="text-xs">2023</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[4rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Mar</span>
        <span class="text-xs">2022</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[3rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Apr</span>
        <span class="text-xs">2021</span>
      </div>
    </div>
    <div class="flex-1 px-3 z-[1] h-full flex flex-col justify-center">
      <div class="w-full h-full flex-1 flex items-center">
        <div class="w-full rounded-full h-[2.5rem] bg-gradient-to-t from-indigo-600 to-violet-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">May</span>
        <span class="text-xs">2020</span>
      </div>
    </div>
  </div>
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-col items-start gap-1">
		<span class="flex items-center justify-center px-2 py-1 text-xs rounded-md font-medium bg-rose-100 dark:text-rose-500 dark:bg-rose-100/20">€ 9874</span>
		<h2 class="font-medium text-base">Available cash</h2>
	</header>
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<svg width="71" height="26" viewBox="0 0 71 26" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M1.84302 25C2.10589 23.2857 2.63376 21.7799 3.37603 20.2188C4.66585 17.506 6.18161 14.8883 8.36827 12.846C8.73909 12.4997 9.74038 11.2944 10.2746 11.9856C11.2468 13.2436 11.5995 15.0509 12.2755 16.4783C12.4112 16.765 12.4558 17.3189 12.7632 17.2924C12.9788 17.2738 12.919 16.8745 12.9922 16.6638C13.4176 15.4388 14.1866 14.245 15.2021 13.4591C15.8166 12.9836 17.28 11.8409 18.0591 12.4699C18.9592 13.1966 19.1947 14.393 19.5324 15.4479C19.6915 15.9449 19.933 16.4229 20.1197 16.9111C20.2635 17.2872 20.3337 17.3458 20.5925 16.9832C21.4439 15.7909 22.9324 14.659 24.221 15.9322C24.5822 16.2891 24.8087 16.6538 25.316 16.3238C25.819 15.9965 25.8846 16.2426 26.1024 16.7823C26.3462 17.3863 26.6523 19.1571 27.4314 18.2558C27.5407 18.1293 28.4257 16.9081 28.6209 17.0141C29.1285 17.29 29.4078 18.3465 29.5965 18.8483C29.701 19.1262 30.0425 20.4324 30.3829 20.5331C30.4062 20.54 31.1835 17.5795 31.4082 17.2305C31.7074 16.7661 32.0531 16.3254 32.3838 15.8858C32.4852 15.751 32.9464 14.9916 33.2001 14.9121C33.2405 14.8994 33.3056 15.0713 33.3394 15.0872C33.4324 15.131 33.4707 14.9194 33.5037 14.8193C34.2366 12.5976 36.6071 8.26428 37.7531 8.26428C39.2812 8.26428 41.0354 15.9883 41.1066 15.4479C41.2045 14.705 43.3392 11.2347 43.9511 10.7955C44.7929 10.1911 45.0203 11.3227 45.4442 11.9444C45.951 12.6876 46.0957 12.2816 46.6736 11.7126C46.863 11.5261 48.1415 10.0445 48.3958 10.6048C48.8782 11.668 48.6878 13.0269 49.2569 14.0465C49.3655 14.2412 49.4946 14.5051 49.6252 14.6854C49.6934 14.7795 49.6849 14.3521 49.6849 14.2938C49.6849 14.0011 49.9091 14.5355 49.9188 14.5566C50.1151 14.9805 50.3121 15.4245 50.3121 15.9013C50.3121 15.9977 50.268 15.6829 50.332 15.6128C50.6832 15.2278 51.7191 16.8619 51.8152 17.1069C51.9673 17.4946 52.2752 18.4823 52.8007 18.5186C53.0307 18.5344 53.2542 17.6475 53.2785 17.5809C53.7287 16.3481 54.0777 15.085 54.493 13.8404C54.8921 12.6443 55.4335 11.6167 56.0559 10.543C56.3008 10.1204 56.3487 10.8085 56.4043 11.0428C56.4582 11.2702 56.5661 12.044 56.7328 11.4343C57.2918 9.38967 57.6903 7.30464 58.1961 5.2466C58.2985 4.82988 58.4156 4.41543 58.5395 4.00493C58.6137 3.75939 58.7436 4.11069 58.8033 4.22647C59.6182 5.80551 60.0344 7.56383 60.844 9.14679C61.1406 9.7266 61.0502 9.52833 61.1228 8.98192C61.2819 7.78377 61.4579 6.46232 61.8495 5.31873C62.03 4.79136 62.4806 6.03308 62.5164 6.11216C62.8185 6.77908 63.0977 7.45513 63.4223 8.1112C63.4726 8.21289 63.9155 9.30092 64.139 9.32196C64.1588 9.32383 64.5743 7.54237 64.6119 7.42081C64.9229 6.4135 65.4358 5.74578 65.9806 4.88595C66.0777 4.73275 66.1627 4.43125 66.3191 4.31921C66.5398 4.16104 66.683 4.14979 66.8218 3.88643C66.947 3.64872 68.2977 0.934385 68.519 1.00121C68.6776 1.04909 68.6389 1.14287 68.6982 1.25882C68.762 1.38358 68.9822 1.42638 69.0815 1.53704C69.4438 1.94089 69.843 2.02158 69.843 2.64991" stroke="#0396EA" stroke-width="2" stroke-linecap="round"/>
	</svg>			
</article>

<article class="border shadow-sm break-inside flex flex-col items-start rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<section class="w-full flex items-center justify-between p-4">
		<header class="flex items-center gap-4">
			<div class="w-12 h-12 flex items-center justify-center rounded-xl bg-rose-500 text-white">
				<svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
					<path stroke-linecap="round" stroke-linejoin="round" d="M15.59 14.37a6 6 0 0 1-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 0 0 6.16-12.12A14.98 14.98 0 0 0 9.631 8.41m5.96 5.96a14.926 14.926 0 0 1-5.841 2.58m-.119-8.54a6 6 0 0 0-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 0 0-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 0 1-2.448-2.448 14.9 14.9 0 0 1 .06-.312m-2.24 2.39a4.493 4.493 0 0 0-1.757 4.306 4.493 4.493 0 0 0 4.306-1.758M16.5 9a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0Z"></path>
				</svg>
			</div>
			<div>
				<h2 class="text-lg font-medium">Travels</h2>
				<p class="text-gray-500">Last 30 days</p>
			</div>
		</header>
		<span class="text-xl font-semibold">87.45%</span>
	</section>
	<div class="relative w-full -mt-2">
		<span class="absolute top-3 left-1/2 flex items-center justify-center px-2 h-5 text-xs rounded-sm backdrop-blur-sm bg-black/80 text-white dark:bg-white/70 dark:text-black">23%</span>
		<svg class="w-full" viewBox="0 0 174 35" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M17.2031 26.0512L9.09507 22.7143C5.236 21.126 1 23.9634 1 28.1365C1 31.3748 3.62518 34 6.8635 34H167C170.314 34 173 31.3137 173 28V5.56131C173 4.78043 172.636 4.04411 172.016 3.56962C170.948 2.75259 169.426 2.92319 168.565 3.95634L159.509 14.8287C158.355 16.2145 156.424 16.6709 154.772 15.9484C153.375 15.3377 151.753 15.5625 150.575 16.5302L138.369 26.5574C135.982 28.518 132.497 28.3462 130.314 26.1604L120.467 16.2983C119.132 14.9611 117.099 14.6102 115.393 15.4224C113.315 16.4118 110.825 15.6573 109.645 13.6808L106.524 8.45117C104.375 4.84933 99.2869 4.50851 96.676 7.79144L91.5091 14.2884C91.2072 14.668 90.6696 14.763 90.2559 14.5098C89.8428 14.257 89.3062 14.3512 89.004 14.7296L75.413 31.7446C74.2745 33.17 72.4157 34.2408 70.8425 33.3173C68.5276 31.9584 67.2499 28.5518 64.9271 22.9261C61.0172 13.4568 60.1024 2.1075 55.7602 1.22177C47.0293 -0.559169 46.5933 23.8119 39.115 17.8321C34.226 13.9227 28.409 19.4794 24.967 23.7959C23.1136 26.1202 19.9522 27.1826 17.2031 26.0512Z" fill="url(#paint0_linear_2_7)"/>
			<path d="M1 19.3827L17.2031 26.0512C19.9522 27.1826 23.1136 26.1202 24.967 23.7959C28.409 19.4794 34.226 13.9227 39.115 17.8321C46.5933 23.8119 47.0293 -0.559169 55.7602 1.22177C60.1024 2.1075 61.0172 13.4568 64.9271 22.9261C67.2499 28.5518 68.5276 31.9584 70.8425 33.3173C72.4157 34.2408 74.2745 33.17 75.413 31.7446L89.004 14.7295C89.3062 14.3512 89.8428 14.257 90.2559 14.5098V14.5098C90.6696 14.763 91.2072 14.668 91.5091 14.2884L96.676 7.79144C99.2869 4.50851 104.375 4.84933 106.524 8.45117L109.645 13.6808C110.825 15.6574 113.315 16.4118 115.393 15.4224V15.4224C117.099 14.6102 119.132 14.9611 120.467 16.2983L130.314 26.1604C132.497 28.3462 135.982 28.518 138.369 26.5574L150.575 16.5302C151.753 15.5625 153.375 15.3377 154.772 15.9484V15.9484C156.424 16.6709 158.355 16.2145 159.509 14.8287L167.772 4.90828C169.076 3.34313 171.382 3.08468 173 4.32241V4.32241" stroke="url(#paint1_linear_2_7)"/>
			<defs>
			<linearGradient id="paint0_linear_2_7" x1="87" y1="1" x2="87" y2="34" gradientUnits="userSpaceOnUse">
				<stop stop-color="#FF00E6" stop-opacity="0.21"/>
				<stop offset="1" stop-color="white" stop-opacity="0"/>
			</linearGradient>
			<linearGradient id="paint1_linear_2_7" x1="0.999998" y1="19.5" x2="173" y2="2.99999" gradientUnits="userSpaceOnUse">
				<stop stop-color="#F10266"/>
				<stop offset="0.42819" stop-color="#F337F7"/>
				<stop offset="0.764243" stop-color="#891CF7"/>
				<stop offset="1" stop-color="#1C59F7"/>
			</linearGradient>
			</defs>
		</svg>
	</div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <button class="z-[1] w-9 h-9 absolute top-4 right-4 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 14 4" fill="none">
      <path d="M10.8889 2C10.8889 2.39782 11.0528 2.77936 11.3445 3.06066C11.6362 3.34196 12.0319 3.5 12.4444 3.5C12.857 3.5 13.2527 3.34196 13.5444 3.06066C13.8361 2.77936 14 2.39782 14 2C14 1.60218 13.8361 1.22064 13.5444 0.93934C13.2527 0.658035 12.857 0.5 12.4444 0.5C12.0319 0.5 11.6362 0.658035 11.3445 0.93934C11.0528 1.22064 10.8889 1.60217 10.8889 2ZM5.44444 2C5.44444 2.39782 5.60833 2.77935 5.90006 3.06066C6.19178 3.34196 6.58744 3.5 7 3.5C7.41256 3.5 7.80822 3.34196 8.09994 3.06066C8.39167 2.77935 8.55556 2.39782 8.55556 2C8.55556 1.60217 8.39167 1.22064 8.09994 0.93934C7.80822 0.658035 7.41256 0.499999 7 0.499999C6.58744 0.499999 6.19178 0.658035 5.90006 0.939339C5.60833 1.22064 5.44444 1.60217 5.44444 2ZM-1.31134e-07 2C-1.65913e-07 2.39782 0.163889 2.77935 0.455612 3.06066C0.747335 3.34196 1.143 3.5 1.55556 3.5C1.96811 3.5 2.36378 3.34196 2.6555 3.06066C2.94722 2.77935 3.11111 2.39782 3.11111 2C3.11111 1.60217 2.94722 1.22064 2.6555 0.939339C2.36378 0.658035 1.96811 0.499999 1.55556 0.499999C1.143 0.499999 0.747335 0.658034 0.455612 0.939339C0.163889 1.22064 -9.63552e-08 1.60217 -1.31134e-07 2Z" fill="currentColor"></path>
    </svg>
  </button>
  <header class="p-3 w-full flex items-center text-center justify-center flex-col">
    <img class="flex-none mt-1 w-14 h-14 rounded-full ring-2 ring-pink-600 border-2 border-white dark:border-gray-950" src="https://randomuser.me/api/portraits/men/86.jpg" alt="avatar" loading="lazy">
    <div class="flex flex-col mt-2">
      <a href="#" class="text-base font-semibold block">Jhonathan</a>
      <span class="text-gray-600 dark:text-gray-400">Economist and writer</span>
    </div>
  </header>
  <div class="relative -mt-3 w-full grid grid-cols-7 items-start justify-start h-36 pb-3 dark:border-gray-800 text-gray-500">
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs dark:text-white">Mon</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[6rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Tue</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[2rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Wed</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Thu</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[5rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Fri</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full border-r flex flex-col justify-center dark:border-gray-800 transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[4rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Sat</span>
      </div>
    </div>
    <div class="w-full px-2.5 z-[1] h-full flex flex-col justify-center transition-all duration-300 bg-gradient-to-t from-transparent via-transparent to-transparent hover:via-rose-100 dark:hover:via-rose-500/10">
      <div class="h-full w-full flex items-center">
        <div class="w-full rounded-full h-[2.5rem] shadow-[0px_0px_14px_1px_#ff007e52] bg-gradient-to-t from-rose-600 to-pink-500"></div>
      </div>
      <div class="flex items-center flex-col justify-center font-medium gap-1">
        <span class="text-xs">Sun</span>
      </div>
    </div>
  </div>
</article>

<section class="grid grid-cols-2 gap-4" >
	<article class="relative overflow-hidden border shadow-sm break-inside rounded-xl gap-2 p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
		<div class="absolute top-0 left-0 w-20 h-20 bg-gradient-to-br from-purple-500/60 to-white dark:to-gray-950 rounded-full flex items-center justify-center blur-2xl"></div>
		<header class="relative flex flex-col gap-2">
			<div class="flex items-center justify-center w-10 h-10 rounded-full bg-gradient-to-br from-purple-500 to-blue-500 text-white">
				<svg width="28" height="28" viewBox="0 0 18 12" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path d="M9.80757 2.07613C8.78994 1.88835 7.73713 1.97028 6.76579 2.31284C6.71863 2.33048 6.6756 2.35671 6.63918 2.39005C6.60275 2.42338 6.57364 2.46317 6.55349 2.50713C6.51281 2.59592 6.51115 2.69633 6.54886 2.78627C6.58658 2.87622 6.66059 2.94833 6.75461 2.98675C6.84862 3.02517 6.95495 3.02674 7.0502 2.99112C7.88656 2.6925 8.79379 2.6169 9.6726 2.77262C9.72411 2.78542 9.77787 2.78801 9.8305 2.78021C9.88313 2.77242 9.93347 2.75441 9.97836 2.72733C10.0233 2.70025 10.0617 2.66468 10.0913 2.62287C10.1209 2.58105 10.141 2.53389 10.1504 2.48437C10.1598 2.43485 10.1581 2.38403 10.1457 2.33513C10.1332 2.28623 10.1101 2.24029 10.0779 2.20023C10.0457 2.16016 10.005 2.12683 9.95852 2.10234C9.91199 2.07784 9.8606 2.06272 9.80757 2.05792V2.07613Z" fill="white"/>
					<path d="M12.536 5.53582C12.8981 5.53582 13.1916 5.25864 13.1916 4.91672C13.1916 4.5748 12.8981 4.29762 12.536 4.29762C12.1739 4.29762 11.8804 4.5748 11.8804 4.91672C11.8804 5.25864 12.1739 5.53582 12.536 5.53582Z" fill="currentColor"/>
					<path d="M17.4193 5.79075C17.3746 5.72833 17.3142 5.67735 17.2435 5.64239C17.1729 5.60744 17.0941 5.58959 17.0143 5.59045C16.6249 5.5394 16.2675 5.35857 16.0068 5.0806C15.5051 4.56276 15.0788 3.98409 14.739 3.35986L16.1273 1.31135C16.2116 1.19264 16.2632 1.05598 16.2775 0.913718C16.2918 0.771454 16.2684 0.628065 16.2093 0.4965C16.1501 0.376807 16.0607 0.272686 15.9489 0.193304C15.8371 0.113922 15.7064 0.0617143 15.5682 0.0412766C14.6853 -0.0710818 13.7867 0.0469934 12.9699 0.382694C12.5017 0.577417 12.0613 0.826691 11.6587 1.12471C10.8702 0.790838 10.0306 0.57726 9.17125 0.491948C5.75347 0.177844 2.62973 2.27187 2.22963 5.04874C2.0737 4.98249 1.93405 4.88638 1.81953 4.76648C1.70501 4.64658 1.61813 4.50552 1.56439 4.35224C1.53002 4.24714 1.51828 4.1366 1.52987 4.02714C1.54146 3.91768 1.57615 3.81153 1.63188 3.71493C1.68185 3.63383 1.75328 3.56638 1.83916 3.51918C1.89772 3.48571 1.94872 3.44167 1.98925 3.38958C2.02978 3.33749 2.05906 3.27837 2.07539 3.21559C2.09173 3.15282 2.09482 3.08762 2.08448 3.02372C2.07413 2.95982 2.05056 2.89847 2.01511 2.84318C1.97966 2.78788 1.93302 2.73972 1.87786 2.70144C1.8227 2.66316 1.7601 2.63552 1.69362 2.62009C1.62715 2.60466 1.55811 2.60175 1.49045 2.61152C1.42278 2.62129 1.35781 2.64354 1.29926 2.67702C1.0659 2.81228 0.873332 3.00197 0.74007 3.22784C0.616173 3.43982 0.538288 3.67301 0.510973 3.91375C0.483659 4.1545 0.507462 4.39797 0.580991 4.62993C0.671497 4.91101 0.821583 5.17177 1.02213 5.39637C1.22267 5.62096 1.46949 5.80471 1.74757 5.93642L2.19106 6.14582C2.24647 7.25396 2.54524 8.33911 3.06841 9.33239L3.15036 9.50537C3.56847 10.3404 4.10175 11.1195 4.73633 11.8225C4.7815 11.871 4.83711 11.9099 4.89944 11.9366C4.96178 11.9633 5.02942 11.9772 5.09787 11.9772H7.27677C7.35572 11.9769 7.43337 11.9582 7.50289 11.9228C7.57241 11.8875 7.63167 11.8366 7.67546 11.7745C7.71926 11.7125 7.74625 11.6413 7.75406 11.5671C7.76187 11.4929 7.75027 11.418 7.72026 11.349L7.53226 10.9393L8.10109 10.9985C8.74227 11.0584 9.38814 11.0584 10.0293 10.9985C10.2077 11.2716 10.4005 11.5448 10.6126 11.8134C10.657 11.8707 10.715 11.9175 10.782 11.9499C10.8489 11.9823 10.923 11.9995 10.9983 12H13.0904C13.1699 11.9999 13.2483 11.9813 13.3183 11.9457C13.3884 11.9101 13.4481 11.8587 13.492 11.796C13.5359 11.7334 13.5627 11.6614 13.57 11.5866C13.5773 11.5118 13.5649 11.4364 13.5339 11.3672C13.4519 11.1851 13.37 10.9894 13.3073 10.821C13.2205 10.5797 13.153 10.3657 13.1 10.1609C13.6324 9.88948 14.121 9.54764 14.551 9.14575C15.0313 9.20057 15.5169 9.20057 15.9972 9.14575C16.0805 9.13385 16.1591 9.10152 16.2251 9.052C16.291 9.00248 16.3421 8.93749 16.3732 8.86351L17.4626 6.21866C17.4933 6.14948 17.5054 6.07422 17.4978 5.99956C17.4902 5.92491 17.4633 5.85318 17.4193 5.79075ZM15.5971 8.26717C15.2187 8.28751 14.839 8.27073 14.4642 8.21709C14.0375 8.14902 13.6255 8.01522 13.2446 7.82105C13.1319 7.76823 13.0017 7.75918 12.8819 7.79583C12.7621 7.83247 12.6623 7.91191 12.6038 8.01715C12.5452 8.12239 12.5326 8.24509 12.5685 8.35901C12.6045 8.47293 12.6863 8.56904 12.7963 8.62679C12.9978 8.72655 13.2055 8.81472 13.4182 8.89082C13.1553 9.10277 12.8635 9.28038 12.5505 9.41888L12.0395 9.63739C12.0395 9.63739 12.2757 10.6343 12.4348 11.0759H11.2875C11.1718 10.9211 10.5885 10.0016 10.5885 10.0016L10.2655 10.0425C9.58709 10.1349 8.89965 10.1532 8.21678 10.0972C7.89862 10.0699 7.36836 10.0061 6.95379 9.93784L6.2066 9.81493C6.2066 9.81493 6.5103 10.9211 6.56814 11.0622H5.32444C4.8164 10.4748 4.38582 9.83126 4.04216 9.14575L3.95539 8.96821C3.32906 7.82967 3.06456 6.54444 3.19374 5.26724C3.45405 2.90463 6.14393 1.12016 9.07002 1.37963C9.92122 1.46974 10.7496 1.69765 11.5189 2.05336L11.8177 2.18538L12.0588 1.97142C12.4342 1.65467 12.8584 1.39372 13.3169 1.19754C13.9236 0.949055 14.5864 0.847355 15.2452 0.901649L13.6158 3.30978L13.7363 3.53739C14.1574 4.33819 14.6944 5.07974 15.3319 5.74068C15.6281 6.01399 15.9787 6.22906 16.3636 6.37344L15.5971 8.26717Z" fill="currentColor"/>
				</svg>
			</div>
			<div class="flex flex-col items-start">
				<h2 class="font-semibold text-lg">Є9834.72</h2>
				<p class="text-xs">Statement of earnings</p>
			</div>
		</header>
		<section class="w-full">
			<svg class="w-full stroke-[#264653] dark:stroke-green-300" viewBox="0 0 81 34" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M1 33.3915C1.3054 31.0778 1.91866 29.0455 2.781 26.9385C4.27947 23.2773 6.04042 19.7442 8.58081 16.9879C9.01161 16.5205 10.1749 14.8938 10.7955 15.8267C11.925 17.5245 12.3347 19.9638 13.12 21.8902C13.2778 22.2772 13.3296 23.0247 13.6867 22.9889C13.9372 22.9638 13.8677 22.425 13.9527 22.1406C14.4469 20.4872 15.3403 18.8761 16.5201 17.8154C17.234 17.1737 18.9341 15.6313 19.8393 16.4803C20.8849 17.4611 21.1586 19.0758 21.5509 20.4995C21.7357 21.1703 22.0163 21.8154 22.2332 22.4743C22.4003 22.9819 22.4818 23.061 22.7825 22.5717C23.7716 20.9625 25.5009 19.4348 26.9979 21.1532C27.4176 21.6349 27.6807 22.1271 28.2701 21.6816C28.8545 21.2399 28.9307 21.5721 29.1837 22.3005C29.4669 23.1157 29.8226 25.5056 30.7276 24.2892C30.8547 24.1184 31.8829 22.4702 32.1096 22.6134C32.6993 22.9857 33.0238 24.4117 33.243 25.0889C33.3644 25.4639 33.7612 27.2269 34.1566 27.3627C34.1838 27.372 35.0867 23.3764 35.3478 22.9055C35.6953 22.2786 36.097 21.6839 36.4812 21.0906C36.5991 20.9086 37.1348 19.8837 37.4295 19.7763C37.4765 19.7592 37.5521 19.9913 37.5914 20.0128C37.6995 20.0718 37.7439 19.7863 37.7822 19.6512C37.9229 19.1558 38.2018 17.9378 38.2911 17.5581C38.8814 15.0492 39.4599 12.5787 40.6041 10.3403C41.1889 9.19628 42.1367 7.86363 43.2698 7.46848C44.1751 7.15279 45.1121 8.83453 45.4903 9.56847C45.9517 10.464 46.3628 11.5816 46.959 12.3638C47.5811 13.1799 47.5789 14.7563 48.0114 15.7293C48.0686 15.858 48.7471 16.9045 48.7747 16.6611C48.8884 15.6585 49.2088 14.8133 49.9196 14.2204C50.8977 13.4047 51.1618 14.932 51.6544 15.7711C52.2431 16.7741 52.4112 16.2262 53.0826 15.4582C53.3026 15.2066 54.788 13.2069 55.0834 13.9631C55.6438 15.3981 55.4226 17.232 56.0837 18.6081C56.21 18.8709 56.3599 19.2271 56.5116 19.4704C56.5909 19.5975 56.581 19.0206 56.581 18.9419C56.581 18.5469 56.8415 19.2681 56.8528 19.2965C57.0808 19.8687 57.3096 20.468 57.3096 21.1114C57.3096 21.2416 57.2584 20.8166 57.3327 20.722C57.7408 20.2025 58.9442 22.408 59.0559 22.7386C59.2327 23.2618 59.5903 24.5949 60.2008 24.6439C60.468 24.6653 60.7277 23.4682 60.756 23.3783C61.2789 21.7144 61.6845 20.0098 62.1669 18.33C62.6305 16.7157 63.2596 15.3288 63.9826 13.8797C64.2672 13.3093 64.3228 14.238 64.3873 14.5542C64.45 14.8612 64.5754 15.9054 64.769 15.0827C65.4185 12.3231 65.8814 9.50902 66.469 6.7314C66.588 6.16898 66.724 5.60962 66.868 5.05558C66.9541 4.7242 67.1051 5.19833 67.1745 5.35459C68.1211 7.48573 68.6047 9.85884 69.5453 11.9953C69.8898 12.7778 69.7848 12.5102 69.8691 11.7728C70.054 10.1557 70.2585 8.37219 70.7134 6.82875C70.9231 6.117 71.4466 7.79287 71.4882 7.8996C71.8392 8.79971 72.1635 9.71214 72.5406 10.5976C72.5991 10.7348 73.1136 12.2033 73.3733 12.2317C73.3963 12.2342 73.879 9.82987 73.9226 9.66582C74.2839 8.3063 74.8798 7.40512 75.5128 6.24465C75.6256 6.03789 75.7244 5.63097 75.906 5.47975C76.1624 5.26628 76.3288 5.2511 76.49 4.89565C76.6356 4.57484 78.2047 0.911443 78.4619 1.00164C78.6461 1.06626 78.6011 1.19283 78.67 1.34932C78.7442 1.51769 79 1.57546 79.1153 1.72481C79.5362 2.26987 80 2.37877 80 3.22679" stroke-linecap="round"/>
				</svg>
		</section>
	</article>
	<article class="relative overflow-hidden border shadow-sm break-inside rounded-xl gap-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
		<div class="absolute top-0 right-0 w-20 h-20 bg-gradient-to-br from-rose-500/80 to-white dark:to-gray-950 rounded-full flex items-center justify-center blur-2xl"></div>
		<header class="relative flex flex-col gap-2 p-3">
			<div class="flex items-center justify-center w-10 h-10 rounded-full bg-gradient-to-br from-orange-500 to-rose-500 text-white">
				<svg width="24" height="24" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
					<path d="M15.5 2A1.5 1.5 0 0 0 14 3.5v13a1.5 1.5 0 0 0 1.5 1.5h1a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 16.5 2h-1ZM9.5 6A1.5 1.5 0 0 0 8 7.5v9A1.5 1.5 0 0 0 9.5 18h1a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 10.5 6h-1ZM3.5 10A1.5 1.5 0 0 0 2 11.5v5A1.5 1.5 0 0 0 3.5 18h1A1.5 1.5 0 0 0 6 16.5v-5A1.5 1.5 0 0 0 4.5 10h-1Z"></path>
				</svg>
			</div>
			<div class="flex flex-col items-start">
				<h2 class="font-semibold text-lg">Є326.00</h2>
				<p class="text-xs">Statement of earnings</p>
			</div>
		</header>
		<section class="w-full -mt-3 relative">
			<span class="absolute bottom-[28px] left-[50px] flex h-3 w-3">
				<span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-rose-400 opacity-75"></span>
				<span class="relative inline-flex rounded-full h-3 w-3 border-2 border-white bg-rose-500 dark:border-gray-950"></span>
			</span>
			<svg class="w-full" viewBox="0 0 156 54" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M0 35.2121C1.12193 35.7084 2.05287 36.4465 3.15467 36.9127C3.88018 37.2197 4.96816 37.139 5.33694 37.8731C5.78171 38.7584 6.41334 37.1208 6.84078 36.7427C7.35846 36.2847 8.0534 35.1306 8.75167 35.3022C11.4731 35.971 14.5286 35.7848 17.3224 35.7523C17.6226 35.7488 17.9104 35.5687 17.9104 35.8724C17.9104 35.9323 17.9191 36.0299 17.9164 36.1291C18.3683 35.944 19.053 35.7572 19.1768 35.7523C20.6722 35.6935 21.0695 36.6679 22.2975 37.2528C23.2021 37.6838 23.2021 38.1814 23.2021 37.0128C23.2021 35.6556 24.0027 35.3695 24.8303 34.3118C25.1311 33.9274 25.4288 33.5039 25.9497 33.4015C26.5891 33.2758 27.1368 33.243 27.8154 33.2114C30.881 33.0687 33.9468 32.5976 36.9289 31.971C38.3957 31.6628 39.862 31.3127 41.2934 30.8906C41.6774 30.7773 41.6134 31.478 41.7231 31.7509C41.8505 32.068 42.5107 34.0517 42.7407 34.0517C42.8236 34.0517 42.7407 33.905 42.7407 33.8316V32.8113C42.7407 32.182 42.8631 31.787 43.2608 31.2507C43.6045 30.7875 45.7737 28.5386 46.0989 29.21C46.4428 29.9198 46.4557 30.5161 46.9696 31.1707C47.0957 31.3314 47.2004 31.786 47.2296 31.4108C47.276 30.8159 47.1736 29.3852 47.7271 28.9499C48.1423 28.6234 50.4124 33.7413 50.7913 34.4118C50.8749 34.5597 51.4545 35.7515 51.7411 35.3922C52.3142 34.674 53.4118 34.1187 54.1495 33.5815C55.9224 32.2907 57.4928 30.8434 59.1925 29.4901C59.3229 29.3863 59.8755 29.4777 59.7126 29.4201C59.1512 29.2214 59.8806 28.1863 59.984 27.9796C60.7619 26.4247 61.2675 24.79 61.827 23.1679C62.0575 22.4997 62.6297 21.7287 62.6864 21.0271C62.7081 20.7579 62.5243 19.9876 62.8899 19.9067C63.3145 19.8128 63.0628 18.5414 63.1047 18.2261C63.168 17.7501 63.6596 18.91 63.6814 18.9464C64.3669 20.0893 64.9188 21.2579 65.5358 22.4276C65.6835 22.7077 66.0959 24.9687 66.4856 24.6784C67.4868 23.9325 68.1285 22.8128 69.1427 22.0475C70.2353 21.223 70.6307 23.3734 70.8388 23.9581C71.5045 25.829 73.5756 31.4204 72.908 29.5501C72.6058 28.7035 74.1901 27.2634 74.8528 26.8292C75.0807 26.6798 75.3292 26.7757 75.4973 26.9492C75.9782 27.4456 76.0081 27.0539 76.6167 26.6891C78.3694 25.6387 78.9067 30.3861 79.9749 29.5001C80.2389 29.2812 80.3132 28.7752 80.642 28.6298C81.2229 28.3728 81.9908 29.8405 82.1798 30.1303C82.247 30.2335 82.7905 31.2581 83.0391 31.1207C83.4397 30.8992 83.5218 30.7105 84.0567 30.7105C85.5083 30.7105 85.7936 32.3676 86.2503 33.4115C86.7384 34.527 87.4071 35.1912 88.1951 36.1124C88.4976 36.4661 88.1275 35.7882 88.263 35.2321C88.6731 33.5484 89.9177 32.3477 91.248 31.1707C91.4066 31.0304 91.5497 30.6721 91.7908 30.7906C92.3756 31.078 93.0648 28.0325 93.125 27.7895C93.1857 27.5445 93.5668 24.2433 93.8713 24.2582C94.767 24.3023 95.4483 26.6541 95.7369 27.2093C95.9907 27.6972 96.2507 28.3009 96.7207 27.6394C97.5846 26.4234 97.918 24.7089 99.0047 23.648C99.5343 23.131 99.8986 23.9357 100.181 24.2282C100.638 24.7027 101.234 24.0552 101.651 23.8281C102.818 23.1913 104.902 21.5496 105.947 22.9178C106.347 23.4417 106.663 24.1263 107.214 24.5483C107.776 24.9795 108.692 23.1065 108.91 22.8678C109.743 21.9538 110.916 21.4318 111.85 20.627C112.32 20.2215 112.659 19.7113 113.274 19.4465C113.598 19.307 113.885 19.5045 114.066 19.7366C114.583 20.402 115.569 17.7932 115.75 17.4258C116.429 16.0492 116.594 17.5072 117.695 16.9056C120.594 15.3215 124.628 15.045 127.973 15.045C128.215 15.045 128.078 15.0317 127.973 14.9049C127.701 14.574 128.378 14.0083 128.539 13.7445C128.933 13.0974 129.068 12.261 129.353 11.5737C129.443 11.3559 129.67 10.3633 130.054 10.3633C130.72 10.3633 131.718 12.6542 131.953 13.0443C132.34 13.6843 133.31 15.8144 134.215 16.1054C134.401 16.1653 135.866 11.3414 136.058 10.8135C136.186 10.4619 136.627 9.01776 137.177 8.86279C137.448 8.78656 138.345 10.2279 138.512 10.4233C138.52 10.4328 138.527 10.442 138.535 10.4508C138.494 10.3806 138.458 10.3001 138.444 10.2233C138.347 9.69988 138.842 9.23517 139.326 9.00284C140.226 8.57054 141.178 9.81554 141.723 10.2333C142.357 10.7192 144.434 11.2956 144.979 10.5234C146.128 8.89668 145.725 7.5836 145.725 5.78169C145.725 5.375 146.782 4.62733 147.15 4.46123C148.144 4.01306 148.545 4.7615 149.072 5.44157C149.408 5.87513 150.401 7.75245 151.085 7.86243C151.397 7.91259 150.99 7.29903 151.04 7.02213C151.148 6.42555 151.637 5.97194 152.024 5.5016C152.526 4.88998 152.985 4.08963 153.754 3.70096C154.092 3.52983 154.448 2.74764 154.839 2.48052C155.147 2.27048 155.682 1.93861 155.902 1.58023V1C156.046 1.19134 156.019 1.38954 155.902 1.58023V53.9024H0V35.2121Z" fill="url(#paint0_linear_196_88272)"/>
				<path d="M0 35.2121C1.12193 35.7084 2.05287 36.4465 3.15467 36.9127C3.88018 37.2197 4.96816 37.139 5.33694 37.8731C5.78171 38.7584 6.41334 37.1208 6.84078 36.7427C7.35846 36.2847 8.0534 35.1306 8.75167 35.3022C11.4731 35.971 14.5286 35.7848 17.3224 35.7523C17.6226 35.7488 17.9104 35.5687 17.9104 35.8724C17.9104 36.0498 17.9868 36.5562 17.6164 36.4626C17.05 36.3194 18.9616 35.7608 19.1768 35.7523C20.6722 35.6935 21.0695 36.6678 22.2975 37.2528C23.2021 37.6838 23.2021 38.1814 23.2021 37.0128C23.2021 35.6556 24.0027 35.3695 24.8303 34.3118C25.1311 33.9274 25.4288 33.5039 25.9497 33.4015C26.5891 33.2758 27.1368 33.243 27.8154 33.2114C30.881 33.0687 33.9468 32.5976 36.9289 31.971C38.3957 31.6628 39.862 31.3127 41.2934 30.8906C41.6774 30.7773 41.6134 31.478 41.7231 31.7509C41.8505 32.068 42.5107 34.0517 42.7407 34.0517C42.8236 34.0517 42.7407 33.905 42.7407 33.8316C42.7407 33.4915 42.7407 33.1514 42.7407 32.8113C42.7407 32.182 42.8631 31.787 43.2608 31.2507C43.6045 30.7875 45.7737 28.5386 46.0989 29.21C46.4428 29.9198 46.4557 30.516 46.9696 31.1707C47.0957 31.3314 47.2004 31.786 47.2296 31.4108C47.276 30.8159 47.1736 29.3852 47.7271 28.9499C48.1423 28.6234 50.4124 33.7413 50.7913 34.4118C50.8749 34.5597 51.4545 35.7515 51.7411 35.3922C52.3142 34.674 53.4118 34.1187 54.1495 33.5815C55.9224 32.2907 57.4928 30.8434 59.1925 29.4901C59.3229 29.3863 59.8755 29.4777 59.7126 29.4201C59.1512 29.2214 59.8806 28.1863 59.984 27.9796C60.7619 26.4247 61.2675 24.79 61.8271 23.1679C62.0575 22.4997 62.6297 21.7287 62.6864 21.0271C62.7081 20.7579 62.5243 19.9876 62.8899 19.9067C63.3145 19.8128 63.0628 18.5414 63.1047 18.2261C63.168 17.7501 63.6596 18.91 63.6814 18.9464C64.3669 20.0893 64.9188 21.2579 65.5358 22.4276C65.6835 22.7077 66.0959 24.9687 66.4856 24.6784C67.4868 23.9325 68.1285 22.8128 69.1427 22.0475C70.2353 21.223 70.6307 23.3734 70.8388 23.9581C71.5045 25.829 73.5756 31.4204 72.908 29.5501C72.0659 27.1911 75.5473 27.33 76.6167 26.6891C78.3694 25.6387 78.9067 30.3861 79.9749 29.5001C80.2389 29.2812 80.3132 28.7752 80.642 28.6298C81.2229 28.3728 81.9908 29.8405 82.1798 30.1303C82.247 30.2335 82.7905 31.2581 83.0391 31.1207C83.4397 30.8992 83.5218 30.7105 84.0567 30.7105C85.5083 30.7105 85.7936 32.3676 86.2503 33.4115C86.7384 34.527 87.4071 35.1911 88.1951 36.1124C88.4976 36.4661 88.1275 35.7882 88.263 35.2321C88.6731 33.5484 89.9177 32.3477 91.248 31.1707C91.4066 31.0304 91.5497 30.6721 91.7908 30.7906C92.3756 31.078 93.0648 28.0325 93.125 27.7895C93.1857 27.5445 93.5668 24.2433 93.8713 24.2582C94.767 24.3023 95.4483 26.6541 95.7369 27.2093C95.9907 27.6972 96.2507 28.3009 96.7207 27.6394C97.5846 26.4234 97.918 24.7089 99.0047 23.648C99.0383 23.6152 105.641 22.5174 105.947 22.9178C106.347 23.4416 106.663 24.1263 107.214 24.5483C107.776 24.9795 108.692 23.1065 108.91 22.8677C109.743 21.9538 110.916 21.4318 111.85 20.627C112.32 20.2215 112.659 19.7113 113.274 19.4465C113.598 19.307 113.885 19.5045 114.066 19.7366C114.583 20.402 115.569 17.7932 115.75 17.4258C116.429 16.0492 116.594 17.5072 117.695 16.9056C120.594 15.3215 124.628 15.045 127.973 15.045C128.215 15.045 128.078 15.0317 127.973 14.9049C127.701 14.574 128.378 14.0083 128.539 13.7445C128.933 13.0974 129.068 12.261 129.353 11.5737C129.443 11.3559 129.67 10.3633 130.054 10.3633C130.72 10.3633 131.718 12.6542 131.953 13.0443C132.34 13.6843 133.31 15.8144 134.215 16.1054C134.401 16.1653 135.866 11.3414 136.058 10.8135C136.186 10.4619 136.627 9.01776 137.177 8.86279C137.448 8.78656 138.345 10.2279 138.512 10.4233C138.918 10.8994 138.501 10.5322 138.444 10.2233C138.347 9.69988 138.842 9.23517 139.326 9.00284C140.226 8.57054 141.178 9.81554 141.723 10.2333C142.357 10.7192 144.434 11.2956 144.979 10.5234C146.128 8.89668 145.725 7.5836 145.725 5.78169C145.725 5.375 146.782 4.62733 147.15 4.46123C148.144 4.01306 148.545 4.76149 149.072 5.44157C149.408 5.87513 150.401 7.75245 151.085 7.86243C151.397 7.91259 150.99 7.29903 151.04 7.02213C151.148 6.42555 151.637 5.97194 152.024 5.5016C152.526 4.88998 152.985 4.08963 153.754 3.70096C154.092 3.52983 154.448 2.74764 154.839 2.48052C155.31 2.15871 156.317 1.55092 155.902 1" stroke="url(#paint1_linear_196_8827)" stroke-linecap="round" stroke-width="1.5"/>
				<defs>
					<linearGradient id="paint0_linear_196_88272" x1="78" y1="-5.9092" x2="78" y2="53.9024" gradientUnits="userSpaceOnUse">
						<stop offset="0.144057" stop-color="#D60F63" stop-opacity="0.22"/>
						<stop offset="0.983952" stop-color="white" stop-opacity="0"/>
					</linearGradient>
					<linearGradient id="paint1_linear_196_8827" x1="153.629" y1="4.07508" x2="9.25031" y2="54.8124" gradientUnits="userSpaceOnUse">
						<stop offset="0.161546" stop-color="#D60F27"/>
						<stop offset="1" stop-color="#EA0FBA"/>
					</linearGradient>
				</defs>
			</svg>
		</section>
	</article>
</section>

<article class="border shadow-sm break-inside relative overflow-hidden rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="p-4">
		<h2 class="text-lg font-medium">Statistics</h2>
	</header>
	<section class="relative w-full -mt-10">
		<svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 172 103" fill="none">
			<path d="M0 47.0497C1.237 47.7323 2.26342 48.7473 3.47823 49.3885C4.27815 49.8106 5.47771 49.6996 5.88431 50.7092C6.3747 51.9267 7.07112 49.6746 7.54239 49.1546C8.11318 48.5247 8.87939 46.9376 9.64928 47.1735C12.6498 48.0933 16.0187 47.8374 19.0991 47.7926C19.43 47.7878 19.7474 47.5401 19.7474 47.9577C19.7474 48.0402 19.757 48.1743 19.754 48.3108C20.2522 48.0562 21.0072 47.7993 21.1436 47.7926C22.7924 47.7118 23.2305 49.0517 24.5845 49.8562C25.5818 50.4488 25.5818 51.1332 25.5818 49.526C25.5818 47.6596 26.4645 47.2661 27.377 45.8116C27.7087 45.283 28.0369 44.7005 28.6112 44.5597C29.3162 44.3868 29.9201 44.3417 30.6682 44.2983C34.0483 44.102 37.4285 43.4541 40.7165 42.5924C42.3338 42.1685 43.9504 41.6871 45.5286 41.1066C45.952 40.9509 45.8814 41.9144 46.0024 42.2897C46.1429 42.7258 46.8708 45.4539 47.1244 45.4539C47.2158 45.4539 47.1244 45.2521 47.1244 45.1512V43.748C47.1244 42.8826 47.2593 42.3393 47.6978 41.6019C48.0767 40.9648 50.4684 37.8721 50.827 38.7954C51.2061 39.7716 51.2204 40.5915 51.7869 41.4918C51.926 41.7128 52.0414 42.338 52.0737 41.822C52.1248 41.0039 52.0119 39.0363 52.6222 38.4377C53.0799 37.9887 55.5829 45.027 56.0007 45.9492C56.0928 46.1525 56.7318 47.7915 57.0479 47.2974C57.6797 46.3097 58.89 45.546 59.7033 44.8073C61.658 43.0321 63.3895 41.0418 65.2635 39.1806C65.4072 39.0379 66.0165 39.1635 65.837 39.0843C65.218 38.8111 66.0222 37.3876 66.1362 37.1033C66.9939 34.965 67.5513 32.7169 68.1683 30.486C68.4224 29.5672 69.0533 28.5068 69.1158 27.542C69.1397 27.1718 68.937 26.1124 69.3402 26.0012C69.8083 25.872 69.5308 24.1235 69.577 23.69C69.6468 23.0354 70.1888 24.6305 70.2128 24.6805C70.9686 26.2523 71.5771 27.8593 72.2574 29.468C72.4203 29.8532 72.875 32.9626 73.3046 32.5634C74.4085 31.5375 75.116 29.9978 76.2343 28.9452C77.4389 27.8113 77.8749 30.7687 78.1043 31.5728C78.8383 34.1457 81.1218 41.8352 80.3857 39.2631C80.0525 38.0988 81.7994 36.1184 82.53 35.5212C82.7812 35.3158 83.0553 35.4476 83.2406 35.6863C83.7708 36.3689 83.8038 35.8302 84.4748 35.3286C86.4073 33.884 86.9996 40.4128 88.1774 39.1944C88.4685 38.8933 88.5505 38.1975 88.913 37.9975C89.5535 37.6441 90.4001 39.6625 90.6085 40.0611C90.6826 40.2029 91.2819 41.612 91.5559 41.423C91.9976 41.1184 92.0881 40.859 92.6779 40.859C94.2784 40.859 94.5929 43.1378 95.0965 44.5734C95.6346 46.1075 96.3719 47.0209 97.2408 48.2879C97.5743 48.7743 97.1662 47.842 97.3156 47.0772C97.7678 44.7617 99.14 43.1104 100.607 41.4918C100.782 41.2988 100.939 40.8061 101.205 40.969C101.85 41.3643 102.61 37.176 102.676 36.8419C102.743 36.5049 103.163 31.965 103.499 31.9856C104.487 32.0461 105.238 35.2805 105.556 36.0439C105.836 36.715 106.123 37.5452 106.641 36.6355C107.593 34.9632 107.961 32.6053 109.159 31.1464C109.743 30.4354 110.145 31.542 110.456 31.9443C110.96 32.5969 111.617 31.7064 112.076 31.394C113.364 30.5183 115.662 28.2605 116.814 30.1421C117.255 30.8626 117.603 31.8041 118.21 32.3845C118.83 32.9775 119.84 30.4016 120.08 30.0733C120.999 28.8164 122.292 28.0986 123.321 26.9917C123.839 26.4341 124.214 25.7325 124.892 25.3683C125.249 25.1765 125.566 25.448 125.765 25.7673C126.335 26.6823 127.422 23.0946 127.622 22.5894C128.371 20.6963 128.553 22.7013 129.767 21.874C132.963 19.6954 137.41 19.3152 141.099 19.3152C141.365 19.3152 141.214 19.2969 141.099 19.1226C140.799 18.6674 141.545 17.8895 141.722 17.5267C142.157 16.6368 142.306 15.4866 142.62 14.5414C142.719 14.2418 142.969 12.8768 143.393 12.8768C144.127 12.8768 145.227 16.0273 145.487 16.5637C145.914 17.4439 146.983 20.3732 147.981 20.7734C148.186 20.8558 149.801 14.2218 150.013 13.4958C150.153 13.0123 150.64 11.0263 151.247 10.8132C151.545 10.7084 152.534 12.6906 152.718 12.9593C152.727 12.9724 152.735 12.985 152.744 12.9971C152.699 12.9006 152.659 12.7899 152.643 12.6842C152.537 11.9644 153.082 11.3253 153.616 11.0058C154.608 10.4113 155.658 12.1234 156.258 12.6979C156.957 13.3662 159.247 14.1589 159.849 13.0969C161.116 10.8598 160.672 9.054 160.672 6.57596C160.672 6.01666 161.836 4.98844 162.243 4.76C163.338 4.14367 163.781 5.17294 164.362 6.10821C164.732 6.70445 165.827 9.28621 166.581 9.43746C166.925 9.50645 166.476 8.66265 166.531 8.28185C166.65 7.46141 167.189 6.83759 167.616 6.19075C168.17 5.34964 168.675 4.24896 169.523 3.71445C169.896 3.47912 170.289 2.40342 170.72 2.03607C171.059 1.74721 171.65 1.2908 171.892 0.797951V0C172.051 0.263133 172.021 0.535701 171.892 0.797951V103H0V47.0497Z" fill="url(#paint0_linear_181_7796)"/>
			<path d="M0 47.0497C1.237 47.7323 2.26342 48.7473 3.47823 49.3885C4.27815 49.8106 5.47771 49.6996 5.88431 50.7092C6.3747 51.9267 7.07112 49.6746 7.54239 49.1546C8.11318 48.5247 8.87939 46.9376 9.64928 47.1735C12.6498 48.0933 16.0187 47.8373 19.0991 47.7926C19.43 47.7878 19.7474 47.5401 19.7474 47.9577C19.7474 48.2018 19.8316 48.8981 19.4232 48.7694C18.7987 48.5725 20.9064 47.8043 21.1436 47.7926C22.7924 47.7118 23.2305 49.0517 24.5845 49.8562C25.5818 50.4488 25.5818 51.1332 25.5818 49.526C25.5818 47.6596 26.4645 47.2661 27.377 45.8116C27.7087 45.283 28.0369 44.7005 28.6112 44.5597C29.3162 44.3868 29.9201 44.3417 30.6682 44.2983C34.0483 44.102 37.4285 43.4541 40.7165 42.5924C42.3338 42.1685 43.9504 41.6871 45.5286 41.1066C45.952 40.9509 45.8814 41.9144 46.0024 42.2897C46.1429 42.7258 46.8708 45.4539 47.1244 45.4539C47.2158 45.4539 47.1244 45.2521 47.1244 45.1512C47.1244 44.6835 47.1244 44.2157 47.1244 43.748C47.1244 42.8826 47.2593 42.3393 47.6978 41.6019C48.0767 40.9648 50.4684 37.8721 50.827 38.7954C51.2061 39.7716 51.2204 40.5915 51.7869 41.4918C51.926 41.7128 52.0414 42.338 52.0737 41.822C52.1248 41.0039 52.0119 39.0363 52.6222 38.4377C53.0799 37.9887 55.5829 45.027 56.0007 45.9492C56.0929 46.1525 56.7318 47.7915 57.0479 47.2974C57.6797 46.3097 58.89 45.546 59.7033 44.8073C61.658 43.0321 63.3895 41.0418 65.2635 39.1806C65.4072 39.0379 66.0165 39.1635 65.837 39.0843C65.218 38.8111 66.0222 37.3876 66.1362 37.1033C66.9939 34.965 67.5513 32.7169 68.1683 30.486C68.4224 29.5672 69.0533 28.5068 69.1158 27.542C69.1397 27.1718 68.937 26.1124 69.3402 26.0012C69.8082 25.872 69.5308 24.1235 69.577 23.69C69.6468 23.0354 70.1888 24.6305 70.2128 24.6805C70.9686 26.2523 71.5771 27.8593 72.2574 29.468C72.4203 29.8532 72.875 32.9626 73.3046 32.5634C74.4085 31.5375 75.116 29.9978 76.2343 28.9452C77.4389 27.8113 77.8749 30.7687 78.1043 31.5728C78.8383 34.1457 81.1218 41.8352 80.3857 39.2631C80.0525 38.0988 81.7994 36.1184 82.53 35.5212C82.7812 35.3158 83.0553 35.4476 83.2406 35.6863C83.7708 36.3689 83.8038 35.8302 84.4748 35.3286C86.4073 33.884 86.9996 40.4128 88.1774 39.1944C88.4685 38.8932 88.5505 38.1975 88.913 37.9975C89.5535 37.6441 90.4001 39.6624 90.6085 40.0611C90.6826 40.2029 91.2819 41.612 91.5559 41.423C91.9976 41.1184 92.0881 40.859 92.6779 40.859C94.2784 40.859 94.5929 43.1378 95.0965 44.5734C95.6346 46.1075 96.3719 47.0209 97.2408 48.2879C97.5743 48.7743 97.1662 47.842 97.3156 47.0772C97.7678 44.7617 99.14 43.1104 100.607 41.4918C100.782 41.2988 100.939 40.8061 101.205 40.969C101.85 41.3643 102.61 37.176 102.676 36.8419C102.743 36.5049 103.163 31.965 103.499 31.9856C104.487 32.0461 105.238 35.2805 105.556 36.0439C105.836 36.715 106.123 37.5452 106.641 36.6355C107.593 34.9632 107.961 32.6053 109.159 31.1464C109.743 30.4354 110.145 31.542 110.456 31.9443C110.96 32.5969 111.617 31.7064 112.076 31.394C113.364 30.5183 115.662 28.2605 116.814 30.1421C117.255 30.8626 117.603 31.8041 118.21 32.3845C118.83 32.9775 119.84 30.4016 120.08 30.0733C120.999 28.8164 122.292 28.0986 123.321 26.9917C123.839 26.4341 124.214 25.7325 124.892 25.3683C125.249 25.1765 125.566 25.448 125.765 25.7673C126.335 26.6823 127.422 23.0946 127.622 22.5894C128.371 20.6963 128.553 22.7013 129.767 21.874C132.963 19.6954 137.41 19.3152 141.099 19.3152C141.365 19.3152 141.214 19.2969 141.099 19.1226C140.799 18.6674 141.545 17.8895 141.722 17.5267C142.157 16.6368 142.306 15.4866 142.62 14.5414C142.719 14.2418 142.969 12.8768 143.393 12.8768C144.127 12.8768 145.227 16.0273 145.487 16.5637C145.914 17.4439 146.983 20.3732 147.981 20.7734C148.186 20.8558 149.801 14.2218 150.013 13.4958C150.153 13.0123 150.64 11.0263 151.247 10.8132C151.545 10.7084 152.534 12.6906 152.718 12.9593C153.166 13.614 152.706 13.109 152.643 12.6842C152.537 11.9644 153.082 11.3253 153.616 11.0058C154.608 10.4113 155.658 12.1234 156.258 12.6979C156.957 13.3662 159.247 14.1589 159.849 13.0969C161.116 10.8598 160.672 9.054 160.672 6.57596C160.672 6.01666 161.836 4.98844 162.243 4.76C163.338 4.14367 163.781 5.17294 164.362 6.10821C164.732 6.70445 165.827 9.28621 166.581 9.43746C166.925 9.50645 166.476 8.66265 166.531 8.28185C166.65 7.46141 167.189 6.83759 167.616 6.19075C168.17 5.34964 168.675 4.24896 169.523 3.71445C169.896 3.47912 170.289 2.40342 170.72 2.03607C171.239 1.5935 172.35 0.757644 171.892 0" stroke="url(#paint1_linear_181_7796)" stroke-linecap="round"/>
			<defs>
				<linearGradient id="paint0_linear_181_7796" x1="86" y1="-9.50178" x2="86" y2="103" gradientUnits="userSpaceOnUse">
					<stop offset="0.445037" stop-color="#ABFFB8" stop-opacity="0.26"/>
					<stop offset="1" stop-color="white" stop-opacity="0"/>
				</linearGradient>
				<linearGradient id="paint1_linear_181_7796" x1="169.386" y1="4.22896" x2="3.69275" y2="50.9116" gradientUnits="userSpaceOnUse">
					<stop offset="0.161546" stop-color="#00BA4B"/>
					<stop offset="1" stop-color="#0FEACF"/>
				</linearGradient>
			</defs>
		</svg>
		<div class="relative -mt-24 z-[1] bottom-0 left-0 w-full flex items-center justify-between p-4">
			<header class="flex items-center gap-3">
				<div class="flex-none w-10 h-10 flex items-center justify-center rounded-full text-white bg-green-600">
					<span class="font-bold text-xl">C</span>
				</div>
				<div class="flex w-full flex-col">
					<h2 class="font-medium text-base">Company</h2>
					<p class="text-xs text-gray-500">Last 30 days</p>
				</div>
			</header>
			<div class="flex items-center gap-2 flex-none">
				<span class="font-bold text-base">€ 654</span>
			</div>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside flex flex-col items-start justify-between rounded-xl p-3 gap-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center w-full justify-between">
		<svg xmlns="http://www.w3.org/2000/svg" class="w-full max-w-[8rem]" viewBox="0 0 64 24" fill="none">
			<path d="M4.50431 14.4631C4.22471 14.3927 3.94645 14.8661 3.73916 15.054C2.86194 15.849 2.27408 15.0035 1 14.4262V23.8826H63V1C60.3677 2.8416 60.6329 2.0066 59.052 4.29909C55.6212 9.27412 54.914 4.23344 53.0757 4.23344C52.3351 4.23344 50.2766 5.71376 48.1271 6.91703C47.8523 7.07084 46.8028 8.24839 46.6737 8.07828C46.1396 7.37418 44.0965 10.1827 43.93 10.052C41.6785 8.28347 40.8168 9.75068 39.7285 11.3199C39.424 11.7589 38.9643 9.95196 38.5876 9.93299C38.4656 9.92685 38.3131 11.281 38.2887 11.3815C37.9875 12.6263 36.6317 13.2157 36.3419 14.4344C36.2877 14.6625 36.4359 14.9405 36.3147 14.7955C35.8391 14.2258 32.1906 10.6157 31.6785 10.9301C29.5931 12.2105 30.2421 12.335 29.365 9.80989C29.2817 9.57005 29.1233 8.68795 28.6858 9.02615C28.2797 9.34009 28.0228 9.79935 27.6219 10.1053C27.4715 10.2201 25.4672 10.5408 25.0185 11.4594C24.5502 12.4183 23.5864 13.0829 22.6823 13.7573C22.3869 13.9776 21.9474 14.2054 21.718 14.5C21.6032 14.6474 21.3711 14.1585 21.3377 14.0979C20.6245 12.8051 18.1141 11.5408 18.1141 13.8599C18.1141 13.89 18.1473 13.9502 18.1141 13.9502C17.4209 13.9502 14.1658 13.5087 12.1377 13.6055C11.866 13.6184 11.6467 13.6319 11.3907 13.6834C11.1821 13.7255 11.0629 13.8992 10.9425 14.0569C10.5304 14.5962 10.4517 15.5187 9.92829 15.2632C8.17527 14.4077 6.47518 14.9593 4.50431 14.4631Z" fill="url(#paint0_linear_181_7970)"/>
			<path d="M1 14.4262C2.27408 15.0035 2.86194 15.849 3.73916 15.054C3.94645 14.8661 4.22471 14.3927 4.50431 14.4631C6.47518 14.9593 8.17527 14.4077 9.92829 15.2632C10.4517 15.5187 10.5304 14.5962 10.9425 14.0569C11.0629 13.8992 11.1821 13.7255 11.3907 13.6834C11.6467 13.6319 11.866 13.6184 12.1377 13.6055C14.1658 13.5087 17.4209 13.9502 18.1141 13.9502C18.1473 13.9502 18.1141 13.89 18.1141 13.8599C18.1141 11.5408 20.6245 12.8051 21.3377 14.0979C21.3711 14.1585 21.6032 14.6474 21.718 14.5C21.9474 14.2054 22.387 13.9776 22.6823 13.7573C23.5864 13.0829 24.5502 12.4183 25.0185 11.4594C25.4672 10.5408 27.4715 10.2201 27.6219 10.1053C28.0228 9.79935 28.2797 9.34009 28.6858 9.02615C29.1233 8.68795 29.2817 9.57005 29.365 9.80989C30.2421 12.335 29.5931 12.2105 31.6785 10.9301C32.1906 10.6157 35.8391 14.2258 36.3147 14.7955C36.4359 14.9405 36.2877 14.6625 36.3419 14.4344C36.6317 13.2157 37.9875 12.6263 38.2887 11.3815C38.3131 11.281 38.4656 9.92685 38.5876 9.93299C38.9643 9.95196 39.424 11.7589 39.7285 11.3199C40.8168 9.75068 41.6785 8.28347 43.93 10.052C44.0965 10.1827 46.1396 7.37418 46.6737 8.07828C46.8028 8.24839 47.8523 7.07084 48.1271 6.91703C50.2766 5.71376 52.3351 4.23344 53.0757 4.23344C54.914 4.23344 55.6212 9.27412 59.052 4.29909C60.6329 2.0066 60.3677 2.8416 63 1" stroke="#0038FF" stroke-linecap="round"/>
			<defs>
				<linearGradient id="paint0_linear_181_7970" x1="32" y1="1" x2="32" y2="23.8826" gradientUnits="userSpaceOnUse">
					<stop stop-color="#00C2FF" stop-opacity="0.15"/>
					<stop offset="1" stop-color="white" stop-opacity="0"/>
				</linearGradient>
			</defs>
		</svg>
		<button class="w-9 h-9 flex items-center justify-center rounded-full transition-colors duration-200 hover:bg-gray-200 dark:hover:bg-gray-900">
			<svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" viewBox="0 0 4 12" fill="none">
				<path d="M2 4.94131C0.895431 4.94131 0 4.04588 0 2.94131C0 1.83675 0.895431 0.941315 2 0.941315C3.10457 0.941315 4 1.83675 4 2.94131C4 4.04588 3.10457 4.94131 2 4.94131Z" fill="currentColor"/>
				<path d="M2 11.9413C0.895431 11.9413 0 11.0459 0 9.94131C0 8.83675 0.895431 7.94131 2 7.94131C3.10457 7.94131 4 8.83675 4 9.94131C4 11.0459 3.10457 11.9413 2 11.9413Z" fill="currentColor"/>
			</svg>
		</button>
	</header>
	<section class="flex items-center gap-4">
		<div class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-900">
			<svg width="16" height="16" viewBox="0 0 14 17" fill="none">
				<path d="M11.6647 16.2407C10.7601 17.085 9.77242 16.9517 8.82168 16.5518C7.81555 16.1429 6.8925 16.1251 5.83099 16.5518C4.5018 17.1028 3.80028 16.9428 3.00645 16.2407C-1.49804 11.7701 -0.833444 4.96211 4.28026 4.71326C5.52638 4.77547 6.39405 5.37095 7.12326 5.42428C8.21247 5.21097 9.25551 4.59772 10.4186 4.67771C11.8124 4.78436 12.8646 5.31763 13.5569 6.2775C10.677 7.93952 11.3601 11.5924 14 12.6145C13.4739 13.9476 12.7908 15.2719 11.6554 16.2496L11.6647 16.2407ZM7.03096 4.65993C6.8925 2.67796 8.56322 1.04261 10.4832 0.882629C10.7509 3.17567 8.32323 4.88212 7.03096 4.65993Z" fill="white"/>
			</svg>
		</div>
		<div class="flex flex-col">
			<h2 class="font-medium">Apple</h2>
			<span class="block text-gray-500 dark:text-gray-300">Financial Services</span>
		</div>
	</section>
	<section class="flex flex-col w-full gap-1">
		<div class="relative w-full block h-1 rounded-full overflow-hidden bg-gray-200 dark:bg-gray-900">
			<div class="absolute left-0 h-full w-1/2 bg-indigo-600"></div>
		</div>
		<div class="flex items-center w-full text-xs font-medium">
			<span>Progress</span>
			<span class="ml-auto">66%</span>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-start justify-between">
		<h2 class="font-medium text-base">Investments per month</h2>
		<button class="flex-none flex mt-1 items-center justify-center rounded-full text-xs font-medium h-8 gap-2 px-3 border border-gray-300 bg-white dark:bg-gray-950 dark:border-gray-900">
			<span>September</span>
			<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-chevron-down"><polyline points="6 9 12 15 18 9"></polyline></svg>
		</button>
	</header>
	<section class="grid grid-cols-12 gap-4 w-full mt-2">
		<div class="flex flex-col items-start col-span-8 gap-1">
			<div class="flex items-center gap-2">
				<h3 class="font-semibold text-xl">345.00</h3>
				<div class="flex items-center gap-1 justify-center h-6 px-1 rounded-sm font-medium text-xs bg-emerald-100 text-emerald-600">
					<svg width="14" height="14" fill="none" stroke-width="2.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" data-astro-source-file="D:/tailwindcss/widgets-components-v2.1/src/pages/index.astro" data-astro-source-loc="1461:160"> 
						<path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" data-astro-source-file="D:/tailwindcss/widgets-components-v2.1/src/pages/index.astro" data-astro-source-loc="1462:9"></path>
					</svg>
					<span>32.65%</span>
				</div>
			</div>
			<p class="text-xs">Lorem ipsum dolor sit amet consectetur</p>
		</div>
		<div class="w-full h-full col-span-4">
			<svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 121 102" fill="none">
				<path d="M120 101.655H1.32568C1.57605 98.6416 2.07679 92.5594 2.07679 92.3402C2.07679 92.121 5.8323 88.4133 7.71006 86.5868L22.7321 66.3128L30.9943 62.2032L46.1084 57.6335L50.1474 55.3539L59.1701 46.2205L65.9206 42.4772L70.8027 32.0662L80.4419 23.9379L92.384 17.1444L120 1.65527V101.655Z" fill="url(#paint0_linear_95_1308)"/>
				<path d="M119.254 1.927C105.525 11.9238 74.8583 22.0811 68.102 35.7467C67.1947 37.5819 67.4154 41.692 64.9853 42.8369C55.2635 47.4174 51.4935 57.7007 39.8882 59.3908C15.6501 62.9206 17.2236 78.8607 5.37976 87.4849C0.126623 91.31 4.1939 96.6634 1 100.85" stroke="#00BE91" stroke-width="2" stroke-linecap="round"/>
				<defs>
					<linearGradient id="paint0_linear_95_1308" x1="60.6628" y1="1.65527" x2="60.6628" y2="98.6416" gradientUnits="userSpaceOnUse">
						<stop stop-color="#B9FFEE"/>
						<stop offset="1" stop-color="white" stop-opacity="0"/>
					</linearGradient>
				</defs>
			</svg>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside flex items-center flex-row justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-col items-start gap-2">
		<span class="uppercase text-xs font-medium text-gray-600 dark:text-gray-400">CURRENT PRICE</span>
		<div class="flex items-center justify-center gap-2">
			<h2 class="text-sm sm:text-base font-semibold">€45.00</h2>
			<span class="px-2 py-[2px] text-xs rounded-sm bg-[#D1FFD6] text-black">-082%</span>
		</div>
		<p class="text-xs text-gray-500">Update now - 3:23AM</p>
	</header>
	<section class="flex flex-col gap-2 max-w-[7rem]">
		<div class="flex flex-row items-center gap-2">
			<svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
				<path d="M17 17L7.8 7.7M7 17V7h10"></path>
			</svg>
			<span class="font-semibold uppercase text-xs">Upward</span>
		</div>
		<div class="w-full">
			<svg class="w-full" viewBox="0 0 141 34" fill="none" xmlns="http://www.w3.org/2000/svg">
				<g>
					<path d="M5 1.06827C21.6434 0.767281 22.9399 12.3208 34.9648 17.0373C40.1853 19.085 49.7907 6.92438 50.5584 9.19207C52.0191 13.5068 56.5137 13.1684 59.691 15.8304C62.3177 18.031 66.82 17.223 70.2031 17.223C71.4937 17.223 70.5663 21.5846 71.8795 22.3604C76.5857 25.1406 100.925 -1.04184 101.181 7.6911C101.267 10.6171 104.228 14.784 107.729 14.9638C112.327 15.2001 116.088 13.9989 118.887 18.0586C121.415 21.7246 125.071 23.9078 129.941 23.9078C133.089 23.9078 132.858 20.66 136 24.0625" stroke="url(#paint0_linear_228_43)" stroke-width="3" stroke-linecap="round"> </path>
				</g>
				<defs>
					<linearGradient id="paint0_linear_228_43" x1="5" y1="1.0625" x2="139.386" y2="19.4725" gradientUnits="userSpaceOnUse">
						<stop stop-color="#7000FF"></stop>
						<stop offset="1" stop-color="#EA00B6"> </stop>
					</linearGradient>
				</defs>
			</svg>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-row justify-between items-start w-full p-4 gap-4 relative z-[1]">
		<div class="flex flex-col items-start">
			<h2 class="font-bold text-base block mb-1 leading-6">
				Company finances in
				<br />
				the last year
			</h2>
		</div>
		<span class="flex-none text-lg font-semibold block mb-1">76%</span>
	</header>
	<div class="w-full -mt-10 relative">
		<span class="absolute top-[10px] right-[42px] flex h-3 w-3">
			<span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-rose-400 opacity-75"></span>
			<span class="relative inline-flex rounded-full h-3 w-3 border-2 border-white bg-rose-500 dark:border-gray-950"></span>
		</span>
		<svg class="w-full" viewBox="0 0 156 54" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M0 35.2121C1.12193 35.7084 2.05287 36.4465 3.15467 36.9127C3.88018 37.2197 4.96816 37.139 5.33694 37.8731C5.78171 38.7584 6.41334 37.1208 6.84078 36.7427C7.35846 36.2847 8.0534 35.1306 8.75167 35.3022C11.4731 35.971 14.5286 35.7848 17.3224 35.7523C17.6226 35.7488 17.9104 35.5687 17.9104 35.8724C17.9104 35.9323 17.9191 36.0299 17.9164 36.1291C18.3683 35.944 19.053 35.7572 19.1768 35.7523C20.6722 35.6935 21.0695 36.6679 22.2975 37.2528C23.2021 37.6838 23.2021 38.1814 23.2021 37.0128C23.2021 35.6556 24.0027 35.3695 24.8303 34.3118C25.1311 33.9274 25.4288 33.5039 25.9497 33.4015C26.5891 33.2758 27.1368 33.243 27.8154 33.2114C30.881 33.0687 33.9468 32.5976 36.9289 31.971C38.3957 31.6628 39.862 31.3127 41.2934 30.8906C41.6774 30.7773 41.6134 31.478 41.7231 31.7509C41.8505 32.068 42.5107 34.0517 42.7407 34.0517C42.8236 34.0517 42.7407 33.905 42.7407 33.8316V32.8113C42.7407 32.182 42.8631 31.787 43.2608 31.2507C43.6045 30.7875 45.7737 28.5386 46.0989 29.21C46.4428 29.9198 46.4557 30.5161 46.9696 31.1707C47.0957 31.3314 47.2004 31.786 47.2296 31.4108C47.276 30.8159 47.1736 29.3852 47.7271 28.9499C48.1423 28.6234 50.4124 33.7413 50.7913 34.4118C50.8749 34.5597 51.4545 35.7515 51.7411 35.3922C52.3142 34.674 53.4118 34.1187 54.1495 33.5815C55.9224 32.2907 57.4928 30.8434 59.1925 29.4901C59.3229 29.3863 59.8755 29.4777 59.7126 29.4201C59.1512 29.2214 59.8806 28.1863 59.984 27.9796C60.7619 26.4247 61.2675 24.79 61.827 23.1679C62.0575 22.4997 62.6297 21.7287 62.6864 21.0271C62.7081 20.7579 62.5243 19.9876 62.8899 19.9067C63.3145 19.8128 63.0628 18.5414 63.1047 18.2261C63.168 17.7501 63.6596 18.91 63.6814 18.9464C64.3669 20.0893 64.9188 21.2579 65.5358 22.4276C65.6835 22.7077 66.0959 24.9687 66.4856 24.6784C67.4868 23.9325 68.1285 22.8128 69.1427 22.0475C70.2353 21.223 70.6307 23.3734 70.8388 23.9581C71.5045 25.829 73.5756 31.4204 72.908 29.5501C72.6058 28.7035 74.1901 27.2634 74.8528 26.8292C75.0807 26.6798 75.3292 26.7757 75.4973 26.9492C75.9782 27.4456 76.0081 27.0539 76.6167 26.6891C78.3694 25.6387 78.9067 30.3861 79.9749 29.5001C80.2389 29.2812 80.3132 28.7752 80.642 28.6298C81.2229 28.3728 81.9908 29.8405 82.1798 30.1303C82.247 30.2335 82.7905 31.2581 83.0391 31.1207C83.4397 30.8992 83.5218 30.7105 84.0567 30.7105C85.5083 30.7105 85.7936 32.3676 86.2503 33.4115C86.7384 34.527 87.4071 35.1912 88.1951 36.1124C88.4976 36.4661 88.1275 35.7882 88.263 35.2321C88.6731 33.5484 89.9177 32.3477 91.248 31.1707C91.4066 31.0304 91.5497 30.6721 91.7908 30.7906C92.3756 31.078 93.0648 28.0325 93.125 27.7895C93.1857 27.5445 93.5668 24.2433 93.8713 24.2582C94.767 24.3023 95.4483 26.6541 95.7369 27.2093C95.9907 27.6972 96.2507 28.3009 96.7207 27.6394C97.5846 26.4234 97.918 24.7089 99.0047 23.648C99.5343 23.131 99.8986 23.9357 100.181 24.2282C100.638 24.7027 101.234 24.0552 101.651 23.8281C102.818 23.1913 104.902 21.5496 105.947 22.9178C106.347 23.4417 106.663 24.1263 107.214 24.5483C107.776 24.9795 108.692 23.1065 108.91 22.8678C109.743 21.9538 110.916 21.4318 111.85 20.627C112.32 20.2215 112.659 19.7113 113.274 19.4465C113.598 19.307 113.885 19.5045 114.066 19.7366C114.583 20.402 115.569 17.7932 115.75 17.4258C116.429 16.0492 116.594 17.5072 117.695 16.9056C120.594 15.3215 124.628 15.045 127.973 15.045C128.215 15.045 128.078 15.0317 127.973 14.9049C127.701 14.574 128.378 14.0083 128.539 13.7445C128.933 13.0974 129.068 12.261 129.353 11.5737C129.443 11.3559 129.67 10.3633 130.054 10.3633C130.72 10.3633 131.718 12.6542 131.953 13.0443C132.34 13.6843 133.31 15.8144 134.215 16.1054C134.401 16.1653 135.866 11.3414 136.058 10.8135C136.186 10.4619 136.627 9.01776 137.177 8.86279C137.448 8.78656 138.345 10.2279 138.512 10.4233C138.52 10.4328 138.527 10.442 138.535 10.4508C138.494 10.3806 138.458 10.3001 138.444 10.2233C138.347 9.69988 138.842 9.23517 139.326 9.00284C140.226 8.57054 141.178 9.81554 141.723 10.2333C142.357 10.7192 144.434 11.2956 144.979 10.5234C146.128 8.89668 145.725 7.5836 145.725 5.78169C145.725 5.375 146.782 4.62733 147.15 4.46123C148.144 4.01306 148.545 4.7615 149.072 5.44157C149.408 5.87513 150.401 7.75245 151.085 7.86243C151.397 7.91259 150.99 7.29903 151.04 7.02213C151.148 6.42555 151.637 5.97194 152.024 5.5016C152.526 4.88998 152.985 4.08963 153.754 3.70096C154.092 3.52983 154.448 2.74764 154.839 2.48052C155.147 2.27048 155.682 1.93861 155.902 1.58023V1C156.046 1.19134 156.019 1.38954 155.902 1.58023V53.9024H0V35.2121Z" fill="url(#deuwe8dhwe)"/>
			<path d="M0 35.2121C1.12193 35.7084 2.05287 36.4465 3.15467 36.9127C3.88018 37.2197 4.96816 37.139 5.33694 37.8731C5.78171 38.7584 6.41334 37.1208 6.84078 36.7427C7.35846 36.2847 8.0534 35.1306 8.75167 35.3022C11.4731 35.971 14.5286 35.7848 17.3224 35.7523C17.6226 35.7488 17.9104 35.5687 17.9104 35.8724C17.9104 36.0498 17.9868 36.5562 17.6164 36.4626C17.05 36.3194 18.9616 35.7608 19.1768 35.7523C20.6722 35.6935 21.0695 36.6678 22.2975 37.2528C23.2021 37.6838 23.2021 38.1814 23.2021 37.0128C23.2021 35.6556 24.0027 35.3695 24.8303 34.3118C25.1311 33.9274 25.4288 33.5039 25.9497 33.4015C26.5891 33.2758 27.1368 33.243 27.8154 33.2114C30.881 33.0687 33.9468 32.5976 36.9289 31.971C38.3957 31.6628 39.862 31.3127 41.2934 30.8906C41.6774 30.7773 41.6134 31.478 41.7231 31.7509C41.8505 32.068 42.5107 34.0517 42.7407 34.0517C42.8236 34.0517 42.7407 33.905 42.7407 33.8316C42.7407 33.4915 42.7407 33.1514 42.7407 32.8113C42.7407 32.182 42.8631 31.787 43.2608 31.2507C43.6045 30.7875 45.7737 28.5386 46.0989 29.21C46.4428 29.9198 46.4557 30.516 46.9696 31.1707C47.0957 31.3314 47.2004 31.786 47.2296 31.4108C47.276 30.8159 47.1736 29.3852 47.7271 28.9499C48.1423 28.6234 50.4124 33.7413 50.7913 34.4118C50.8749 34.5597 51.4545 35.7515 51.7411 35.3922C52.3142 34.674 53.4118 34.1187 54.1495 33.5815C55.9224 32.2907 57.4928 30.8434 59.1925 29.4901C59.3229 29.3863 59.8755 29.4777 59.7126 29.4201C59.1512 29.2214 59.8806 28.1863 59.984 27.9796C60.7619 26.4247 61.2675 24.79 61.8271 23.1679C62.0575 22.4997 62.6297 21.7287 62.6864 21.0271C62.7081 20.7579 62.5243 19.9876 62.8899 19.9067C63.3145 19.8128 63.0628 18.5414 63.1047 18.2261C63.168 17.7501 63.6596 18.91 63.6814 18.9464C64.3669 20.0893 64.9188 21.2579 65.5358 22.4276C65.6835 22.7077 66.0959 24.9687 66.4856 24.6784C67.4868 23.9325 68.1285 22.8128 69.1427 22.0475C70.2353 21.223 70.6307 23.3734 70.8388 23.9581C71.5045 25.829 73.5756 31.4204 72.908 29.5501C72.0659 27.1911 75.5473 27.33 76.6167 26.6891C78.3694 25.6387 78.9067 30.3861 79.9749 29.5001C80.2389 29.2812 80.3132 28.7752 80.642 28.6298C81.2229 28.3728 81.9908 29.8405 82.1798 30.1303C82.247 30.2335 82.7905 31.2581 83.0391 31.1207C83.4397 30.8992 83.5218 30.7105 84.0567 30.7105C85.5083 30.7105 85.7936 32.3676 86.2503 33.4115C86.7384 34.527 87.4071 35.1911 88.1951 36.1124C88.4976 36.4661 88.1275 35.7882 88.263 35.2321C88.6731 33.5484 89.9177 32.3477 91.248 31.1707C91.4066 31.0304 91.5497 30.6721 91.7908 30.7906C92.3756 31.078 93.0648 28.0325 93.125 27.7895C93.1857 27.5445 93.5668 24.2433 93.8713 24.2582C94.767 24.3023 95.4483 26.6541 95.7369 27.2093C95.9907 27.6972 96.2507 28.3009 96.7207 27.6394C97.5846 26.4234 97.918 24.7089 99.0047 23.648C99.0383 23.6152 105.641 22.5174 105.947 22.9178C106.347 23.4416 106.663 24.1263 107.214 24.5483C107.776 24.9795 108.692 23.1065 108.91 22.8677C109.743 21.9538 110.916 21.4318 111.85 20.627C112.32 20.2215 112.659 19.7113 113.274 19.4465C113.598 19.307 113.885 19.5045 114.066 19.7366C114.583 20.402 115.569 17.7932 115.75 17.4258C116.429 16.0492 116.594 17.5072 117.695 16.9056C120.594 15.3215 124.628 15.045 127.973 15.045C128.215 15.045 128.078 15.0317 127.973 14.9049C127.701 14.574 128.378 14.0083 128.539 13.7445C128.933 13.0974 129.068 12.261 129.353 11.5737C129.443 11.3559 129.67 10.3633 130.054 10.3633C130.72 10.3633 131.718 12.6542 131.953 13.0443C132.34 13.6843 133.31 15.8144 134.215 16.1054C134.401 16.1653 135.866 11.3414 136.058 10.8135C136.186 10.4619 136.627 9.01776 137.177 8.86279C137.448 8.78656 138.345 10.2279 138.512 10.4233C138.918 10.8994 138.501 10.5322 138.444 10.2233C138.347 9.69988 138.842 9.23517 139.326 9.00284C140.226 8.57054 141.178 9.81554 141.723 10.2333C142.357 10.7192 144.434 11.2956 144.979 10.5234C146.128 8.89668 145.725 7.5836 145.725 5.78169C145.725 5.375 146.782 4.62733 147.15 4.46123C148.144 4.01306 148.545 4.76149 149.072 5.44157C149.408 5.87513 150.401 7.75245 151.085 7.86243C151.397 7.91259 150.99 7.29903 151.04 7.02213C151.148 6.42555 151.637 5.97194 152.024 5.5016C152.526 4.88998 152.985 4.08963 153.754 3.70096C154.092 3.52983 154.448 2.74764 154.839 2.48052C155.31 2.15871 156.317 1.55092 155.902 1" stroke="url(#9845t43mcf)" stroke-linecap="round"/>
			<defs>
				<linearGradient id="deuwe8dhwe" x1="78" y1="-5.9092" x2="78" y2="53.9024" gradientUnits="userSpaceOnUse">
					<stop offset="0.144057" stop-color="#D60F63" stop-opacity="0.22"/>
					<stop offset="0.983952" stop-color="white" stop-opacity="0"/>
				</linearGradient>
				<linearGradient id="9845t43mcf" x1="153.629" y1="4.07508" x2="9.25031" y2="54.8124" gradientUnits="userSpaceOnUse">
					<stop offset="0.161546" stop-color="#D60F27"/>
					<stop offset="1" stop-color="#EA0FBA"/>
				</linearGradient>
			</defs>
		</svg>
	</div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 flex flex-col gap-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-start justify-between">
		<div class="flex flex-col gap-1">
			<h2 class="font-medium text-base">Header</h2>
			<p>The best solution for your online payments</p>
		</div>
		<button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
			<svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
			</svg>
		</button>
	</header>
	<section class="flex items-center justify-between">
		<svg class="w-full max-w-[7rem]" viewBox="0 0 88 16" fill="none" xmlns="http://www.w3.org/2000/svg">
			<path d="M82.9613 6.40709L84.8427 10.9549H84.8648L86.7017 6.40692H88L84.0397 15.5359H82.8077L84.2818 12.3424L81.6745 6.40692L82.9613 6.40709ZM78.693 6.19788C79.573 6.19788 80.2658 6.42911 80.772 6.90257C81.2782 7.37621 81.5312 8.01483 81.5312 8.84081V12.75H80.3978V11.8691H80.3431C79.8481 12.5958 79.1988 12.9592 78.3845 12.9592C77.6916 12.9592 77.1085 12.75 76.6356 12.3426C76.1623 11.9242 75.9313 11.4067 75.9313 10.7899C75.9313 10.1401 76.1735 9.61156 76.6796 9.22601C77.1746 8.84064 77.8346 8.64244 78.6596 8.64244C79.3636 8.64244 79.9468 8.77474 80.409 9.02782V8.75255C80.409 8.33414 80.244 7.99281 79.914 7.69552C79.584 7.40907 79.1988 7.26593 78.7588 7.26593C78.0988 7.26593 77.5708 7.5412 77.1855 8.10292L76.1405 7.44227C76.7125 6.61629 77.571 6.19788 78.693 6.19788ZM72.686 3.47788C73.4891 3.47788 74.1713 3.74214 74.7321 4.28184C75.3041 4.82137 75.5793 5.471 75.5793 6.23092C75.5793 7.01268 75.2931 7.6735 74.7321 8.191C74.1819 8.71969 73.5001 8.98395 72.686 8.98395H70.7278V12.739H69.5394V3.47788H72.686ZM78.8468 9.57853C78.3628 9.57853 77.9668 9.69965 77.6365 9.93087C77.3175 10.1731 77.1525 10.4596 77.1525 10.8009C77.1525 11.1092 77.2845 11.3735 77.5485 11.5716C77.8125 11.781 78.1205 11.8801 78.4725 11.8801C78.9676 11.8801 79.4188 11.6929 79.8148 11.3296C80.2108 10.955 80.3978 10.5256 80.3978 10.019C80.024 9.72167 79.5068 9.57853 78.8468 9.57853ZM72.7186 4.63401H70.7276V7.86068H72.7186C73.192 7.86068 73.588 7.70653 73.896 7.38722C74.2151 7.06791 74.3689 6.69337 74.3689 6.25294C74.3689 5.82352 74.2151 5.44898 73.896 5.12967C73.588 4.79935 73.192 4.63401 72.7186 4.63401ZM52.7512 6.2089C53.5542 6.2089 54.1925 6.56124 54.5227 6.95763H54.5774V6.40709H55.9857V12.4637C55.9857 14.9525 54.5227 15.9766 52.7845 15.9766C51.156 15.9766 50.177 14.8754 49.8029 13.9833L51.0902 13.4438C51.321 13.9944 51.8822 14.6442 52.7845 14.6442C53.8955 14.6442 54.5774 13.9503 54.5774 12.6619V12.1774H54.5227C54.1925 12.5848 53.5542 12.9482 52.7512 12.9482C51.068 12.9482 49.528 11.4836 49.528 9.58954C49.528 7.68451 51.068 6.2089 52.7512 6.2089ZM62.4328 6.21991C64.1821 6.21991 65.0291 7.60743 65.3151 8.36718L65.4691 8.75255L60.9696 10.6137C61.3106 11.2855 61.8496 11.6379 62.5976 11.6379C63.3461 11.6159 63.8741 11.2525 64.2589 10.6908L65.4029 11.4615C65.0291 12.0123 64.1379 12.9593 62.5976 12.9593C60.6834 12.9593 59.2644 11.4837 59.2644 9.58954C59.2644 7.58524 60.7056 6.21991 62.4328 6.21991ZM29.4953 2.48692C31.0903 2.48692 32.2235 3.11453 33.0707 3.9295L32.0585 4.94249C31.4425 4.36993 30.6173 3.91849 29.4842 3.91849C27.383 3.91849 25.7328 5.61431 25.7328 7.71771C25.7328 9.82094 27.372 11.5168 29.4842 11.5168C30.8483 11.5168 31.6295 10.9662 32.1245 10.4707C32.5317 10.0632 32.7957 9.47961 32.9057 8.67565H29.4513V7.24425H34.2918C34.3468 7.49733 34.3688 7.8058 34.3688 8.13612C34.3688 9.20434 34.0718 10.5366 33.1365 11.4837C32.2125 12.4418 31.0465 12.9483 29.4953 12.9483C26.613 12.9483 24.1926 10.6027 24.1926 7.71771C24.1926 4.83255 26.6128 2.48692 29.4953 2.48692ZM38.2417 6.2089C40.101 6.2089 41.619 7.62945 41.619 9.57853C41.619 11.5168 40.101 12.9482 38.2417 12.9482C36.3825 12.9482 34.8644 11.5168 34.8644 9.57853C34.8644 7.62928 36.3825 6.2089 38.2417 6.2089ZM45.5902 6.2089C47.4494 6.2089 48.9676 7.62945 48.9676 9.57853C48.9676 11.5168 47.4494 12.9482 45.5902 12.9482C43.7309 12.9482 42.2125 11.5168 42.2125 9.57853C42.2125 7.62928 43.7309 6.2089 45.5902 6.2089ZM58.5274 2.83926V12.7391H57.0532V2.83926H58.5274ZM38.2527 7.5412C37.2407 7.5412 36.3604 8.36718 36.3604 9.57853C36.3604 10.7789 37.2407 11.6159 38.2527 11.6159C39.2649 11.6159 40.145 10.7789 40.145 9.57853C40.145 8.36735 39.2649 7.5412 38.2527 7.5412ZM45.5902 7.5412C44.5779 7.5412 43.6979 8.36718 43.6979 9.57853C43.6979 10.7789 44.5779 11.6159 45.5902 11.6159C46.6022 11.6159 47.4822 10.7789 47.4822 9.57853C47.4822 8.36735 46.6022 7.5412 45.5902 7.5412ZM52.8942 7.53036C51.8712 7.53036 51.0242 8.40021 51.0242 9.58971C51.0242 10.7679 51.8822 11.6159 52.8942 11.6159C53.8955 11.6159 54.6876 10.7679 54.6876 9.58954C54.6876 8.40021 53.8955 7.53036 52.8942 7.53036ZM62.4768 7.50834C61.7288 7.50834 60.6834 8.17999 60.7274 9.47943L63.7309 8.22404C63.5659 7.80563 63.0709 7.50834 62.4768 7.50834Z" class="fill-gray-600 dark:fill-gray-400"></path><path d="M16.3905 2.99892C14.6104 1.97044 12.3343 2.58154 11.3058 4.36322L8.71272 8.85956C7.96248 10.1578 8.92842 10.6115 10.0054 11.2578L12.5005 12.6996C13.3454 13.1873 14.4246 12.8976 14.9119 12.053L17.5777 7.43229C18.4732 5.87961 17.9417 3.89543 16.3905 2.99892Z" fill="#EA4335"></path><path d="M13.4565 4.85991L10.9615 3.41836C9.58412 2.65311 8.80415 2.60236 8.23868 3.50214L4.55884 9.88132C3.53103 11.662 4.1429 13.9391 5.92181 14.9655C7.47298 15.8619 9.45539 15.3299 10.351 13.7772L14.1013 7.2747C14.5908 6.42894 14.3014 5.34765 13.4565 4.85991Z" fill="#FBBC04"></path><path d="M12.1842 0.567262C10.2458 -0.552394 7.76723 0.111692 6.6485 2.05217L3.31172 7.83625C2.81878 8.68958 3.11148 9.78206 3.96415 10.2744L5.92679 11.4086C6.896 11.9692 8.1347 11.6365 8.69467 10.6664L12.5067 4.05819C13.2965 2.68924 15.0446 2.22008 16.412 3.01079L12.1842 0.567262Z" fill="#34A853"></path><path d="M7.12253 3.70687L5.22795 2.6144C4.38301 2.12786 3.30381 2.41621 2.81654 3.25973L0.543667 7.19109C-0.575239 9.12606 0.0881985 11.6014 2.02643 12.7183L5.97698 14.9955C4.62948 14.0926 4.20151 12.2832 5.02548 10.8584L7.76929 6.11324C8.25535 5.27195 7.96643 4.19358 7.12253 3.70687Z" fill="#4285F4"></path>
		</svg>
		<button class="flex items-center justify-center cursor-pointer rounded-md h-7 px-3 text-sm bg-purple-600 text-white">Button</button>
	</section>
</article>

<article class="border shadow-sm break-inside relative rounded-xl overflow-hidden p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-row items-center justify-between pb-2 relative">
		<h3 class="tracking-tight text-lg font-medium">
			Total Revenue
		</h3>
		<div class="flex flex-none items-center justify-center w-9 h-9 rounded-full bg-gray-100 dark:bg-gray-900">
			<svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M14.121 7.629A3 3 0 0 0 9.017 9.43c-.023.212-.002.425.028.636l.506 3.541a4.5 4.5 0 0 1-.43 2.65L9 16.5l1.539-.513a2.25 2.25 0 0 1 1.422 0l.655.218a2.25 2.25 0 0 0 1.718-.122L15 15.75M8.25 12H12m9 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"></path>
			</svg>
		</div>
	</header>
	<section class="pt-0 relative">
		<div class="text-xl font-semibold">€ 45,231.89</div>
		<p class="text-xs dark:text-gray-500">+20.1% from last month</p>
	</section>
	<div class="absolute z-0 bottom-0 right-0 bg-green-500/60 blur-2xl w-12 h-12 rounded-full"></div>
	<div class="absolute z-0 top-0 left-1/2 bg-yellow-500/20 blur-2xl w-12 h-12 rounded-full"></div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-row items-center justify-between pb-2">
		<h3 class="tracking-tight text-lg font-medium">
			Subscriptions
		</h3>
		<div class="flex flex-none items-center justify-center w-9 h-9 rounded-full bg-gray-100 dark:bg-gray-900">
			<svg width="20" height="20"  fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z"></path>
			</svg>
		</div>
	</header>
	<section class="pt-0">
		<div class="text-xl font-semibold">+2350</div>
		<p class="text-xs">+180.1% from last month</p>
	</section>
</article>

<section class="grid grid-cols-2 gap-4">
	<article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 pb-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
		<header class="p-4">
			<svg width="26" height="26" viewBox="0 0 512 512"><path d="M427.68 351.43C402 320 383.87 304 383.87 217.35 383.87 138 343.35 109.73 310 96c-4.43-1.82-8.6-6-9.95-10.55C294.2 65.54 277.8 48 256 48s-38.21 17.55-44 37.47c-1.35 4.6-5.52 8.71-9.95 10.53-33.39 13.75-73.87 41.92-73.87 121.35C128.13 304 110 320 84.32 351.43 73.68 364.45 83 384 101.61 384h308.88c18.51 0 27.77-19.61 17.19-32.57zM320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
		</header>
		<section class="w-full">
			<svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 104 37" fill="none">
				<path d="M0 36.3915C0.40204 34.0778 1.20938 32.0455 2.34461 29.9385C4.31728 26.2773 6.63549 22.7442 9.9798 19.9879C10.5469 19.5205 12.0783 17.8938 12.8953 18.8267C14.3823 20.5245 14.9217 22.9638 15.9555 24.8902C16.1632 25.2772 16.2314 26.0247 16.7015 25.9889C17.0312 25.9638 16.9398 25.425 17.0517 25.1406C17.7023 23.4872 18.8784 21.8761 20.4316 20.8154C21.3713 20.1737 23.6095 18.6313 24.8011 19.4803C26.1776 20.4611 26.5379 22.0758 27.0543 23.4995C27.2977 24.1703 27.667 24.8154 27.9526 25.4743C28.1725 25.9819 28.2798 26.061 28.6757 25.5717C29.9778 23.9625 32.2544 22.4348 34.2251 24.1532C34.7776 24.6349 35.124 25.1271 35.8999 24.6816C36.6692 24.2399 36.7695 24.5721 37.1026 25.3005C37.4754 26.1157 37.9436 28.5056 39.1351 27.2892C39.3024 27.1184 40.6559 25.4702 40.9545 25.6134C41.7307 25.9857 42.1579 27.4117 42.4465 28.0889C42.6063 28.4639 43.1287 30.2269 43.6492 30.3627C43.6849 30.372 44.8737 26.3764 45.2174 25.9055C45.6749 25.2786 46.2036 24.6839 46.7094 24.0906C46.8646 23.9086 47.5699 22.8837 47.9578 22.7763C48.0197 22.7592 48.1192 22.9913 48.171 23.0128C48.3133 23.0718 48.3717 22.7863 48.4222 22.6512C48.6074 22.1558 48.9745 20.9378 49.0921 20.5581C49.8692 18.0492 50.6308 15.5787 52.137 13.3403C52.9069 12.1963 54.1546 10.8636 55.6463 10.4685C56.8381 10.1528 58.0717 11.8345 58.5695 12.5685C59.1769 13.464 59.7181 14.5816 60.503 15.3638C61.3219 16.1799 61.3191 17.7563 61.8884 18.7293C61.9637 18.858 62.857 19.9045 62.8933 19.6611C63.043 18.6585 63.4647 17.8133 64.4005 17.2204C65.6881 16.4047 66.0358 17.932 66.6842 18.7711C67.4593 19.7741 67.6806 19.2262 68.5645 18.4582C68.8541 18.2066 70.8095 16.2069 71.1984 16.9631C71.9362 18.3981 71.6449 20.232 72.5153 21.6081C72.6815 21.8709 72.8789 22.2271 73.0786 22.4704C73.183 22.5975 73.17 22.0206 73.17 21.9419C73.17 21.5469 73.5128 22.2681 73.5277 22.2965C73.8279 22.8687 74.1291 23.468 74.1291 24.1114C74.1291 24.2416 74.0618 23.8166 74.1596 23.722C74.6967 23.2025 76.281 25.408 76.4281 25.7386C76.6607 26.2618 77.1315 27.5949 77.9353 27.6439C78.287 27.6653 78.6289 26.4682 78.6661 26.3783C79.3545 24.7144 79.8884 23.0098 80.5235 21.33C81.1338 19.7157 81.962 18.3288 82.9138 16.8797C83.2884 16.3093 83.3616 17.238 83.4466 17.5542C83.5292 17.8612 83.6941 18.9054 83.9491 18.0827C84.8041 15.3231 85.4135 12.509 86.1871 9.7314C86.3437 9.16898 86.5228 8.60962 86.7123 8.05558C86.8257 7.7242 87.0244 8.19833 87.1158 8.35459C88.362 10.4857 88.9987 12.8588 90.2369 14.9953C90.6904 15.7778 90.5521 15.5102 90.6632 14.7728C90.9066 13.1557 91.1757 11.3722 91.7746 9.82875C92.0507 9.117 92.7398 10.7929 92.7946 10.8996C93.2567 11.7997 93.6836 12.7121 94.1801 13.5976C94.257 13.7348 94.9343 15.2033 95.2762 15.2317C95.3066 15.2342 95.942 12.8299 95.9994 12.6658C96.4751 11.3063 97.2595 10.4051 98.0928 9.24465C98.2413 9.03789 98.3713 8.63097 98.6105 8.47975C98.948 8.26628 99.1671 8.2511 99.3793 7.89565C99.5709 7.57484 101.637 3.91144 101.975 4.00164C102.218 4.06626 102.158 4.19283 102.249 4.34932C102.347 4.51769 102.683 4.57546 102.835 4.72481C103.389 5.26987 104 5.37877 104 6.22679" stroke="#6E0BED" stroke-linecap="round"/>
				<path d="M0 36.3915C0.40204 34.0778 1.20938 32.0455 2.34461 29.9385C4.31728 26.2773 6.63549 22.7442 9.9798 19.9879C10.5469 19.5205 12.0783 17.8938 12.8953 18.8267C14.3823 20.5245 14.9217 22.9638 15.9555 24.8902C16.1632 25.2772 16.2314 26.0247 16.7015 25.9889C17.0312 25.9638 16.9398 25.425 17.0517 25.1406C17.7023 23.4873 18.8784 21.8761 20.4316 20.8154C21.3713 20.1737 23.6095 18.6313 24.8011 19.4803C26.1776 20.4611 26.5379 22.0758 27.0543 23.4995C27.2977 24.1703 27.667 24.8154 27.9526 25.4743C28.1725 25.9819 28.2798 26.061 28.6757 25.5717C29.9778 23.9625 32.2544 22.4348 34.2251 24.1532C34.7776 24.6349 35.124 25.1271 35.8999 24.6816C36.6692 24.2399 36.7695 24.5721 37.1026 25.3005C37.4754 26.1157 37.9436 28.5057 39.1351 27.2892C39.3024 27.1184 40.6559 25.4702 40.9545 25.6134C41.7307 25.9857 42.1579 27.4117 42.4465 28.0889C42.6063 28.4639 43.1287 30.2269 43.6492 30.3627C43.6849 30.372 44.8737 26.3764 45.2174 25.9055C45.6749 25.2786 46.2036 24.6839 46.7094 24.0906C46.8646 23.9086 47.5699 22.8837 47.9578 22.7763C48.0197 22.7592 48.1192 22.9913 48.171 23.0128C48.3133 23.0718 48.3717 22.7863 48.4222 22.6512C48.6074 22.1558 48.9745 20.9378 49.0921 20.5581C49.8692 18.0492 50.6308 15.5787 52.137 13.3403C52.9069 12.1963 54.1546 10.8636 55.6463 10.4685C56.8381 10.1528 58.0717 11.8345 58.5695 12.5685C59.1769 13.464 59.7181 14.5816 60.503 15.3638C61.3219 16.1799 61.3191 17.7563 61.8884 18.7294C61.9637 18.858 62.8569 19.9045 62.8933 19.6611C63.0429 18.6585 63.4647 17.8133 64.4005 17.2204C65.6881 16.4047 66.0358 17.932 66.6842 18.7711C67.4593 19.7741 67.6806 19.2262 68.5645 18.4582C68.8541 18.2066 70.8095 16.2069 71.1984 16.9631C71.9362 18.3981 71.6449 20.232 72.5153 21.6081C72.6815 21.8709 72.8789 22.2271 73.0786 22.4704C73.183 22.5975 73.17 22.0206 73.17 21.9419C73.17 21.5469 73.5128 22.2681 73.5277 22.2965C73.8279 22.8687 74.1291 23.468 74.1291 24.1114C74.1291 24.2416 74.0617 23.8166 74.1596 23.722C74.6967 23.2025 76.281 25.408 76.4281 25.7386C76.6607 26.2618 77.1315 27.5949 77.9353 27.6439C78.287 27.6653 78.6289 26.4682 78.6661 26.3783C79.3545 24.7144 79.8884 23.0098 80.5235 21.33C81.1338 19.7157 81.9619 18.3288 82.9138 16.8797C83.2884 16.3093 83.3616 17.238 83.4466 17.5542C83.5292 17.8612 83.6941 18.9054 83.9491 18.0827C84.8041 15.3231 85.4135 12.509 86.1871 9.7314C86.3437 9.16898 86.5228 8.60962 86.7123 8.05558C86.8257 7.7242 87.0244 8.19833 87.1158 8.35459C88.362 10.4857 88.9987 12.8588 90.2369 14.9953C90.6904 15.7778 90.5521 15.5102 90.6632 14.7728C90.9066 13.1557 91.1757 11.3722 91.7746 9.82875C92.0507 9.117 92.7398 10.7929 92.7946 10.8996C93.2566 11.7997 93.6836 12.7121 94.1801 13.5976C94.257 13.7348 94.9343 15.2033 95.2762 15.2317C95.3066 15.2342 95.942 12.8299 95.9994 12.6658C96.4751 11.3063 97.2595 10.4051 98.0928 9.24465C98.2413 9.03789 98.3713 8.63097 98.6105 8.47975C98.948 8.26628 99.167 8.2511 99.3793 7.89565C99.5709 7.57484 101.637 3.91144 101.975 4.00164C102.218 4.06626 102.158 4.19283 102.249 4.34932C102.347 4.51769 102.683 4.57546 102.835 4.72481C103.389 5.26987 104 5.37877 104 6.22679" stroke="url(#paint0_linear_184_7810)" stroke-opacity="0.21" stroke-width="7" stroke-linecap="round"/>
				<defs>
					<linearGradient id="paint0_linear_184_7810" x1="106.815" y1="3.84823" x2="2.13301" y2="41.9212" gradientUnits="userSpaceOnUse">
						<stop stop-color="white" stop-opacity="0.31"/>
						<stop offset="0.381048" stop-color="#970AEE"/>
						<stop offset="0.76813" stop-color="#6AE9C3"/>
						<stop offset="1" stop-color="white" stop-opacity="0"/>
					</linearGradient>
				</defs>
			</svg>
		</section>
	</article>
	<article class="border shadow-sm break-inside flex items-start flex-col justify-between rounded-xl gap-2 pb-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
		<header class="p-4">
			<svg width="26" height="26" viewBox="0 0 512 512"><path d="M427.68 351.43C402 320 383.87 304 383.87 217.35 383.87 138 343.35 109.73 310 96c-4.43-1.82-8.6-6-9.95-10.55C294.2 65.54 277.8 48 256 48s-38.21 17.55-44 37.47c-1.35 4.6-5.52 8.71-9.95 10.53-33.39 13.75-73.87 41.92-73.87 121.35C128.13 304 110 320 84.32 351.43 73.68 364.45 83 384 101.61 384h308.88c18.51 0 27.77-19.61 17.19-32.57zM320 384v16a64 64 0 01-128 0v-16" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
		</header>
		<section class="w-full">
			<svg xmlns="http://www.w3.org/2000/svg" class="w-full" viewBox="0 0 96 36" fill="none">
				<path d="M96 1.94572C88.6165 -2.89 84.5392 12.3925 78.2605 12.3925C71.1686 12.3925 63.7091 6.04792 57.5672 8.03967C48.7597 10.8959 44.5128 21.6062 34.1005 20.1953C23.4441 18.7513 10.3968 21.6247 0 24V36H96V1.94572Z" fill="url(#paint0_linear_181_7869)"/>
				<path d="M0 24C10.3968 21.6247 23.4441 18.7513 34.1005 20.1953C44.5128 21.6062 48.7597 10.8959 57.5672 8.03967C63.709 6.04792 71.1686 12.3925 78.2605 12.3925C84.5392 12.3925 88.6165 -2.89 96 1.94572" stroke="#10C643" stroke-linecap="round"/>
				<defs>
					<linearGradient id="paint0_linear_181_7869" x1="48" y1="1" x2="48" y2="36" gradientUnits="userSpaceOnUse">
						<stop stop-color="#16FF73" stop-opacity="0.43"/>
						<stop offset="1" stop-color="#D9D9D9" stop-opacity="0"/>
					</linearGradient>
				</defs>
			</svg>
		</section>
	</article>
</section>

<article class="border shadow-sm break-inside rounded-xl divide-y dark:divide-gray-900 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-row items-center justify-between p-4">
		<div class="flex flex-col">
			<h3 class="tracking-tight text-xl font-medium">
				Sales
			</h3>
			<p class="text-xs dark:text-gray-400">+19% from last month</p>
		</div>
		<div class="flex flex-none items-center justify-center w-9 h-9 rounded-full bg-gray-100 dark:bg-gray-900">
			<svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M2.25 8.25h19.5M2.25 9h19.5m-16.5 5.25h6m-6 2.25h3m-3.75 3h15a2.25 2.25 0 0 0 2.25-2.25V6.75A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25v10.5A2.25 2.25 0 0 0 4.5 19.5Z"></path>
			</svg>
		</div>
	</header>
	<section class="p-4">
		<div class="flex items-center gap-2">
			<h3 class="font-semibold text-xl">12,234</h3>
			<div class="flex items-center gap-1 justify-center h-6 px-2 rounded-sm font-medium text-xs bg-emerald-100 text-emerald-600 dark:bg-emerald-500/20 dark:text-emerald-400">
				<svg width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" data-astro-source-file="D:/tailwindcss/widgets-components-v2.1/src/pages/index.astro" data-astro-source-loc="1461:160"> 
					<path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" ></path>
				</svg>
				<span>32.65%</span>
			</div>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <header class="flex items-start justify-between">
    <div class="flex flex-col gap-1">
      <div class="flex items-center gap-2">
        <h2 class="font-medium text-lg leading-6">New reports</h2>
        <span class="text-xs text-gray-400">3 min ago</span>
      </div>
    </div>
    <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-gray-100 dark:hover:bg-gray-900">
      <svg width="30" height="30" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
      </svg>
    </button>
  </header>
  <section class="w-full h-24 grid grid-cols-12 grid-rows-1 gap-1 ">
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[33%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Jan</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[58%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Feb</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[68%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Mar</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[50%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Apr</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[25%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">May</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[40%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Jun</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-full  bg-blue-700 dark:bg-blue-700"></div>
      <span class="text-[10px] font-medium">Jul</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[81%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Aug</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[33%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Sep</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[33%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Oct</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[33%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Nov</span>
    </div>
    <div class="flex flex-col w-full gap-2 h-full justify-end">
      <div class="rounded-md w-full h-[33%] bg-gray-200 dark:bg-gray-800"></div>
      <span class="text-[10px]">Dec</span>
    </div>
  <section>
</article>

<article class="border shadow-sm break-inside rounded-xl divide-y dark:divide-gray-900 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex flex-row items-center justify-between p-4">
		<div class="flex flex-col">
			<h3 class="tracking-tight text-xl font-medium">
				Active now
			</h3>
			<p class="text-xs dark:text-gray-400">+19% from last month</p>
		</div>
		<div class="flex flex-none items-center justify-center w-9 h-9 rounded-full bg-gray-100 dark:bg-gray-900">
			<svg width="24" height="24" fill="none" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5m.75-9 3-3 2.148 2.148A12.061 12.061 0 0 1 16.5 7.605"></path>
			</svg>
		</div>
	</header>
	<section class="p-4">
		<div class="flex items-center gap-2">
			<h3 class="font-semibold text-xl">573</h3>
			<div class="flex items-center gap-1 justify-center h-6 px-2 rounded-sm font-medium text-xs bg-emerald-100 text-emerald-600 dark:bg-emerald-500/20 dark:text-emerald-400">
				<svg width="14" height="14" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" data-astro-source-file="D:/tailwindcss/widgets-components-v2.1/src/pages/index.astro" data-astro-source-loc="1461:160"> 
					<path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" ></path>
				</svg>
				<span>32.65%</span>
			</div>
		</div>
	</section>
</article>

<article class="shadow-sm break-inside overflow-hidden relative flex items-center justify-between gap-2 rounded-xl text-sm mb-3 p-1 bg-green-100 dark:text-white dark:bg-green-600/20" data-filter="finance">
  <div class="flex items-center w-full border-2 border-dashed border-green-400 dark:border-green-300 rounded-xl p-3 dark:border-green-600/20">
    <header class="flex items-center w-full gap-2 flex-1">
      <div class="relative flex items-center justify-center rounded-full w-9 h-9 text-lg font-bold bg-emerald-500 text-white ">
        <span>B</span>
        <div class="absolute flex items-center justify-center w-4 h-4 text-black bg-white rounded-full -bottom-1 -right-1 shadow">
          <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
        </div>
      </div>
      <h3 class="text-base font-medium">Princiapl &middot; EUR</h3>
    </header>
    <span class="font-bold">22,08 &euro;</span>
  </div>
</article>

<article class="border shadow-sm break-inside rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-start justify-between">
		<div class="flex flex-col gap-1">
			<p class="text-xs uppercase text-gray-400 dark:text-gray-600">Total Revenue</p>
			<h2 class="text-2xl font-semibold">€151.89</h2>
			<p class="text-xs dark:text-gray-400">+20.1% from last month</p>
		</div>
		<div class="flex justify-center items-center rounded-md px-2 py-1 bg-cyan-100 gap-1 font-medium dark:bg-cyan-500/20">
			<span class="text-xs font-medium text-cyan-700 dark:text-cyan-200">23%</span>
			<svg width="14" height="14" viewBox="0 0 15 8" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M1.57835 7.65466H14.1787C14.3063 7.6544 14.4313 7.6309 14.5404 7.5867C14.6495 7.5425 14.7384 7.47927 14.7977 7.40382C14.8569 7.32837 14.8842 7.24356 14.8767 7.15851C14.8692 7.07346 14.827 6.9914 14.7548 6.92115L8.45465 0.84365C8.19354 0.591667 7.56492 0.591667 7.30311 0.84365L1.00293 6.92115C0.93001 6.99125 0.887245 7.07336 0.879287 7.15855C0.871328 7.24374 0.898481 7.32876 0.957793 7.40437C1.01711 7.47997 1.10631 7.54328 1.21572 7.58741C1.32512 7.63154 1.45054 7.6548 1.57835 7.65466Z" fill="currentColor" class="fill-cyan-500 dark:fill-cyan-400"></path>
			</svg>
		</div>
	</header>
	<section class="-mt-4">
		<div class="w-full">
			<svg class="recharts-surface" class="w-full" viewBox="0 0 303 80">
				<defs>
					<clipPath id="recharts5-clip">
						<rect x="10" y="5" height="75" width="283"></rect>
					</clipPath>
				</defs>
				<g class="recharts-layer recharts-line">
					<path stroke-width="2" fill="none" width="283" height="75" class="stroke-black dark:stroke-white" stroke-dasharray="306.34661865234375px 0px" d="M10,52.143C23.476,46.779,36.952,41.415,50.429,41.415C63.905,41.415,77.381,52.679,90.857,54.821C104.333,56.964,117.81,56.964,131.286,58.036C144.762,59.107,158.238,61.25,171.714,61.25C185.19,61.25,198.667,56.18,212.143,54.286C225.619,52.391,239.095,52.818,252.571,49.882C266.048,46.946,279.524,28.016,293,9.085"></path>
					<g class="recharts-layer"></g>
					<g class="recharts-layer recharts-line-dots" role="img">
						<circle r="4" stroke-width="2" width="283" height="75" cx="10" cy="52.14285714285714" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="50.42857142857143" cy="41.41517857142857" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="90.85714285714286" cy="54.821428571428584" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="131.28571428571428" cy="58.035714285714285" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="171.71428571428572" cy="61.25" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="212.14285714285717" cy="54.285714285714285" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="252.57142857142858" cy="49.88214285714285" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
						<circle r="4" stroke-width="2" width="283" height="75" cx="293" cy="9.08482142857143" class="stroke-black dark:stroke-white fill-white dark:fill-gray-950"></circle>
					</g>
				</g>
			</svg>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside flex items-center flex-col justify-between rounded-xl p-4 gap-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center justify-between w-full">
		<div class="flex items-center justify-start gap-2">
			<div class="flex items-center justify-center w-10 h-10 rounded-full bg-violet-200">
				<svg width="22" height="22" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
					<path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 0 0 6 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0 1 18 16.5h-2.25m-7.5 0h7.5m-7.5 0-1 3m8.5-3 1 3m0 0 .5 1.5m-.5-1.5h-9.5m0 0-.5 1.5m.75-9 3-3 2.148 2.148A12.061 12.061 0 0 1 16.5 7.605"></path>
				</svg>
			</div>
			<h2 class="text-base font-medium block">Balance</h2>
		</div>
		<button class="h-8 px-2 rounded-full flex items-center justify-center border dark:border-gray-900">
			<svg width="24" height="24" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
				<path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5"></path>
			</svg>
		</button>
	</header>
	<section class="grid grid-cols-12 gap-4 items-start w-full">
		<div class="flex flex-col col-span-8 gap-3">
			<div class="flex items-center gap-2">
				<h2 class="font-semibold text-lg">345.00</h2>
				<div class="flex items-center gap-1 justify-center h-6 px-1 rounded-md font-medium text-xs bg-indigo-200 text-indigo-600">
					<svg width="16" height="16" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
						<path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25"></path>
					</svg>
					<span>32.65%</span>
				</div>
			</div>
			<p class="text-sm">Lorem ipsum dolor sit amet consectetur</p>
		</div>
		<div class="w-full col-span-4">
			<svg class="w-full" viewBox="0 0 66 55" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M65 54H2.1026C2.2353 52.4027 2.50068 49.1792 2.50068 49.063C2.50068 48.9468 4.49111 46.9817 5.48632 46.0137L13.448 35.2685L17.8269 33.0904L25.8375 30.6685L27.9781 29.4603L32.7601 24.6196L36.3379 22.6356L38.9254 17.1178L44.0342 12.8098L50.3635 9.20924L65 1V54Z" fill="url(#paint0_linear_193_8249)"/>
				<path d="M64.6044 1.14398C57.328 6.4423 41.0749 11.8256 37.4941 19.0684C37.0132 20.0411 37.1301 22.2194 35.8422 22.8263C30.6897 25.2539 28.6915 30.704 22.5407 31.5998C9.69457 33.4706 10.5285 41.9189 4.25127 46.4896C1.4671 48.5169 3.62276 51.3543 1.92999 53.5729" stroke="#5515DD" stroke-width="2" stroke-linecap="round"/>
				<defs>
					<linearGradient id="paint0_linear_193_8249" x1="33.5513" y1="1" x2="33.5513" y2="52.4027" gradientUnits="userSpaceOnUse">
						<stop stop-color="#5515DD" stop-opacity="0.29"/>
						<stop offset="1" stop-color="white" stop-opacity="0"/>
					</linearGradient>
				</defs>
			</svg>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl p-3 gap-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center justify-between w-full">
		<div class="flex items-start flex-col gap-1">
			<p class="text-xs text-gray-600 dark:text-gray-400">Update Ocober 2022 - 3:23AM</p>
			<h2 class="text-xs font-medium block">CURRENT PRICE</h2>
		</div>
		<button class="h-8 w-8 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
			<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 13 8" fill="none">
				<path fill-rule="evenodd" clip-rule="evenodd" d="M0 1.375C0 1.14294 0.0978313 0.920376 0.271972 0.756282C0.446113 0.592187 0.682299 0.5 0.928571 0.5H12.0714C12.3177 0.5 12.5539 0.592187 12.728 0.756282C12.9022 0.920376 13 1.14294 13 1.375C13 1.60706 12.9022 1.82962 12.728 1.99372C12.5539 2.15781 12.3177 2.25 12.0714 2.25H0.928571C0.682299 2.25 0.446113 2.15781 0.271972 1.99372C0.0978313 1.82962 0 1.60706 0 1.375ZM0 6.625C0 6.39294 0.0978313 6.17038 0.271972 6.00628C0.446113 5.84219 0.682299 5.75 0.928571 5.75H12.0714C12.3177 5.75 12.5539 5.84219 12.728 6.00628C12.9022 6.17038 13 6.39294 13 6.625C13 6.85706 12.9022 7.07962 12.728 7.24372C12.5539 7.40781 12.3177 7.5 12.0714 7.5H0.928571C0.682299 7.5 0.446113 7.40781 0.271972 7.24372C0.0978313 7.07962 0 6.85706 0 6.625Z" fill="currentColor"/>
			</svg>
		</button>
	</header>
	<section class="flex items-center justify-start w-full gap-2">
		<h2 class="font-semibold text-purple-600">€657.000</h2>
		<div class="flex items-center justify-center h-5 px-1.5 rounded-sm font-medium text-xs bg-purple-200 text-purple-600">
			<span>32.65%</span>
		</div>
	</section>
	<section class="flex items-center w-full justify-between gap-2">
    <div class="flex-1 flex items-center gap-2">
      <div class="flex-none w-9 h-9 rounded-full flex items-center justify-center text-lg font-semibold bg-purple-200 text-purple-900 dark:bg-purple-600/50 dark:text-white">H</div>
      <p class="w-full text-xs">Lorem ipsum dolor sit amet consetur...</p>
    </div>
    <div class="flex items-end">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-full h-11" viewBox="0 0 77 35" fill="none">
        <path d="M1 22.9248C1.53939 23.2428 1.98696 23.7158 2.51667 24.0146C2.86547 24.2113 3.38854 24.1596 3.56583 24.63C3.77967 25.1974 4.08334 24.148 4.28883 23.9056C4.53772 23.6121 4.87183 22.8725 5.20753 22.9825C6.5159 23.4111 7.98491 23.2918 9.32809 23.271C9.4724 23.2687 9.61077 23.1533 9.61077 23.3479C9.61077 23.3863 9.61496 23.4488 9.61365 23.5124C9.8309 23.3938 10.1601 23.2741 10.2196 23.271C10.9386 23.2333 11.1296 23.8577 11.72 24.2326C12.1548 24.5087 12.1549 24.8276 12.1549 24.0787C12.1549 23.2089 12.5398 23.0256 12.9377 22.3478C13.0823 22.1015 13.2254 21.8301 13.4758 21.7644C13.7832 21.6839 14.0466 21.6629 14.3728 21.6426C15.8466 21.5511 17.3206 21.2492 18.7543 20.8477C19.4595 20.6502 20.1644 20.4258 20.8526 20.1553C21.0372 20.0828 21.0064 20.5318 21.0592 20.7067C21.1204 20.9099 21.4378 22.1811 21.5484 22.1811C21.5883 22.1811 21.5484 22.0871 21.5484 22.0401V21.3862C21.5484 20.9829 21.6072 20.7298 21.7985 20.3861C21.9637 20.0892 23.0066 18.6481 23.1629 19.0783C23.3283 19.5332 23.3345 19.9153 23.5815 20.3348C23.6422 20.4378 23.6925 20.7292 23.7066 20.4887C23.7288 20.1075 23.6796 19.1906 23.9457 18.9116C24.1453 18.7024 25.2367 21.9822 25.4189 22.4119C25.4591 22.5067 25.7377 23.2704 25.8755 23.0402C26.151 22.5799 26.6788 22.2241 27.0334 21.8798C27.8857 21.0526 28.6408 20.1251 29.4579 19.2578C29.5206 19.1913 29.7863 19.2499 29.708 19.2129C29.4381 19.0856 29.7887 18.4223 29.8385 18.2898C30.2124 17.2934 30.4555 16.2458 30.7245 15.2062C30.8353 14.7781 31.1105 14.2839 31.1377 13.8343C31.1481 13.6618 31.0598 13.1681 31.2355 13.1163C31.4396 13.0561 31.3187 12.2414 31.3388 12.0393C31.3692 11.7343 31.6056 12.4776 31.6161 12.5009C31.9456 13.2334 32.2109 13.9822 32.5076 14.7318C32.5786 14.9113 32.7769 16.3603 32.9642 16.1743C33.4456 15.6962 33.7541 14.9787 34.2417 14.4882C34.767 13.9598 34.9571 15.338 35.0571 15.7127C35.3772 16.9116 36.3729 20.4949 36.0519 19.2963C35.9066 18.7537 36.6683 17.8309 36.9869 17.5526C37.0965 17.4569 37.216 17.5183 37.2968 17.6295C37.528 17.9476 37.5423 17.6966 37.8349 17.4628C38.6776 16.7896 38.9359 19.832 39.4495 19.2642C39.5764 19.1239 39.6121 18.7997 39.7702 18.7065C40.0495 18.5418 40.4186 19.4824 40.5095 19.6681C40.5418 19.7342 40.8031 20.3909 40.9226 20.3028C41.1152 20.1608 41.1547 20.0399 41.4119 20.0399C42.1098 20.0399 42.2469 21.1019 42.4665 21.7708C42.7011 22.4857 43.0226 22.9113 43.4015 23.5017C43.5469 23.7284 43.369 23.294 43.4341 22.9376C43.6313 21.8586 44.2297 21.0891 44.8692 20.3348C44.9455 20.2449 45.0143 20.0153 45.1302 20.0912C45.4113 20.2754 45.7427 18.3237 45.7716 18.168C45.8008 18.011 45.984 15.8954 46.1304 15.905C46.5611 15.9332 46.8886 17.4404 47.0274 17.7962C47.1494 18.1089 47.2744 18.4957 47.5003 18.0718C47.9157 17.2926 48.076 16.1938 48.5984 15.5139C48.853 15.1826 49.0282 15.6983 49.1638 15.8858C49.3837 16.1899 49.6702 15.7749 49.8705 15.6293C50.4318 15.2213 51.4338 14.1692 51.9362 15.046C52.1285 15.3817 52.2804 15.8204 52.545 16.0909C52.8154 16.3672 53.2558 15.1669 53.3604 15.0139C53.7611 14.4282 54.3252 14.0937 54.7738 13.5779C54.9998 13.3181 55.163 12.9911 55.4588 12.8214C55.6146 12.732 55.7525 12.8586 55.8393 13.0073C56.0878 13.4337 56.5621 11.7619 56.6493 11.5265C56.9757 10.6443 57.055 11.5786 57.5843 11.1931C58.978 10.1779 60.9173 10.0007 62.5257 10.0007C62.6418 10.0007 62.5758 9.99221 62.5257 9.91094C62.3949 9.69884 62.7201 9.33634 62.7975 9.1673C62.9873 8.7526 63.0519 8.21661 63.1889 7.77617C63.2323 7.63657 63.3412 7.00046 63.5259 7.00046C63.8461 7.00046 64.3258 8.4686 64.4392 8.71855C64.6252 9.12872 65.0915 10.4938 65.5264 10.6802C65.6159 10.7186 66.3203 7.62724 66.4125 7.28895C66.4739 7.06362 66.686 6.13816 66.9507 6.03885C67.0808 5.99 67.5119 6.91369 67.5921 7.03893C67.596 7.04503 67.5998 7.05092 67.6034 7.05659C67.5838 7.01159 67.5663 6.96 67.5595 6.91071C67.5132 6.5753 67.7509 6.27749 67.9835 6.1286C68.4162 5.85156 68.874 6.64942 69.136 6.91712C69.4407 7.22855 70.4393 7.59793 70.7015 7.10304C71.254 6.06057 71.0603 5.21909 71.0603 4.06434C71.0603 3.80371 71.5682 3.32457 71.7453 3.21812C72.223 2.93092 72.4161 3.41055 72.6694 3.84637C72.8309 4.12422 73.3083 5.32729 73.637 5.39778C73.787 5.42992 73.5912 5.03672 73.6153 4.85927C73.6672 4.47695 73.9024 4.18626 74.0882 3.88484C74.3299 3.49289 74.5503 2.97998 74.92 2.7309C75.0827 2.62124 75.2538 2.11997 75.4418 1.94879C75.5897 1.81419 75.8472 1.60151 75.9528 1.37185V1C76.0221 1.12262 76.009 1.24964 75.9528 1.37185V34.9024H1V22.9248Z" fill="url(#paint0_linear_193_8328)"/>
        <path d="M1 22.9248C1.53939 23.2428 1.98696 23.7158 2.51667 24.0146C2.86547 24.2113 3.38854 24.1596 3.56583 24.63C3.77967 25.1974 4.08334 24.148 4.28883 23.9056C4.53772 23.6121 4.87183 22.8725 5.20753 22.9825C6.5159 23.4111 7.98491 23.2918 9.32809 23.271C9.4724 23.2687 9.61077 23.1533 9.61077 23.3479C9.61077 23.4616 9.6475 23.7861 9.46943 23.7261C9.19711 23.6344 10.1162 23.2764 10.2196 23.271C10.9386 23.2333 11.1296 23.8577 11.72 24.2326C12.1548 24.5087 12.1549 24.8276 12.1549 24.0787C12.1549 23.2089 12.5398 23.0256 12.9377 22.3478C13.0823 22.1015 13.2254 21.8301 13.4758 21.7644C13.7832 21.6839 14.0466 21.6629 14.3728 21.6426C15.8466 21.5511 17.3206 21.2492 18.7543 20.8477C19.4595 20.6502 20.1644 20.4258 20.8526 20.1553C21.0372 20.0828 21.0064 20.5318 21.0592 20.7067C21.1204 20.9099 21.4378 22.1811 21.5484 22.1811C21.5883 22.1811 21.5484 22.0871 21.5484 22.0401C21.5484 21.8221 21.5484 21.6042 21.5484 21.3862C21.5484 20.9829 21.6072 20.7298 21.7985 20.3861C21.9637 20.0892 23.0066 18.648 23.1629 19.0783C23.3283 19.5332 23.3345 19.9153 23.5815 20.3348C23.6422 20.4378 23.6925 20.7292 23.7065 20.4887C23.7288 20.1075 23.6796 19.1906 23.9457 18.9116C24.1453 18.7024 25.2367 21.9822 25.4189 22.4119C25.4591 22.5067 25.7377 23.2704 25.8755 23.0402C26.151 22.5799 26.6788 22.224 27.0334 21.8798C27.8857 21.0526 28.6408 20.1251 29.4579 19.2578C29.5206 19.1913 29.7863 19.2499 29.708 19.2129C29.4381 19.0856 29.7887 18.4223 29.8385 18.2898C30.2124 17.2934 30.4555 16.2458 30.7245 15.2062C30.8353 14.7781 31.1105 14.2839 31.1377 13.8343C31.1481 13.6618 31.0598 13.1681 31.2355 13.1163C31.4396 13.0561 31.3187 12.2413 31.3388 12.0393C31.3692 11.7343 31.6056 12.4776 31.6161 12.5009C31.9456 13.2334 32.2109 13.9822 32.5076 14.7318C32.5786 14.9113 32.7769 16.3603 32.9642 16.1742C33.4456 15.6962 33.7541 14.9787 34.2417 14.4882C34.767 13.9598 34.9571 15.338 35.0571 15.7127C35.3772 16.9116 36.3729 20.4949 36.0519 19.2963C35.6471 17.7845 37.3208 17.8736 37.8349 17.4628C38.6776 16.7896 38.9359 19.832 39.4495 19.2642C39.5764 19.1239 39.6121 18.7997 39.7702 18.7065C40.0495 18.5418 40.4186 19.4824 40.5095 19.6681C40.5418 19.7342 40.8031 20.3909 40.9226 20.3028C41.1152 20.1608 41.1547 20.0399 41.4119 20.0399C42.1098 20.0399 42.2469 21.1019 42.4665 21.7708C42.7011 22.4857 43.0226 22.9113 43.4015 23.5017C43.5469 23.7284 43.369 23.294 43.4341 22.9376C43.6313 21.8586 44.2297 21.0891 44.8692 20.3348C44.9455 20.2449 45.0143 20.0153 45.1302 20.0912C45.4113 20.2754 45.7427 18.3237 45.7716 18.168C45.8008 18.011 45.984 15.8954 46.1304 15.905C46.5611 15.9332 46.8886 17.4404 47.0274 17.7962C47.1494 18.1089 47.2744 18.4957 47.5003 18.0718C47.9157 17.2926 48.076 16.1938 48.5984 15.5139C48.6146 15.4929 51.7891 14.7894 51.9362 15.046C52.1285 15.3817 52.2804 15.8204 52.545 16.0909C52.8154 16.3672 53.2558 15.1669 53.3604 15.0139C53.7611 14.4282 54.3252 14.0937 54.7738 13.5779C54.9998 13.3181 55.163 12.9911 55.4588 12.8214C55.6146 12.732 55.7525 12.8586 55.8393 13.0073C56.0878 13.4337 56.5621 11.7619 56.6493 11.5265C56.9757 10.6443 57.055 11.5786 57.5843 11.1931C58.978 10.1779 60.9172 10.0007 62.5257 10.0007C62.6418 10.0007 62.5758 9.99221 62.5257 9.91094C62.3949 9.69884 62.7201 9.33634 62.7975 9.1673C62.9873 8.7526 63.0519 8.2166 63.1889 7.77616C63.2323 7.63657 63.3412 7.00046 63.5259 7.00046C63.8461 7.00046 64.3258 8.4686 64.4392 8.71854C64.6252 9.12871 65.0915 10.4937 65.5264 10.6802C65.6159 10.7186 66.3203 7.62724 66.4125 7.28895C66.4739 7.06362 66.686 6.13816 66.9507 6.03885C67.0808 5.99 67.5119 6.91369 67.5921 7.03893C67.7876 7.34402 67.5868 7.10867 67.5595 6.91071C67.5132 6.5753 67.7509 6.27749 67.9835 6.1286C68.4162 5.85156 68.874 6.64942 69.136 6.91712C69.4407 7.22855 70.4393 7.59792 70.7015 7.10304C71.254 6.06057 71.0603 5.21908 71.0603 4.06434C71.0603 3.80371 71.5682 3.32457 71.7453 3.21812C72.223 2.93092 72.4161 3.41055 72.6694 3.84637C72.8309 4.12422 73.3083 5.32729 73.637 5.39778C73.787 5.42992 73.5912 5.03672 73.6153 4.85927C73.6672 4.47695 73.9023 4.18626 74.0882 3.88484C74.3299 3.49289 74.5503 2.97998 74.92 2.7309C75.0827 2.62124 75.2538 2.11997 75.4418 1.94879C75.6684 1.74256 76.1524 1.35306 75.9528 1" stroke="url(#paint1_linear_193_8328)" stroke-linecap="round"/>
        <defs>
          <linearGradient id="paint0_linear_193_8328" x1="38.5" y1="-3.42775" x2="38.5" y2="34.9024" gradientUnits="userSpaceOnUse">
            <stop offset="0.144057" stop-color="#730FD6" stop-opacity="0.22"/>
            <stop offset="0.983952" stop-color="white" stop-opacity="0"/>
          </linearGradient>
          <linearGradient id="paint1_linear_193_8328" x1="74.8601" y1="2.97066" x2="1.94318" y2="22.1943" gradientUnits="userSpaceOnUse">
            <stop offset="0.161546" stop-color="#5B0FD6"/>
            <stop offset="1" stop-color="#EA0FBA"/>
          </linearGradient>
        </defs>
      </svg>
    </div>
	</section>
</article>

<section class="grid grid-cols-12 gap-3 mb-3" data-filter="finance">
	<article class="border shadow-sm break-inside col-span-8 flex flex-col items-center justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
		coming soon...
	</article>
	<section class="col-span-4 grid gap-3">
		<article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
			<div class="w-11 h-11 flex items-center justify-center rounded-full bg-green-200">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 11 12" fill="none">
					<path d="M1.375 11.5C2.13125 11.5 2.75 10.8813 2.75 10.125V5.3125C2.75 4.55625 2.13125 3.9375 1.375 3.9375C0.61875 3.9375 0 4.55625 0 5.3125V10.125C0 10.8813 0.61875 11.5 1.375 11.5ZM8.25 8.0625V10.125C8.25 10.8813 8.86875 11.5 9.625 11.5C10.3813 11.5 11 10.8813 11 10.125V8.0625C11 7.30625 10.3813 6.6875 9.625 6.6875C8.86875 6.6875 8.25 7.30625 8.25 8.0625ZM5.5 11.5C6.25625 11.5 6.875 10.8813 6.875 10.125V1.875C6.875 1.11875 6.25625 0.5 5.5 0.5C4.74375 0.5 4.125 1.11875 4.125 1.875V10.125C4.125 10.8813 4.74375 11.5 5.5 11.5Z" fill="#2A9D8F"/>
				</svg>
			</div>
			<h2 class="font-medium text-base">23.00</h2>
		</article>
		<article class="border shadow-sm break-inside flex flex-col items-center justify-between rounded-xl gap-2 p-4 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900">
			<div class="w-11 h-11 flex items-center justify-center rounded-full bg-yellow-200">
				<svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 13 14" fill="none">
					<path d="M9.78357 4.26401C10.5315 4.09794 11.5056 3.35562 11.6538 2.99004C11.7408 2.77604 11.3072 2.44166 11.1913 2.3068C10.926 1.99917 11.033 1.84759 11.1356 1.48089C11.2526 1.06403 10.9751 0.603706 10.5816 0.423143C10.1882 0.242579 9.71781 0.299423 9.32213 0.475528C8.92645 0.651633 8.58873 0.934739 8.2577 1.21339C8.01583 1.06069 7.63019 0.386361 7.00602 0.824394C6.57467 1.12645 6.53566 1.78405 6.59139 2.30903C6.7218 3.52058 7.02051 4.14921 7.58337 4.31863C8.29448 4.53263 9.08138 4.42006 9.78357 4.26401Z" fill="#FFCA28"/>
					<path d="M10.9985 0.778687C10.9037 2.41156 9.31098 3.49494 8.55529 3.97198L9.04571 4.3933C9.04571 4.3933 9.35668 4.39998 9.78245 4.264C10.5125 4.03217 11.5792 3.37679 11.6527 2.99003C11.7608 2.42716 11.1835 2.54977 11.0531 2.10505C10.9851 1.86987 11.3841 1.42515 10.9985 0.778687ZM8.25881 1.21449C8.25881 1.21449 7.97459 0.923583 7.76393 0.790947C7.65916 0.988229 7.58449 1.20223 7.5477 1.42292C7.48194 1.8108 7.5477 2.3614 7.70263 2.77157C7.72715 2.8351 7.81855 2.82507 7.82858 2.75819C7.96233 1.87656 8.25881 1.21449 8.25881 1.21449Z" fill="#E2A610"/>
					<path d="M6.2726 4.12025C6.2726 4.12025 2.7962 4.49587 1.22798 7.51417C-0.340247 10.5325 0.9928 12.3626 2.40387 13.0292C3.81494 13.6957 7.37047 13.9309 9.68324 13.3825C11.996 12.8341 12.5745 11.6972 12.4664 10.5994C12.3092 8.99657 10.8201 8.01128 10.8201 8.01128C10.8201 8.01128 10.8792 6.03177 9.34329 4.74665C7.98015 3.60531 6.2726 4.12025 6.2726 4.12025Z" fill="#FFCA28"/>
					<path d="M7.69936 9.19936C6.9537 8.25865 6.07318 8.1327 5.79119 7.79498C5.63737 7.61107 5.54709 7.42493 5.58164 7.19421C5.61842 6.949 5.90264 6.77959 6.12333 6.73835C6.3808 6.68931 6.99494 6.71494 7.51099 7.20647C7.6336 7.32239 7.58902 7.50296 7.58567 7.66457C7.57675 8.01121 8.07275 8.34781 8.474 8.05802C8.87636 7.76711 8.56762 7.11954 8.30792 6.80522C8.11176 6.56782 7.40065 6.04507 6.51678 5.96259C6.26823 5.93919 5.26844 5.79095 4.69109 6.88882C4.52501 7.20425 4.46371 7.96662 5.33309 8.61086C5.51477 8.74572 6.45771 9.22499 6.71964 9.53596C7.17327 10.0743 6.8623 10.548 6.50786 10.6104C5.54152 10.7798 4.99425 10.2571 4.89283 9.97065C4.82038 9.76668 4.89617 9.546 4.80255 9.35429C4.70669 9.157 4.51052 9.07898 4.30321 9.14474C3.62331 9.36097 3.83954 10.1044 4.14048 10.5135C4.4626 10.9515 4.85827 11.2156 5.303 11.3605C6.96262 11.9011 7.76066 11.0473 7.89999 10.4221C8.00253 9.96396 7.99138 9.56717 7.69936 9.19936Z" fill="#6B4B46"/>
					<path d="M7.29811 5.32733C5.88592 8.34341 5.64294 12.152 5.64294 12.152" stroke="#6B4B46" stroke-miterlimit="10"/>
					<path d="M8.46942 3.42917C9.41013 3.73569 9.61856 4.58612 9.55057 4.81795C9.46921 5.08991 8.42707 4.03105 6.87779 4.09458C6.3361 4.11688 6.49326 3.78473 6.74404 3.59302C7.07507 3.34001 7.63125 3.15722 8.46942 3.42917Z" fill="#6D4C41"/>
					<path d="M8.46942 3.42917C9.41013 3.73569 9.61856 4.58612 9.55057 4.81795C9.46921 5.08991 8.42707 4.03105 6.87779 4.09458C6.3361 4.11688 6.49326 3.78473 6.74404 3.59302C7.07507 3.34001 7.63125 3.15722 8.46942 3.42917Z" fill="#6B4B46"/>
					<path d="M10.1213 6.42743C10.2394 6.34606 10.6362 6.4865 10.7477 7.26337C10.8023 7.64344 10.819 8.01126 10.819 8.01126C10.819 8.01126 10.3509 7.59106 10.1959 7.29569C10.0009 6.9223 9.92509 6.56118 10.1213 6.42743Z" fill="#E2A610"/>
				</svg>
			</div>
			<h2 class="font-medium text-base">88.30</h2>
		</article>
	</section>
</section>

<article class="border shadow-sm break-inside overflow-hidden relative grid grid-cols-12 items-start gap-2 rounded-xl text-sm mb-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <div class="col-span-8 flex items-center justify-start gap-2 flex-1 pl-3 pt-3 pb-3">
    <span class="flex-none w-9 h-9 rounded-full flex items-center justify-center text-lg font-bold text-white bg-gradient-to-tr from-rose-600 to-indigo-500">
      A
    </span>
    <div class="flex flex-col">
      <h2 class="font-medium text-base leading-6"> Globals sales </h2>
      <p class="-mt-0.5 text-xs text-gray-500">Current trends</p>
    </div>
  </div>
  <div class="col-span-4 flex items-center justify-center p-3 border-l flex-none h-full dark:border-gray-900">
    <div class='flex items-center text-xs gap-1 h-6 px-1 font-medium rounded text-rose-600 bg-rose-100 dark:bg-rose-500/20 dark:text-rose-500'>
      <svg width='16' height='16' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'>
        <path d='M11,4H13V16L18.5,10.5L19.92,11.92L12,19.84L4.08,11.92L5.5,10.5L11,16V4Z' fill='currentColor' />
      </svg>
      <span>23.6%</span>
    </div>
  </div>
</article>

<article class='border flex flex-row justify-between items-center break-inside rounded-xl gap-2 p-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:border-gray-900' data-filter="finance">
	<section class='flex flex-1 items-start flex-col p-4 gap-1 rounded-lg bg-gray-100 text-black dark:bg-gray-900 dark:text-white'>
		<p class='text-gray-500 dark:text-gray-400'>Current trends</p>
		<h2 class='font-semibold text-lg'>324K</h2>
		<div class='flex items-center gap-1 py-0.5 px-2 font-medium rounded-md text-[#f4006e] bg-[#f4006e16] dark:bg-[#b2417467]'>
			<svg width='20' height='20' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'>
				<path d='M11,4H13V16L18.5,10.5L19.92,11.92L12,19.84L4.08,11.92L5.5,10.5L11,16V4Z' fill='currentColor' />
			</svg>
			<span>43%</span>
		</div>
	</section>
	<section class='flex flex-1 items-start flex-col p-4 rounded-lg gap-1 bg-transparent text-black dark:text-white'>
		<p class='text-gray-500 dark:text-gray-400'>Customers</p>
		<h2 class='font-semibold text-lg'>1045K</h2>
		<div class='flex items-center gap-1 py-0.5 px-2 font-medium rounded-md text-[#0ac66b] bg-[#00e1741e]'>
			<svg width='20' height='20' viewBox='0 0 24 24' fill='none' xmlns='http://www.w3.org/2000/svg'>
				<path d='M13,20H11V8L5.5,13.5L4.08,12.08L12,4.16L19.92,12.08L18.5,13.5L13,8V20Z' fill='currentColor' />
			</svg>
			<span>43%</span>
		</div>
	</section>
</article>

<article class="shadow-sm break-inside flex items-center flex-row justify-between rounded-xl p-4 mb-3 text-sm text-white bg-gradient-to-tr from-blue-700 via-violet-800 to-fuchsia-900" data-filter="finance">
	<header class="flex flex-col items-start gap-2">
		<span class="uppercase text-xs font-medium text-white dark:text-gray-400">CURRENT PRICE</span>
		<div class="flex items-center justify-center gap-2">
			<h2 class="text-sm sm:text-base font-medium">€45.00</h2>
			<span class="px-2 py-[2px] text-xs rounded-sm bg-white/20 text-white">-082%</span>
		</div>
		<p class="text-xs text-white/80">Update now - 3:23AM</p>
	</header>
	<section class="flex flex-col gap-2 max-w-[7rem]">
		<div class="flex flex-row items-center gap-2">
			<svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
				<path d="M17 17L7.8 7.7M7 17V7h10"></path>
			</svg>
			<span class="font-semibold uppercase text-xs">Upward</span>
		</div>
		<div class="w-full">
			<svg class="w-full" viewBox="0 0 141 34" fill="none" xmlns="http://www.w3.org/2000/svg">
				<g >
					<path d="M5 1.06827C21.6434 0.767281 22.9399 12.3208 34.9648 17.0373C40.1853 19.085 49.7907 6.92438 50.5584 9.19207C52.0191 13.5068 56.5137 13.1684 59.691 15.8304C62.3177 18.031 66.82 17.223 70.2031 17.223C71.4937 17.223 70.5663 21.5846 71.8795 22.3604C76.5857 25.1406 100.925 -1.04184 101.181 7.6911C101.267 10.6171 104.228 14.784 107.729 14.9638C112.327 15.2001 116.088 13.9989 118.887 18.0586C121.415 21.7246 125.071 23.9078 129.941 23.9078C133.089 23.9078 132.858 20.66 136 24.0625" stroke="url(#paint0_linear_228_432)" stroke-width="2" stroke-linecap="round"></path>
				</g>
				<defs>
					<linearGradient id="paint0_linear_228_432" x1="5" y1="1.0625" x2="139.386" y2="19.4725" gradientUnits="userSpaceOnUse">
						<stop stop-color="#1decc2"></stop>
						<stop offset="1" stop-color="#ffd500"> </stop>
					</linearGradient>
				</defs>
			</svg>
		</div>
	</section>
</article>

<article class="border shadow-sm break-inside relative flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<div class="flex items-start gap-3">
		<div class="flex-none flex items-center justify-center w-12 h-12 mt-0.5 rounded-2xl bg-rose-100 text-rose-600">
			<svg width="26" height="26" viewBox="0 0 512 512"><rect x="64" y="320" width="48" height="160" rx="8" ry="8" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="288" y="224" width="48" height="256" rx="8" ry="8" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="400" y="112" width="48" height="368" rx="8" ry="8" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/><rect x="176" y="32" width="48" height="448" rx="8" ry="8" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/></svg>
		</div>
		<header class="flex flex-col items-start">
			<h2 class="text-base font-semibold">Finance App</h2>
			<p>Statistics center for your finances and spending.</p>
		</header>
	</div>
	<span class="absolute top-3 right-3 rounded-full w-6 h-6 flex items-center justify-center bg-green-500 text-white">
		<svg width="16" height="16" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
			<path clip-rule="evenodd" fill-rule="evenodd" d="M10.788 3.21c.448-1.077 1.976-1.077 2.424 0l2.082 5.006 5.404.434c1.164.093 1.636 1.545.749 2.305l-4.117 3.527 1.257 5.273c.271 1.136-.964 2.033-1.96 1.425L12 18.354 7.373 21.18c-.996.608-2.231-.29-1.96-1.425l1.257-5.273-4.117-3.527c-.887-.76-.415-2.212.749-2.305l5.404-.434 2.082-5.005Z"></path>
		</svg>
	</span>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-3 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<div class="flex items-center gap-4">
		<div class="flex-none w-10 h-10 rounded-full flex items-center justify-center text-lg font-semibold bg-green-200 text-green-900 dark:bg-green-600/50 dark:text-white">A</div>
		<div class="flex-auto">
			<a href="#" class="font-medium block">Anabel Oliva</a>
			<span class="block text-xs text-gray-600 dark:text-gray-400">Dog trainer</span>
		</div>
	</div>
	<div class="flex flex-col items-end">
		<span class="font-semibold">€ 876.00</span>
		<span class="text-xs text-gray-600 dark:text-gray-400">23 min ago</span>
	</div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex items-center justify-between gap-5 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <div class="absolute w-14 h-14 bg-indigo-500 rounded-full -top-8 left-1/2 blur-3xl"></div>
  <header class="flex items-center gap-2 flex-none">
    <svg width="40" height="40" viewBox="0 0 26 27" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M20.4944 3.24707C19.8854 3.96066 19.6 5.55908 20.2184 7.18606C20.8369 8.81303 21.7883 8.461 22.3782 10.1165C23.1584 12.3048 22.7969 15.2448 22.7969 15.2448C22.7969 15.2448 23.7388 17.9659 24.3953 15.0735C25.851 9.64079 20.4944 4.58861 20.4944 3.24707Z"
        fill="url(#paint0_radial_136_2508)" />
      <path
        d="M13.035 25.8057C19.305 25.8057 24.3762 20.7059 24.3762 14.4074C24.3762 8.10879 19.2955 3.01855 13.035 3.01855C6.77447 3.01855 1.70326 8.11831 1.70326 14.4074C1.69375 20.7059 6.77447 25.8057 13.035 25.8057Z"
        fill="url(#paint1_radial_136_2508)" />
      <path
        d="M21.5314 21.4385C21.284 21.6098 21.0272 21.762 20.7608 21.9047C21.1128 21.3814 21.4458 20.8486 21.7407 20.2968C21.9786 20.0304 22.2069 19.7735 22.3877 19.488C22.4734 19.3453 22.578 19.1836 22.6827 18.9838C23.3201 17.8325 24.0242 15.9772 24.0432 14.0743V13.9316C24.0432 13.4559 23.9957 12.9706 23.9005 12.5044C23.91 12.5425 23.91 12.5805 23.9196 12.6186C23.91 12.5901 23.91 12.5615 23.9005 12.533C23.91 12.5805 23.9196 12.6376 23.9291 12.6852C24.0623 13.7889 23.9671 14.864 23.5009 15.6632C23.4914 15.6727 23.4819 15.6823 23.4819 15.7013C23.7197 14.493 23.8054 13.1609 23.539 11.8289C23.539 11.8289 23.4343 11.1819 22.6351 9.21242C22.1784 8.0802 21.3602 7.14779 20.6466 6.47226C20.0186 5.69207 19.4382 5.16878 19.1243 4.83577C18.4678 4.14121 18.1918 3.61792 18.0777 3.28491C17.9825 3.23734 16.7171 2.00997 16.622 1.9624C16.0701 2.8187 14.348 5.48275 15.1662 7.96603C15.5373 9.09825 16.4792 10.2685 17.4687 10.925C17.5163 10.9726 18.0586 11.5625 18.3155 12.8945C18.5819 14.2741 18.4392 15.3397 17.8969 16.9287C17.2499 18.3178 15.5944 19.6974 14.0435 19.8401C10.7325 20.1445 9.51466 18.175 9.51466 18.175C10.6944 18.6508 12.0074 18.5461 12.8067 18.0609C13.6059 17.5661 14.0911 17.1951 14.4907 17.3378C14.8808 17.4805 15.1853 17.0619 14.9094 16.6242C14.4717 15.9487 13.6725 15.6061 12.8828 15.7393C12.0836 15.8725 11.3414 16.51 10.2948 15.8916C10.2282 15.8535 10.1616 15.8059 10.095 15.7584C10.0284 15.7108 10.3234 15.825 10.2473 15.7774C10.0475 15.6632 9.6764 15.4254 9.59077 15.3397C9.57174 15.3207 9.75252 15.3968 9.73349 15.3778C8.7535 14.5691 8.87719 14.0172 8.90573 13.6747C8.93427 13.3988 9.10553 13.0468 9.41 12.904C9.55271 12.9802 9.64786 13.0468 9.64786 13.0468C9.64786 13.0468 9.58126 12.9231 9.55271 12.8565C9.56223 12.8469 9.57174 12.8565 9.59077 12.8469C9.71446 12.904 9.97135 13.0563 10.1141 13.1419C10.2948 13.2656 10.3519 13.3798 10.3519 13.3798C10.3519 13.3798 10.3995 13.3512 10.3614 13.2466C10.3519 13.199 10.2948 13.0563 10.1141 12.9136H10.1236C10.2282 12.9706 10.3329 13.0468 10.428 13.1229C10.4756 12.9421 10.5708 12.7518 10.5517 12.4093C10.5422 12.1714 10.5422 12.1048 10.5042 12.0097C10.4661 11.9336 10.5232 11.8955 10.5898 11.9811C10.5803 11.9145 10.5612 11.8479 10.5327 11.7908V11.7813C10.6183 11.4959 12.2738 10.7443 12.3975 10.6586C12.5973 10.5159 12.7591 10.3351 12.8828 10.1258C12.9779 9.9831 13.0445 9.77378 13.0635 9.4598C13.0731 9.23145 12.9684 9.07922 11.2843 8.90796C10.8277 8.86039 10.5517 8.52738 10.3995 8.22292C10.371 8.15632 10.3424 8.09923 10.3139 8.03263C10.2853 7.96603 10.2663 7.88991 10.2473 7.8138C10.5232 7.0241 10.9799 6.35808 11.6649 5.85382C11.703 5.81576 11.5127 5.86333 11.5508 5.82527C11.5983 5.78722 11.8742 5.67304 11.9313 5.6445C11.9979 5.61596 11.6554 5.46372 11.3509 5.50178C11.0465 5.53984 10.9799 5.5779 10.8086 5.6445C10.8752 5.5779 11.0941 5.48275 11.0465 5.49227C10.7135 5.53984 10.3044 5.73964 9.95232 5.95848C9.95232 5.92042 9.96183 5.88236 9.97135 5.8443C9.8096 5.91091 9.40048 6.19634 9.28631 6.4342C9.29582 6.38663 9.29582 6.33906 9.29582 6.29148C9.17213 6.39614 9.05796 6.51032 8.96282 6.64352L8.90573 6.66255C7.95428 6.28197 7.1075 6.25343 6.40343 6.42469C6.2512 6.27245 6.17508 6.38663 5.81353 5.60644C5.78499 5.55887 5.83256 5.65401 5.81353 5.60644C5.75644 5.45421 5.85159 5.80625 5.81353 5.60644C5.22363 6.08217 4.44345 6.61498 4.06287 6.98604C4.06287 7.00507 4.50053 6.86235 4.06287 6.98604C3.91064 7.03361 3.92015 7.11924 3.90112 7.947C3.89161 8.0136 3.90112 8.0802 3.89161 8.13729C3.58715 8.51787 3.38734 8.84136 3.31123 9.01262C2.92113 9.67863 2.49298 10.7252 2.08386 12.3712C2.26463 11.924 2.48347 11.4959 2.74036 11.0868C2.39784 11.9621 2.06483 13.3417 1.99823 15.4539C2.08386 15.0162 2.18852 14.5881 2.32172 14.1599C2.23609 15.9201 2.54055 17.6708 3.20657 19.2978C3.44443 19.8781 3.83452 20.763 4.51005 21.7335C6.62226 23.9503 9.59077 25.3299 12.8828 25.3299C16.3175 25.3299 19.4097 23.8266 21.5314 21.4385Z"
        fill="url(#paint2_linear_136_2508)" />
      <path
        d="M18.9815 23.0464C23.1394 22.5611 24.9852 18.2796 22.6161 18.194C20.4848 18.1274 17.012 23.2747 18.9815 23.0464Z"
        fill="url(#paint3_radial_136_2508)" />
      <path
        d="M22.9205 17.3186C25.7844 15.6536 25.0327 12.0571 25.0327 12.0571C25.0327 12.0571 23.9291 13.3416 23.1774 15.3872C22.4448 17.4138 21.1984 18.3272 22.9205 17.3186Z"
        fill="url(#paint4_radial_136_2508)" />
      <path
        d="M13.8342 25.1774C17.8303 26.4523 21.2555 23.303 19.1433 22.2564C17.2214 21.3145 11.9409 24.578 13.8342 25.1774Z"
        fill="url(#paint5_radial_136_2508)" />
      <path
        d="M23.225 18.8506C23.3201 18.7174 23.4533 18.2797 23.5675 18.0799C24.2716 16.9381 24.2811 16.0343 24.2811 16.0152C24.7092 13.8935 24.6712 13.0182 24.4048 11.4198C24.1955 10.1258 23.2726 8.27047 22.4733 7.38563C21.6551 6.46273 22.226 6.76719 21.4363 6.09166C20.7417 5.32099 20.0567 4.55032 19.6951 4.24586C17.0311 2.01947 17.0882 1.54375 17.1452 1.46763L17.1072 1.50569C17.0786 1.382 17.0501 1.27734 17.0501 1.27734C17.0501 1.27734 15.5849 2.72354 15.2804 5.14973C15.0806 6.72913 15.6705 8.38465 16.5363 9.44075C16.9835 9.99259 17.4878 10.4873 18.0396 10.925C18.6866 11.8574 19.0481 13.0087 19.0481 14.2456C19.0481 17.3473 16.5363 19.8496 13.4346 19.8496C13.016 19.8496 12.5878 19.802 12.1787 19.7069C10.7135 19.4309 9.8762 18.6888 9.44804 18.1845C9.21018 17.8991 9.10553 17.6898 9.10553 17.6898C10.4185 18.156 11.8647 18.0609 12.7496 17.5756C13.6344 17.0809 14.1767 16.7193 14.6144 16.862C15.0425 17.0048 15.3851 16.5861 15.0806 16.158C14.7761 15.7298 13.996 15.1114 12.8352 15.2826C11.9503 15.4158 11.1321 16.0438 9.97134 15.4349C9.89522 15.3968 9.81911 15.3492 9.75251 15.3112C9.67639 15.2636 9.99988 15.3778 9.92377 15.3302C9.69542 15.216 9.29581 14.9782 9.19116 14.8925C9.17213 14.8735 9.36242 14.9496 9.3529 14.9306C8.26825 14.1314 8.40145 13.5891 8.43 13.2465C8.45854 12.9706 8.65835 12.6281 8.99135 12.4854C9.1531 12.5615 9.24824 12.6281 9.24824 12.6281C9.24824 12.6281 9.18164 12.5044 9.14358 12.4378C9.1531 12.4283 9.17213 12.4378 9.18164 12.4283C9.31484 12.4854 9.60979 12.6281 9.76202 12.7232C9.96183 12.8469 10.0284 12.9611 10.0284 12.9611C10.0284 12.9611 10.0855 12.9326 10.0379 12.8279C10.0189 12.7803 9.96183 12.6376 9.76202 12.4949H9.77154C9.88571 12.552 9.99988 12.6281 10.1045 12.7042C10.1616 12.5234 10.2568 12.3331 10.2377 11.9906C10.2282 11.7528 10.2282 11.6862 10.1807 11.6005C10.1426 11.5244 10.1997 11.4864 10.2758 11.572C10.2663 11.5054 10.2377 11.4483 10.2092 11.3817V11.3722C10.3043 11.0868 12.1406 10.3446 12.2738 10.259C12.4927 10.1258 12.6734 9.94502 12.8162 9.7357C12.9208 9.59298 12.9969 9.38367 13.016 9.06969C13.0255 8.92697 12.9779 8.82231 12.4927 8.70814C12.1977 8.64154 11.7505 8.58445 11.0465 8.51785C10.5422 8.47028 10.2377 8.14679 10.0665 7.84232C10.0379 7.77572 9.99988 7.71863 9.97134 7.66155C9.9428 7.59495 9.91425 7.51883 9.89523 7.45223C10.1997 6.65302 10.7515 5.97749 11.4651 5.51128C11.5032 5.47322 11.3034 5.52079 11.3414 5.48274C11.389 5.44468 11.703 5.3305 11.7601 5.30196C11.8362 5.27342 11.4556 5.1307 11.1131 5.15924C10.7706 5.1973 10.704 5.22585 10.5137 5.30196C10.5898 5.23536 10.8276 5.14973 10.7706 5.14973C10.428 5.18779 9.97134 5.37808 9.58125 5.59691C9.58125 5.55885 9.59076 5.52079 9.60028 5.48274C9.4195 5.54934 8.97232 5.83477 8.83912 6.07263C8.84863 6.02506 8.84863 5.97749 8.84863 5.93943C8.71543 6.04409 8.58223 6.15826 8.47757 6.29146L8.46806 6.30098C7.41195 5.9204 6.47953 5.89186 5.69935 6.06312C5.52809 5.91089 5.25217 5.67303 4.86207 4.90235C4.83353 4.85478 4.82402 4.9975 4.80499 4.94993C4.65276 4.59789 4.55761 4.01751 4.57664 3.6179C4.57664 3.6179 4.26266 3.76062 4.00577 4.36003C3.9582 4.46469 3.92966 4.53129 3.8916 4.58838C3.87257 4.60741 3.92014 4.38857 3.92014 4.4076C3.87257 4.48372 3.7584 4.58838 3.71082 4.73109C3.67277 4.83575 3.62519 4.89284 3.59665 5.01653L3.58714 5.02604C3.58714 4.98798 3.59665 4.87381 3.58714 4.89284C3.46345 5.14022 3.35879 5.39711 3.27316 5.654C3.13044 6.11069 2.9687 6.73865 2.94015 7.55689C2.93064 7.61398 2.94015 7.69009 2.93064 7.74718C2.59763 8.12776 2.36928 8.45125 2.28365 8.61299C1.8555 9.27901 1.37978 10.3066 0.923087 11.9431C1.12289 11.4959 1.37027 11.0677 1.6557 10.6681C1.27512 11.5339 0.904058 12.904 0.827942 14.9972C0.923087 14.5595 1.03726 14.1314 1.17998 13.7127C1.11338 15.1114 1.27512 16.8525 2.15997 18.8125C2.68326 19.9637 3.8916 22.3043 6.8506 24.1311C6.8506 24.1311 7.85913 24.8827 9.58125 25.4441C9.70494 25.4916 9.83814 25.5392 9.97134 25.5773C9.93328 25.5583 9.88571 25.5392 9.84765 25.5297C10.9989 25.8722 12.1882 26.053 13.3965 26.053C17.8683 26.053 19.1909 24.2548 19.1909 24.2548L19.1813 24.2643C19.2479 24.2072 19.305 24.1406 19.3621 24.0835C18.658 24.7495 17.0406 24.7971 16.4412 24.7495C17.4687 24.4451 18.1443 24.1882 19.4573 23.6934C19.6095 23.6363 19.7712 23.5697 19.933 23.4936L19.9806 23.4651C20.0091 23.446 20.0472 23.4365 20.0757 23.4175C20.7132 23.113 21.3221 22.742 21.8739 22.2948C23.1964 21.2387 23.4819 20.2111 23.6341 19.5356C23.6151 19.6022 23.5485 19.7544 23.5009 19.8496C23.1584 20.5727 22.4067 21.0294 21.5885 21.4099C21.9786 20.8962 22.3401 20.3634 22.6731 19.8115C22.9396 19.5451 23.0157 19.1265 23.225 18.8506Z"
        fill="url(#paint6_radial_136_2508)" />
      <path
        d="M21.617 21.3719C22.1594 20.782 22.6351 20.0969 23.0062 19.3263C23.9481 17.3472 25.4038 14.0457 24.2621 10.611C23.3582 7.88987 22.1118 6.40561 20.5324 4.9499C17.9635 2.59031 17.2499 1.5342 17.2499 0.90625C17.2499 0.90625 14.2814 4.20777 15.5658 7.66152C16.8503 11.1153 19.4858 10.9821 21.2269 14.5785C23.2821 18.8125 19.5714 23.4365 16.4983 24.7305C16.6885 24.6924 23.3201 23.1891 23.6722 19.3929C23.6531 19.4595 23.5009 20.5156 21.617 21.3719Z"
        fill="url(#paint7_radial_136_2508)" />
      <path
        d="M13.0159 9.06936C13.0254 8.84101 12.9113 8.69829 11.0559 8.51752C10.2948 8.45092 9.99984 7.74685 9.91421 7.44238C9.6478 8.14645 9.53363 8.88858 9.59072 9.78294C9.62877 10.3728 10.0284 11.0008 10.2092 11.3623C10.2092 11.3623 10.2472 11.3053 10.2662 11.2862C10.6183 10.9152 12.1025 10.3538 12.2453 10.2777C12.407 10.1825 12.9969 9.7544 13.0159 9.06936Z"
        fill="url(#paint8_linear_136_2508)" />
      <path
        d="M4.86207 4.90213C4.83353 4.85456 4.82401 4.99727 4.80498 4.9497C4.65275 4.59767 4.55761 4.0268 4.58615 3.61768C4.58615 3.61768 4.27217 3.76039 4.01528 4.3598C3.96771 4.46446 3.93917 4.53106 3.90111 4.58815C3.88208 4.60718 3.92965 4.38835 3.92965 4.40738C3.88208 4.48349 3.76791 4.58815 3.72033 4.72135C3.68228 4.82601 3.6347 4.89261 3.60616 5.02582C3.59665 5.06387 3.61567 4.86407 3.60616 4.89261C2.99723 6.06289 2.88306 7.83258 2.94966 7.75647C4.24363 6.37687 5.71837 6.05338 5.71837 6.05338C5.5376 5.9392 5.19508 5.59668 4.86207 4.90213Z"
        fill="url(#paint9_linear_136_2508)" />
      <path
        d="M9.7525 19.3069C7.9733 18.5457 5.94672 17.4706 6.02283 15.0349C6.12749 11.8285 9.01989 12.4565 9.01989 12.4565C8.91523 12.485 8.62028 12.6943 8.51562 12.9132C8.41096 13.1891 8.21116 13.817 8.81057 14.4735C9.76202 15.5011 6.86011 16.9092 11.3319 19.5733C11.4461 19.6304 10.2853 19.5352 9.7525 19.3069Z"
        fill="url(#paint10_linear_136_2508)" />
      <path
        d="M9.12452 17.7084C10.3899 18.1461 11.8552 18.07 12.74 17.5848C13.3299 17.2517 14.0911 16.7285 14.5478 16.8617C14.1482 16.6999 13.8437 16.6238 13.4726 16.6143C13.406 16.6143 13.3394 16.6143 13.2728 16.6048C13.1396 16.6048 13.0064 16.6143 12.8732 16.6238C12.6449 16.6428 12.3975 16.7855 12.1691 16.7665C12.1596 16.7665 12.388 16.6714 12.3689 16.6714C12.2453 16.6999 12.1121 16.6999 11.9789 16.7189C11.8932 16.7285 11.8171 16.738 11.722 16.7475C9.08646 16.9663 6.86959 15.3203 6.86959 15.3203C6.6793 15.9483 7.71638 17.2137 9.12452 17.7084Z"
        fill="url(#paint11_linear_136_2508)" />
      <path
        d="M21.6075 21.3908C24.2716 18.7744 25.6131 15.606 25.0422 12.0381C25.0422 12.0381 25.2706 13.8649 24.4048 15.7297C24.8234 13.903 24.871 11.6385 23.7673 9.28844C22.3021 6.15818 19.8854 4.50266 18.9625 3.81762C17.5639 2.77103 16.9835 1.71493 16.974 1.49609C16.5553 2.3524 15.2899 5.28285 16.8408 7.80418C18.287 10.1733 20.5704 10.8678 22.1594 13.0371C25.1088 17.0427 21.6075 21.3908 21.6075 21.3908Z"
        fill="url(#paint12_linear_136_2508)" />
      <path
        d="M21.2269 14.5879C20.2945 12.666 19.1338 11.8287 18.0396 10.9248C18.1633 11.1056 18.2013 11.1627 18.2679 11.2864C19.2384 12.3139 20.6561 14.8257 19.6285 17.9845C17.678 23.9216 9.89521 21.1243 9.07697 20.3441C9.40997 23.7788 15.1567 25.4248 18.9054 23.1985C21.0271 21.1624 22.7492 17.7372 21.2269 14.5879Z"
        fill="url(#paint13_linear_136_2508)" />
      <defs>
        <radialGradient id="paint0_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(24.7228 8.67347) rotate(2.2603) scale(8.76182 12.9144)">
          <stop offset="0.1" stop-color="#FFEA00" />
          <stop offset="0.17" stop-color="#FFDE00" />
          <stop offset="0.28" stop-color="#FFBF00" />
          <stop offset="0.43" stop-color="#FF8E00" />
          <stop offset="0.77" stop-color="#FF272D" />
          <stop offset="0.87" stop-color="#E0255A" />
          <stop offset="0.95" stop-color="#CC2477" />
          <stop offset="1" stop-color="#C42482" />
        </radialGradient>
        <radialGradient id="paint1_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(16.7655 4.79546) scale(24.8649)">
          <stop stop-color="#00CCDA" />
          <stop offset="0.22" stop-color="#0083FF" />
          <stop offset="0.26" stop-color="#007AF9" />
          <stop offset="0.33" stop-color="#005FE7" />
          <stop offset="0.44" stop-color="#2639AD" />
          <stop offset="0.52" stop-color="#401E84" />
          <stop offset="0.57" stop-color="#4A1475" />
        </radialGradient>
        <linearGradient id="paint2_linear_136_2508" x1="14.6375" y1="19.5343" x2="9.74652" y2="3.53505"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#000F43" stop-opacity="0.4" />
          <stop offset="0.48" stop-color="#001962" stop-opacity="0.17" />
          <stop offset="1" stop-color="#002079" stop-opacity="0" />
        </linearGradient>
        <radialGradient id="paint3_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(25.49 17.6343) rotate(5.61742) scale(8.35872 8.35872)">
          <stop stop-color="#FFEA00" />
          <stop offset="0.5" stop-color="#FF272D" />
          <stop offset="1" stop-color="#C42482" />
        </radialGradient>
        <radialGradient id="paint4_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(25.5218 9.58386) rotate(5.61742) scale(13.9582)">
          <stop stop-color="#FFE900" />
          <stop offset="0.16" stop-color="#FFAF0E" />
          <stop offset="0.32" stop-color="#FF7A1B" />
          <stop offset="0.47" stop-color="#FF4E26" />
          <stop offset="0.62" stop-color="#FF2C2E" />
          <stop offset="0.76" stop-color="#FF1434" />
          <stop offset="0.89" stop-color="#FF0538" />
          <stop offset="1" stop-color="#FF0039" />
        </radialGradient>
        <radialGradient id="paint5_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(26.2202 22.6538) rotate(5.61743) scale(12.8082 12.8082)">
          <stop stop-color="#FF272D" />
          <stop offset="0.5" stop-color="#C42482" />
          <stop offset="0.99" stop-color="#620700" />
        </radialGradient>
        <radialGradient id="paint6_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(19.0907 10.9732) scale(19.9838)">
          <stop offset="0.16" stop-color="#FFEA00" />
          <stop offset="0.23" stop-color="#FFDE00" />
          <stop offset="0.37" stop-color="#FFBF00" />
          <stop offset="0.54" stop-color="#FF8E00" />
          <stop offset="0.76" stop-color="#FF272D" />
          <stop offset="0.8" stop-color="#F92433" />
          <stop offset="0.84" stop-color="#E91C45" />
          <stop offset="0.89" stop-color="#CF0E62" />
          <stop offset="0.94" stop-color="#B5007F" />
        </radialGradient>
        <radialGradient id="paint7_radial_136_2508" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(17.9449 1.70526) scale(22.7756 22.7756)">
          <stop offset="0.28" stop-color="#FFEA00" />
          <stop offset="0.4" stop-color="#FFDD00" />
          <stop offset="0.63" stop-color="#FFBA00" />
          <stop offset="0.86" stop-color="#FF9100" />
          <stop offset="0.93" stop-color="#FF6711" />
          <stop offset="0.99" stop-color="#FF4A1D" />
        </radialGradient>
        <linearGradient id="paint8_linear_136_2508" x1="4.61424" y1="10.2343" x2="14.4241" y2="8.73625"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#C42482" stop-opacity="0.5" />
          <stop offset="0.47" stop-color="#FF272D" stop-opacity="0.5" />
          <stop offset="0.49" stop-color="#FF2C2C" stop-opacity="0.51" />
          <stop offset="0.68" stop-color="#FF7A1A" stop-opacity="0.72" />
          <stop offset="0.83" stop-color="#FFB20D" stop-opacity="0.87" />
          <stop offset="0.94" stop-color="#FFD605" stop-opacity="0.96" />
          <stop offset="1" stop-color="#FFE302" />
        </linearGradient>
        <linearGradient id="paint9_linear_136_2508" x1="4.5404" y1="7.66189" x2="3.51749" y2="3.98524"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#891551" stop-opacity="0.6" />
          <stop offset="1" stop-color="#C42482" stop-opacity="0" />
        </linearGradient>
        <linearGradient id="paint10_linear_136_2508" x1="6.4078" y1="12.8282" x2="8.51499" y2="15.772"
          gradientUnits="userSpaceOnUse">
          <stop offset="0.01" stop-color="#891551" stop-opacity="0.5" />
          <stop offset="0.48" stop-color="#FF272D" stop-opacity="0.5" />
          <stop offset="1" stop-color="#FF272D" stop-opacity="0" />
        </linearGradient>
        <linearGradient id="paint11_linear_136_2508" x1="10.5141" y1="17.9531" x2="10.707" y2="16.0618"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#C42482" />
          <stop offset="0.08" stop-color="#C42482" stop-opacity="0.81" />
          <stop offset="0.21" stop-color="#C42482" stop-opacity="0.57" />
          <stop offset="0.33" stop-color="#C42482" stop-opacity="0.36" />
          <stop offset="0.45" stop-color="#C42482" stop-opacity="0.2" />
          <stop offset="0.56" stop-color="#C42482" stop-opacity="0.09" />
          <stop offset="0.67" stop-color="#C42482" stop-opacity="0.02" />
          <stop offset="0.77" stop-color="#C42482" stop-opacity="0" />
        </linearGradient>
        <linearGradient id="paint12_linear_136_2508" x1="16.6687" y1="1.83043" x2="24.4777" y2="19.2925"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#FFF14F" />
          <stop offset="0.27" stop-color="#FFEE4C" />
          <stop offset="0.45" stop-color="#FFE643" />
          <stop offset="0.61" stop-color="#FFD834" />
          <stop offset="0.76" stop-color="#FFC41E" />
          <stop offset="0.89" stop-color="#FFAB02" />
          <stop offset="0.9" stop-color="#FFA900" />
          <stop offset="0.95" stop-color="#FFA000" />
          <stop offset="1" stop-color="#FF9100" />
        </linearGradient>
        <linearGradient id="paint13_linear_136_2508" x1="18.2192" y1="11.8738" x2="14.5203" y2="21.8057"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#FF8E00" />
          <stop offset="0.04" stop-color="#FF8E00" stop-opacity="0.86" />
          <stop offset="0.08" stop-color="#FF8E00" stop-opacity="0.73" />
          <stop offset="0.13" stop-color="#FF8E00" stop-opacity="0.63" />
          <stop offset="0.18" stop-color="#FF8E00" stop-opacity="0.56" />
          <stop offset="0.23" stop-color="#FF8E00" stop-opacity="0.51" />
          <stop offset="0.28" stop-color="#FF8E00" stop-opacity="0.5" />
          <stop offset="0.39" stop-color="#FF8E00" stop-opacity="0.48" />
          <stop offset="0.52" stop-color="#FF8E00" stop-opacity="0.42" />
          <stop offset="0.68" stop-color="#FF8E00" stop-opacity="0.31" />
          <stop offset="0.84" stop-color="#FF8E00" stop-opacity="0.17" />
          <stop offset="1" stop-color="#FF8E00" stop-opacity="0" />
        </linearGradient>
      </defs>
    </svg>
    <div class="flex flex-col">
      <h2 class="font-medium">Firefox</h2>
      <p class="text-xs text-gray-500">Value</p>
    </div>
  </header>
  <svg class="w-full" viewBox="0 0 57 19" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M3.5 16.0771C2.22019 15.7164 0.957196 17.0165 0.500122 17.9182H56.4999V13.3571C55.9285 17.2646 54.0665 11.9405 53 12.9925C52.3075 9.71362 51.4641 15.308 49.7098 16.0771C49.2909 14.5241 46.202 11.5537 45.105 13.3571C43.7338 15.6115 41.3429 13.109 41.0001 12.2073C40.6573 11.3055 38.0905 10.0537 36.605 11.8571C35.1195 13.6606 35.4762 12.8724 34.105 12.8724C32.7338 12.8724 30.0009 7.39801 29.3153 6.1957C28.4025 4.59507 25.4284 14.9424 24.605 12.8724C23.3474 9.71093 26.1456 8.46015 20.5 1.46309C18.5598 -0.941537 18.6775 7.49359 14.0981 12.2073C10.314 16.1023 9.25324 9.60692 6.55636 15.8142C5.64221 17.9182 5.09976 16.528 3.5 16.0771Z"
      fill="url(#paint0_linear_136_2526)" />
    <path
      d="M0.500122 17.9182C0.957196 17.0165 2.22019 15.7164 3.5 16.0771C5.09976 16.528 5.64221 17.9182 6.55636 15.8142C9.25324 9.60692 10.314 16.1023 14.0981 12.2073C18.6775 7.49359 18.5598 -0.941537 20.5 1.46309C26.1456 8.46015 23.3474 9.71093 24.605 12.8724C25.4284 14.9424 28.4025 4.59507 29.3153 6.1957C30.0009 7.39801 32.7338 12.8724 34.105 12.8724C35.4762 12.8724 35.1195 13.6606 36.605 11.8571C38.0905 10.0537 40.6573 11.3055 41.0001 12.2073C41.3429 13.109 43.7338 15.6115 45.105 13.3571C46.202 11.5537 49.2909 14.5241 49.7098 16.0771C51.4641 15.308 52.3075 9.71362 53 12.9925C54.0665 11.9405 55.9285 17.2646 56.4999 13.3571"
      stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
    <defs>
      <linearGradient id="paint0_linear_136_2526" x1="28.5" y1="1.04053" x2="28.5" y2="17.9182"
        gradientUnits="userSpaceOnUse">
        <stop stop-color="#2D81FF" stop-opacity="0.48" />
        <stop offset="1" stop-color="#1849eb12" stop-opacity="0.1" />
      </linearGradient>
    </defs>
  </svg>
  <div class="flex flex-col items-center gap-0.5">
    <h2 class="font-bold">€ 741.00</h2>
    <span class="text-xs px-1 h-5 flex items-center justify-center gap-1 font-medium rounded-md bg-green-200 text-green-800 dark:bg-green-500/30 dark:text-green-400">
      <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17l9.2-9.2M17 17V7H7"/></svg>
      <span class="text-[11px]">2.15%</span>
    </span>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex items-center justify-between gap-5 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <header class="flex items-center gap-2 flex-none">
    <svg width="40" height="40" viewBox="0 0 26 25" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M13.0002 19.3229C16.7801 19.3229 19.8443 16.2586 19.8443 12.4786C19.8443 8.69862 16.7801 5.63428 13.0002 5.63428C9.22019 5.63428 6.15594 8.69862 6.15594 12.4786C6.15594 16.2586 9.22019 19.3229 13.0002 19.3229Z"
        fill="white" />
      <path
        d="M4.14842 9.11566C3.63785 8.23128 3.03773 7.30308 2.34794 6.33105C1.26817 8.20085 0.699683 10.322 0.699646 12.4812C0.699609 14.6403 1.26802 16.7615 2.34773 18.6313C3.42745 20.5011 4.9804 22.0538 6.85047 23.1331C8.72053 24.2124 10.8418 24.7804 13.001 24.7799C14.133 23.1921 14.9018 22.0471 15.3069 21.3454C16.0852 19.9973 17.0917 18.0673 18.3266 15.5554V15.554C17.7871 16.4893 17.0109 17.2661 16.0759 17.8063C15.141 18.3464 14.0803 18.6309 13.0005 18.631C11.9208 18.6312 10.86 18.3471 9.92489 17.8072C8.98978 17.2673 8.21331 16.4908 7.67354 15.5556C5.99636 12.4278 4.82138 10.2811 4.14842 9.11566Z"
        fill="#229342" />
      <path
        d="M13.0007 24.7796C14.616 24.7799 16.2156 24.4619 17.708 23.8438C19.2004 23.2257 20.5565 22.3197 21.6987 21.1775C22.8408 20.0352 23.7468 18.6791 24.3648 17.1867C24.9828 15.6942 25.3007 14.0946 25.3003 12.4793C25.2999 10.3201 24.7311 8.19902 23.651 6.32937C21.3209 6.0997 19.6012 5.98486 18.492 5.98486C17.2342 5.98486 15.4035 6.0997 12.9998 6.32937L12.9985 6.33033C14.0783 6.32983 15.1391 6.61364 16.0744 7.15323C17.0097 7.69282 17.7864 8.46917 18.3265 9.40419C18.8665 10.3392 19.1508 11.4 19.1508 12.4798C19.1508 13.5596 18.8664 14.6203 18.3264 15.5554L13.0007 24.7796Z"
        fill="#FBC116" />
      <path
        d="M13.0002 17.3493C15.6894 17.3493 17.8694 15.1694 17.8694 12.4801C17.8694 9.79071 15.6894 7.61084 13.0001 7.61084C10.311 7.61084 8.13098 9.7909 8.13098 12.4801C8.13098 15.1693 10.311 17.3493 13.0002 17.3493Z"
        fill="#1A73E8" />
      <path
        d="M13.0002 6.32934H23.6513C22.572 4.45925 21.0194 2.90628 19.1495 1.82659C17.2796 0.746909 15.1584 0.178565 12.9992 0.178711C10.84 0.178857 8.71895 0.747488 6.84922 1.82743C4.9795 2.90737 3.42707 4.46054 2.34802 6.33078L7.67362 15.5551L7.67507 15.5559C7.13476 14.621 6.85014 13.5604 6.84982 12.4806C6.84951 11.4008 7.1335 10.34 7.67326 9.40479C8.21301 8.4696 8.98949 7.69301 9.9246 7.15312C10.8597 6.61323 11.9205 6.32908 13.0003 6.32924L13.0001 6.32934H13.0002Z"
        fill="#E33B2E" />
    </svg>
    <div class="flex flex-col">
      <h2 class="font-medium">Chrome</h2>
      <p class="text-xs text-gray-500">Value</p>
    </div>
  </header>
  <svg class="w-full" viewBox="0 0 57 18" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M4.45892 9.49295C3.17912 9.13225 1.20762 8.20681 0.750549 9.10855V17.9224H56.2495V11.5479C55.6781 15.4554 55.3158 5.35599 54.2493 6.40801C53.5568 3.12914 51.2132 14.9983 49.4589 15.7674C49.0399 14.2144 44.7682 2.88023 43.6713 4.6837C42.3 6.93803 41.092 12.7993 40.7492 11.8976C40.4064 10.9958 36.8396 8.17471 35.3541 9.97817C33.8686 11.7816 30.4356 13.1901 29.0644 13.1901C27.6932 13.1901 29.75 7.08832 29.0644 5.88601C28.1516 4.28538 27.3235 3.4783 26.5001 1.40834C25.2424 -1.75312 23.8349 16.49 18.1894 9.49295C16.2492 7.08832 17.1212 4.81822 12.5418 9.53189C8.75768 13.427 7.69695 6.93155 5.00006 13.1388C4.08591 15.2429 6.05868 9.94382 4.45892 9.49295Z"
      fill="url(#paint0_linear_136_1894)" />
    <path
      d="M0.750549 9.10855C1.20762 8.20681 3.17912 9.13225 4.45892 9.49295C6.05868 9.94382 4.08591 15.2429 5.00006 13.1388C7.69694 6.93155 8.75768 13.427 12.5418 9.53189C17.1212 4.81822 16.2492 7.08832 18.1894 9.49295C23.8349 16.49 25.2424 -1.75312 26.5001 1.40834C27.3235 3.4783 28.1516 4.28538 29.0644 5.88601C29.75 7.08832 27.6932 13.1901 29.0644 13.1901C30.4356 13.1901 33.8686 11.7816 35.3541 9.97817C36.8396 8.17471 40.4064 10.9958 40.7492 11.8976C41.092 12.7993 42.3 6.93803 43.6713 4.6837C44.7683 2.88023 49.0399 14.2144 49.4589 15.7674C51.2132 14.9983 53.5568 3.12914 54.2493 6.40801C55.3158 5.35599 55.6781 15.4554 56.2495 11.5479"
      stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
    <defs>
      <linearGradient id="paint0_linear_136_1894" x1="28.5" y1="1.03662" x2="28.5" y2="17.9224"
        gradientUnits="userSpaceOnUse">
        <stop stop-color="#2D81FF" stop-opacity="0.54" />
        <stop offset="1" stop-color="#1849eb12" stop-opacity="0" />
      </linearGradient>
    </defs>
  </svg>
  <div class="flex flex-col items-center gap-0.5">
    <h2 class="font-bold">€ 165.60</h2>
    <span class="text-xs px-1 h-5 flex items-center justify-center gap-1 font-medium rounded-md bg-green-200 text-green-800 dark:bg-green-500/30 dark:text-green-400">
      <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17l9.2-9.2M17 17V7H7"/></svg>
      <span class="text-[11px]">82.15%</span>
    </span>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex items-center justify-between gap-5 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <header class="flex items-center gap-2 flex-none">
    <svg width="40" height="40" viewBox="0 0 24 25" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M21.6556 18.3337C21.3369 18.5024 21.0088 18.6523 20.6713 18.7742C19.5932 19.1772 18.4588 19.3833 17.3058 19.3833C12.8715 19.3833 9.00913 16.3374 9.00913 12.4199C9.01851 11.3515 9.60911 10.3674 10.5466 9.86133C6.53421 10.03 5.50299 14.21 5.50299 16.6561C5.50299 23.582 11.8872 24.2849 13.2653 24.2849C14.0059 24.2849 15.1214 24.0694 15.7964 23.8538L15.9183 23.8163C18.5057 22.926 20.6994 21.1828 22.1618 18.8679C22.2743 18.6898 22.2181 18.4649 22.0494 18.3524C21.9275 18.2774 21.7775 18.2681 21.6556 18.3337Z"
        fill="url(#paint0_linear_134_1843)" />
      <path opacity="0.35"
        d="M21.6556 18.3337C21.3369 18.5024 21.0088 18.6523 20.6713 18.7742C19.5932 19.1772 18.4588 19.3833 17.3058 19.3833C12.8715 19.3833 9.00913 16.3374 9.00913 12.4199C9.01851 11.3515 9.60911 10.3674 10.5466 9.86133C6.53421 10.03 5.50299 14.21 5.50299 16.6561C5.50299 23.582 11.8872 24.2849 13.2653 24.2849C14.0059 24.2849 15.1214 24.0694 15.7964 23.8538L15.9183 23.8163C18.5057 22.926 20.6994 21.1828 22.1618 18.8679C22.2743 18.6898 22.2181 18.4649 22.0494 18.3524C21.9275 18.2774 21.7775 18.2681 21.6556 18.3337Z"
        fill="url(#paint1_radial_134_1843)" />
      <path
        d="M9.90906 23.1041C9.07471 22.5887 8.35286 21.9045 7.781 21.1079C5.31545 17.734 6.05606 13.0011 9.43095 10.5362C9.78719 10.2832 10.1528 10.0489 10.5465 9.86142C10.8372 9.72083 11.334 9.47716 11.9996 9.48653C12.9465 9.49591 13.8371 9.94576 14.4089 10.7049C14.7839 11.211 14.9995 11.8202 15.0089 12.4575C15.0089 12.4387 17.3057 4.99731 7.50913 4.99731C3.39364 4.99731 0.00936776 8.90547 0.00936776 12.3263C-0.00938166 14.1351 0.384356 15.9345 1.14371 17.5746C3.73113 23.0854 10.0309 25.7846 15.8058 23.8633C13.8277 24.4818 11.6715 24.21 9.90906 23.1041Z"
        fill="url(#paint2_linear_134_1843)" />
      <path opacity="0.41"
        d="M9.90906 23.1041C9.07471 22.5887 8.35286 21.9045 7.781 21.1079C5.31545 17.734 6.05606 13.0011 9.43095 10.5362C9.78719 10.2832 10.1528 10.0489 10.5465 9.86142C10.8372 9.72083 11.334 9.47716 11.9996 9.48653C12.9465 9.49591 13.8371 9.94576 14.4089 10.7049C14.7839 11.211 14.9995 11.8202 15.0089 12.4575C15.0089 12.4387 17.3057 4.99731 7.50913 4.99731C3.39364 4.99731 0.00936776 8.90547 0.00936776 12.3263C-0.00938166 14.1351 0.384356 15.9345 1.14371 17.5746C3.73113 23.0854 10.0309 25.7846 15.8058 23.8633C13.8277 24.4818 11.6715 24.21 9.90906 23.1041Z"
        fill="url(#paint3_radial_134_1843)" />
      <path
        d="M14.2777 14.4347C14.2027 14.5285 13.9683 14.669 13.9683 14.9689C13.9683 15.2126 14.1277 15.4469 14.4089 15.6437C15.7589 16.5809 18.2994 16.4591 18.3088 16.4591C19.3119 16.4591 20.2869 16.1873 21.1493 15.6812C22.9118 14.6503 23.9993 12.7665 23.9993 10.7234C24.0274 8.62406 23.2493 7.22762 22.9399 6.60907C20.9525 2.71966 16.6589 0.479736 11.9996 0.479736C5.43733 0.479736 0.0937471 5.74684 0 12.3073C0.0468735 8.88648 3.44989 6.12172 7.49977 6.12172C7.82788 6.12172 9.70282 6.14984 11.4371 7.0683C12.9652 7.8743 13.7714 8.83962 14.3246 9.80494C14.9058 10.8078 15.0089 12.0636 15.0089 12.5697C15.0089 13.0664 14.7558 13.8162 14.2777 14.4347Z"
        fill="url(#paint4_radial_134_1843)" />
      <path
        d="M14.2777 14.4347C14.2027 14.5285 13.9683 14.669 13.9683 14.9689C13.9683 15.2126 14.1277 15.4469 14.4089 15.6437C15.7589 16.5809 18.2994 16.4591 18.3088 16.4591C19.3119 16.4591 20.2869 16.1873 21.1493 15.6812C22.9118 14.6503 23.9993 12.7665 23.9993 10.7234C24.0274 8.62406 23.2493 7.22762 22.9399 6.60907C20.9525 2.71966 16.6589 0.479736 11.9996 0.479736C5.43733 0.479736 0.0937471 5.74684 0 12.3073C0.0468735 8.88648 3.44989 6.12172 7.49977 6.12172C7.82788 6.12172 9.70282 6.14984 11.4371 7.0683C12.9652 7.8743 13.7714 8.83962 14.3246 9.80494C14.9058 10.8078 15.0089 12.0636 15.0089 12.5697C15.0089 13.0664 14.7558 13.8162 14.2777 14.4347Z"
        fill="url(#paint5_radial_134_1843)" />
      <defs>
        <linearGradient id="paint0_linear_134_1843" x1="5.50337" y1="17.0703" x2="22.2169" y2="17.0703"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#0C59A4" />
          <stop offset="1" stop-color="#114A8B" />
        </linearGradient>
        <radialGradient id="paint1_radial_134_1843" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(14.7363 17.2031) scale(8.9407 8.49033)">
          <stop offset="0.72" stop-opacity="0" />
          <stop offset="0.95" stop-opacity="0.53" />
          <stop offset="1" />
        </radialGradient>
        <linearGradient id="paint2_linear_134_1843" x1="14.3218" y1="9.82824" x2="3.88413" y2="21.2006"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#1B9DE2" />
          <stop offset="0.16" stop-color="#1595DF" />
          <stop offset="0.67" stop-color="#0680D7" />
          <stop offset="1" stop-color="#0078D4" />
        </linearGradient>
        <radialGradient id="paint3_radial_134_1843" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(6.61934 19.1313) rotate(-81.3802) scale(13.4394 10.8628)">
          <stop offset="0.76" stop-opacity="0" />
          <stop offset="0.95" stop-opacity="0.5" />
          <stop offset="1" />
        </radialGradient>
        <radialGradient id="paint4_radial_134_1843" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(2.42351 4.92142) rotate(92.2917) scale(18.9833 40.4479)">
          <stop stop-color="#35C1F1" />
          <stop offset="0.11" stop-color="#34C1ED" />
          <stop offset="0.23" stop-color="#2FC2DF" />
          <stop offset="0.31" stop-color="#2BC3D2" />
          <stop offset="0.67" stop-color="#36C752" />
        </radialGradient>
        <radialGradient id="paint5_radial_134_1843" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
          gradientTransform="translate(22.505 7.73425) rotate(73.7322) scale(9.12122 7.42057)">
          <stop stop-color="#66EB6E" />
          <stop offset="1" stop-color="#66EB6E" stop-opacity="0" />
        </radialGradient>
      </defs>
    </svg>
    <div class="flex flex-col">
      <h2 class="font-medium">Edge</h2>
      <p class="text-xs text-gray-500">Value</p>
    </div>
  </header>
  <svg class="w-full" viewBox="0 0 61 17" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M5.60486 7.93025C4.32505 7.56955 1.85222 15.1441 1.39514 16.0459H59.6048V3.72215C59.0335 7.62967 56.5107 1.31753 55.4442 2.36955C54.7517 -0.909323 52.3591 13.4356 50.6049 14.2047C50.1859 12.6517 45.9142 1.31753 44.8172 3.121C43.446 5.37533 42.2379 11.2366 41.8951 10.3349C41.5523 9.43313 40.5904 -0.674871 39.1049 1.1286C37.6194 2.93207 31.5815 11.6274 30.2103 11.6274C28.8391 11.6274 30.8959 5.52562 30.2103 4.32331C29.2976 2.72268 25.2186 6.39327 24.3951 4.32331C23.1375 1.16185 24.9809 14.9273 19.3353 7.93025C17.3951 5.52562 19.5725 5.6212 14.9931 10.3349C11.209 14.2299 10.1483 7.73453 7.45138 13.9418C6.53723 16.0459 7.20462 8.38111 5.60486 7.93025Z"
      fill="url(#paint0_linear_136_1890)" />
    <path
      d="M1.39514 16.0459C1.85222 15.1441 4.32505 7.56955 5.60486 7.93025C7.20462 8.38111 6.53723 16.0459 7.45138 13.9418C10.1483 7.73453 11.209 14.2299 14.9931 10.3349C19.5725 5.6212 17.3951 5.52562 19.3353 7.93025C24.9809 14.9273 23.1375 1.16185 24.3951 4.32331C25.2186 6.39327 29.2976 2.72268 30.2103 4.32331C30.8959 5.52562 28.8391 11.6274 30.2103 11.6274C31.5815 11.6274 37.6194 2.93207 39.1049 1.1286C40.5904 -0.674871 41.5523 9.43313 41.8951 10.3349C42.2379 11.2366 43.446 5.37533 44.8172 3.121C45.9142 1.31753 50.1859 12.6517 50.6049 14.2047C52.3591 13.4356 54.7517 -0.909323 55.4442 2.36955C56.5107 1.31753 59.0335 7.62967 59.6048 3.72215"
      stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
    <defs>
      <linearGradient id="paint0_linear_136_1890" x1="30.5" y1="0.913574" x2="30.5" y2="16.5"
        gradientUnits="userSpaceOnUse">
        <stop stop-color="#2D81FF" stop-opacity="0.51" />
        <stop offset="1" stop-color="#1849eb12" stop-opacity="0" />
      </linearGradient>
    </defs>
  </svg>
  <div class="flex flex-col items-center gap-0.5">
    <h2 class="font-bold">€ 345.00</h2>
    <span class="text-xs px-1 h-5 flex items-center justify-center gap-1 font-medium rounded-md bg-green-200 text-green-800 dark:bg-green-500/30 dark:text-green-400">
      <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17l9.2-9.2M17 17V7H7"/></svg>
      <span class="text-[11px]">71.06%</span>
    </span>
  </div>
</article>

<article class="border shadow-sm break-inside overflow-hidden relative flex items-center justify-between gap-5 rounded-xl text-sm mb-3 p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
  <div class="absolute w-14 h-14 bg-rose-500 rounded-full -top-8 left-1/2 blur-3xl"></div>
  <header class="flex items-center gap-2 flex-none">
    <svg width="40" height="40" viewBox="0 0 26 25" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M8.95428 19.4079C7.58969 17.8031 6.71519 15.4295 6.65754 12.7675V12.191C6.71519 9.52904 7.5993 7.15542 8.95428 5.55059C10.7225 3.26346 13.3171 2.23521 16.2481 2.23521C18.0548 2.23521 19.7557 2.36013 21.1972 3.32111C19.035 1.37033 16.1808 0.188321 13.048 0.178711H13C6.20588 0.178711 0.699463 5.68512 0.699463 12.4792C0.699463 19.0716 5.88875 24.4627 12.4138 24.7702C12.606 24.7798 12.8078 24.7798 13 24.7798C16.152 24.7798 19.0253 23.5978 21.1972 21.647C19.7557 22.608 18.1509 22.6464 16.3442 22.6464C13.4228 22.656 10.7129 21.7047 8.95428 19.4079Z"
        fill="url(#paint0_linear_134_1880)" />
      <path
        d="M8.95428 5.55055C10.0786 4.21479 11.5393 3.41718 13.1345 3.41718C16.719 3.41718 19.6212 7.47251 19.6212 12.4888C19.6212 17.5051 16.719 21.5605 13.1345 21.5605C11.5393 21.5605 10.0882 20.7532 8.95428 19.4271C10.7225 21.7142 13.346 23.1749 16.2673 23.1749C18.0644 23.1749 19.7557 22.6272 21.1972 21.6662C23.7149 19.3983 25.3005 16.1213 25.3005 12.4792C25.3005 8.8371 23.7149 5.56016 21.1972 3.31147C19.7557 2.35049 18.074 1.80273 16.2673 1.80273C13.3364 1.80273 10.7129 3.25381 8.95428 5.55055Z"
        fill="url(#paint1_linear_134_1880)" />
      <defs>
        <linearGradient id="paint0_linear_134_1880" x1="1025.65" y1="40.2785" x2="1025.65" y2="2424.49"
          gradientUnits="userSpaceOnUse">
          <stop offset="0.3" stop-color="#FF1B2D" />
          <stop offset="0.4381" stop-color="#FA1A2C" />
          <stop offset="0.5939" stop-color="#ED1528" />
          <stop offset="0.7581" stop-color="#D60E21" />
          <stop offset="0.9272" stop-color="#B70519" />
          <stop offset="1" stop-color="#A70014" />
        </linearGradient>
        <linearGradient id="paint1_linear_134_1880" x1="826.104" y1="20.0332" x2="826.104" y2="2128.74"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#9C0000" />
          <stop offset="0.7" stop-color="#FF4B4B" />
        </linearGradient>
      </defs>
    </svg>
    <div class="flex flex-col">
      <h2 class="font-medium">Opera</h2>
      <p class="text-xs text-gray-500">Value</p>
    </div>
  </header>
  <svg class="w-full" viewBox="0 0 61 17" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path
      d="M5.60486 7.93025C4.32505 7.56955 1.85222 15.1441 1.39514 16.0459H59.6048V3.72215C59.0335 7.62967 56.5107 1.31753 55.4442 2.36955C54.7517 -0.909323 52.3591 13.4356 50.6049 14.2047C50.1859 12.6517 45.9142 1.31753 44.8172 3.121C43.446 5.37533 42.2379 11.2366 41.8951 10.3349C41.5523 9.43313 40.5904 -0.674871 39.1049 1.1286C37.6194 2.93207 31.5815 11.6274 30.2103 11.6274C28.8391 11.6274 30.8959 5.52562 30.2103 4.32331C29.2976 2.72268 25.2186 6.39327 24.3951 4.32331C23.1375 1.16185 24.9809 14.9273 19.3353 7.93025C17.3951 5.52562 19.5725 5.6212 14.9931 10.3349C11.209 14.2299 10.1483 7.73453 7.45138 13.9418C6.53723 16.0459 7.20462 8.38111 5.60486 7.93025Z"
      fill="url(#paint0_linear_136_1897)" />
    <path
      d="M1.39514 16.0459C1.85222 15.1441 4.32505 7.56955 5.60486 7.93025C7.20462 8.38111 6.53723 16.0459 7.45138 13.9418C10.1483 7.73453 11.209 14.2299 14.9931 10.3349C19.5725 5.6212 17.3951 5.52562 19.3353 7.93025C24.9809 14.9273 23.1375 1.16185 24.3951 4.32331C25.2186 6.39327 29.2976 2.72268 30.2103 4.32331C30.8959 5.52562 28.8391 11.6274 30.2103 11.6274C31.5815 11.6274 37.6194 2.93207 39.1049 1.1286C40.5904 -0.674871 41.5523 9.43313 41.8951 10.3349C42.2379 11.2366 43.446 5.37533 44.8172 3.121C45.9142 1.31753 50.1859 12.6517 50.6049 14.2047C52.3591 13.4356 54.7517 -0.909323 55.4442 2.36955C56.5107 1.31753 59.0335 7.62967 59.6048 3.72215"
      stroke="#ED1261" stroke-linecap="round" stroke-linejoin="round" />
    <defs>
      <linearGradient id="paint0_linear_136_1897" x1="30.5" y1="0.913574" x2="30.5" y2="16.0459"
        gradientUnits="userSpaceOnUse">
        <stop stop-color="#ED1261" stop-opacity="0.54" />
        <stop offset="1" stop-color="#ff005417" stop-opacity="0" />
      </linearGradient>
    </defs>
  </svg>
  <div class="flex flex-col items-center gap-0.5">
    <h2 class="font-bold">€ 345.00</h2>
    <span class="text-xs px-1 h-5 flex items-center justify-center gap-1 font-medium rounded-md bg-rose-200 text-rose-800 dark:bg-rose-500/30 dark:text-rose-400">
      <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M7 17l9.2-9.2M17 17V7H7"/></svg>
      <span class="text-[11px]">71.06%</span>
    </span>
  </div>
</article>

<section class="grid grid-cols-3 gap-3 mb-3">
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <header class="flex flex-col items-center text-center gap-1 flex-none">
      <svg class="w-10 h-10" viewBox="0 0 256 256" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid">
        <defs>
          <linearGradient x1="49.9733228%" y1="-0.0235524798%" x2="49.9733228%" y2="99.9898856%" id="linearGradient-1">
            <stop stop-color="#F9AA4B" offset="0%"> </stop>
            <stop stop-color="#F7931A" offset="100%"> </stop>
          </linearGradient>
        </defs>
        <g>
          <path
            d="M252.171181,158.953845 C235.068666,227.562366 165.558445,269.267547 97.0483714,252.165422 C28.4382829,235.063298 -13.2678496,165.554665 3.83466519,97.0461553 C20.93718,28.4376335 90.3473861,-13.2675466 158.957475,3.83457763 C227.467548,20.8366894 269.273696,90.345323 252.171181,158.953845 L252.171181,158.953845 L252.171181,158.953845 Z"
            fill="url(#linearGradient-1)">
          </path>
          <path
            d="M188.944877,112.05 C191.444877,95.05 178.544877,85.85 160.744877,79.75 L166.544877,56.65 L152.544877,53.15 L146.944877,75.65 C143.244877,74.75 139.444877,73.85 135.644877,73.05 L141.244877,50.45 L127.244877,46.95 L121.544877,69.95 C118.444877,69.25 115.444877,68.55 112.544877,67.85 L112.544877,67.75 L93.1448775,62.95 L89.4448775,77.95 C89.4448775,77.95 99.8448775,80.35 99.6448775,80.45 C105.344877,81.85 106.344877,85.65 106.144877,88.65 L99.5448775,114.95 C99.9448775,115.05 100.444877,115.15 101.044877,115.45 C100.544877,115.35 100.044877,115.25 99.5448775,115.05 L90.3448775,151.85 C89.6448775,153.55 87.8448775,156.15 83.9448775,155.15 C84.0448775,155.35 73.7448775,152.65 73.7448775,152.65 L66.7448775,168.75 L85.0448775,173.35 C88.4448775,174.25 91.7448775,175.05 95.0448775,175.95 L89.2448775,199.25 L103.244877,202.75 L109.044877,179.65 C112.844877,180.65 116.644877,181.65 120.244877,182.55 L114.544877,205.55 L128.544877,209.05 L134.344877,185.75 C158.344877,190.25 176.344877,188.45 183.844877,166.75 C189.944877,149.35 183.544877,139.25 170.944877,132.65 C180.244877,130.55 187.144877,124.45 188.944877,112.05 L188.944877,112.05 L188.944877,112.05 Z M156.844877,157.05 C152.544877,174.45 123.144877,165.05 113.644877,162.65 L121.344877,131.75 C130.844877,134.15 161.444877,138.85 156.844877,157.05 L156.844877,157.05 Z M161.244877,111.75 C157.244877,127.65 132.844877,119.55 124.944877,117.55 L131.944877,89.55 C139.844877,91.55 165.344877,95.25 161.244877,111.75 L161.244877,111.75 Z"
            fill="#FFFFFF">
          </path>
        </g>
      </svg>
      <h2 class="font-medium">Bitcoins</h2>
    </header>
    <section>
      <svg class="w-full" viewBox="0 0 57 19" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M3.5 16.0771C2.22019 15.7164 0.957196 17.0165 0.500122 17.9182H56.4999V13.3571C55.9285 17.2646 54.0665 11.9405 53 12.9925C52.3075 9.71362 51.4641 15.308 49.7098 16.0771C49.2909 14.5241 46.202 11.5537 45.105 13.3571C43.7338 15.6115 41.3429 13.109 41.0001 12.2073C40.6573 11.3055 38.0905 10.0537 36.605 11.8571C35.1195 13.6606 35.4762 12.8724 34.105 12.8724C32.7338 12.8724 30.0009 7.39801 29.3153 6.1957C28.4025 4.59507 25.4284 14.9424 24.605 12.8724C23.3474 9.71093 26.1456 8.46015 20.5 1.46309C18.5598 -0.941537 18.6775 7.49359 14.0981 12.2073C10.314 16.1023 9.25324 9.60692 6.55636 15.8142C5.64221 17.9182 5.09976 16.528 3.5 16.0771Z"
          fill="url(#paint0_linear_136_2526)" />
        <path
          d="M0.500122 17.9182C0.957196 17.0165 2.22019 15.7164 3.5 16.0771C5.09976 16.528 5.64221 17.9182 6.55636 15.8142C9.25324 9.60692 10.314 16.1023 14.0981 12.2073C18.6775 7.49359 18.5598 -0.941537 20.5 1.46309C26.1456 8.46015 23.3474 9.71093 24.605 12.8724C25.4284 14.9424 28.4025 4.59507 29.3153 6.1957C30.0009 7.39801 32.7338 12.8724 34.105 12.8724C35.4762 12.8724 35.1195 13.6606 36.605 11.8571C38.0905 10.0537 40.6573 11.3055 41.0001 12.2073C41.3429 13.109 43.7338 15.6115 45.105 13.3571C46.202 11.5537 49.2909 14.5241 49.7098 16.0771C51.4641 15.308 52.3075 9.71362 53 12.9925C54.0665 11.9405 55.9285 17.2646 56.4999 13.3571"
          stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
        <defs>
          <linearGradient id="paint0_linear_136_2526" x1="28.5" y1="1.04053" x2="28.5" y2="17.9182"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#2D81FF" stop-opacity="0.48" />
            <stop offset="1" stop-color="#0043ff0f" stop-opacity="0.1" />
          </linearGradient>
        </defs>
      </svg>
    </section>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <header class="flex flex-col items-center text-center gap-1 flex-none">
      <svg class="w-10 h-10" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg">
        <g fill="none" fill-rule="evenodd">
          <circle cx="16" cy="16" r="16" fill="#627EEA" />
          <g fill="#FFF" fill-rule="nonzero">
            <path fill-opacity=".602" d="M16.498 4v8.87l7.497 3.35z" />
            <path d="M16.498 4L9 16.22l7.498-3.35z" />
            <path fill-opacity=".602" d="M16.498 21.968v6.027L24 17.616z" />
            <path d="M16.498 27.995v-6.028L9 17.616z" />
            <path fill-opacity=".2" d="M16.498 20.573l7.497-4.353-7.497-3.348z" />
            <path fill-opacity=".602" d="M9 16.22l7.498 4.353v-7.701z" />
          </g>
        </g>
      </svg>
      <h2 class="font-medium">Ethereum</h2>
    </header>
    <section>
      <svg class="w-full" viewBox="0 0 61 17" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M5.60486 7.93025C4.32505 7.56955 1.85222 15.1441 1.39514 16.0459H59.6048V3.72215C59.0335 7.62967 56.5107 1.31753 55.4442 2.36955C54.7517 -0.909323 52.3591 13.4356 50.6049 14.2047C50.1859 12.6517 45.9142 1.31753 44.8172 3.121C43.446 5.37533 42.2379 11.2366 41.8951 10.3349C41.5523 9.43313 40.5904 -0.674871 39.1049 1.1286C37.6194 2.93207 31.5815 11.6274 30.2103 11.6274C28.8391 11.6274 30.8959 5.52562 30.2103 4.32331C29.2976 2.72268 25.2186 6.39327 24.3951 4.32331C23.1375 1.16185 24.9809 14.9273 19.3353 7.93025C17.3951 5.52562 19.5725 5.6212 14.9931 10.3349C11.209 14.2299 10.1483 7.73453 7.45138 13.9418C6.53723 16.0459 7.20462 8.38111 5.60486 7.93025Z"
          fill="url(#paint0_linear_136_1890)" />
        <path
          d="M1.39514 16.0459C1.85222 15.1441 4.32505 7.56955 5.60486 7.93025C7.20462 8.38111 6.53723 16.0459 7.45138 13.9418C10.1483 7.73453 11.209 14.2299 14.9931 10.3349C19.5725 5.6212 17.3951 5.52562 19.3353 7.93025C24.9809 14.9273 23.1375 1.16185 24.3951 4.32331C25.2186 6.39327 29.2976 2.72268 30.2103 4.32331C30.8959 5.52562 28.8391 11.6274 30.2103 11.6274C31.5815 11.6274 37.6194 2.93207 39.1049 1.1286C40.5904 -0.674871 41.5523 9.43313 41.8951 10.3349C42.2379 11.2366 43.446 5.37533 44.8172 3.121C45.9142 1.31753 50.1859 12.6517 50.6049 14.2047C52.3591 13.4356 54.7517 -0.909323 55.4442 2.36955C56.5107 1.31753 59.0335 7.62967 59.6048 3.72215"
          stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
        <defs>
          <linearGradient id="paint0_linear_136_1890" x1="30.5" y1="0.913574" x2="30.5" y2="16.5"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#2D81FF" stop-opacity="0.51" />
            <stop offset="1" stop-color="#0043ff0f" stop-opacity="0" />
          </linearGradient>
        </defs>
      </svg>
    </section>
  </article>
  <article class="border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm p-3 bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <header class="flex flex-col items-center text-center gap-1 flex-none">
      <svg class="w-10 h-10" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg">
        <defs>
        <filter color-interpolation-filters="auto" id="a">
        <feColorMatrix in="SourceGraphic" values="0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 0 1.000000 0 0 0 1.000000 0"/>
        </filter>
        </defs>
        <g fill="none" fill-rule="evenodd">
        <circle fill="#5942CC" fill-rule="nonzero" cx="16" cy="16" r="16"/>
        <g filter="url(#a)">
        <path d="M20.707 19.543a1 1 0 010 1.414l-4 4a1 1 0 11-1.414-1.414l4-4a1 1 0 011.414 0zM15 7.25a6 6 0 110 12 6 6 0 010-12zm0 2a4 4 0 100 8 4 4 0 000-8zm7-2a1 1 0 110 2 1 1 0 010-2z" fill="#000000" fill-rule="nonzero"/>
        </g>
        </g>
      </svg>
      <h2 class="font-medium">Graph</h2>
    </header>
    <section>
      <svg class="w-full" viewBox="0 0 61 17" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M5.60486 7.93025C4.32505 7.56955 1.85222 15.1441 1.39514 16.0459H59.6048V3.72215C59.0335 7.62967 56.5107 1.31753 55.4442 2.36955C54.7517 -0.909323 52.3591 13.4356 50.6049 14.2047C50.1859 12.6517 45.9142 1.31753 44.8172 3.121C43.446 5.37533 42.2379 11.2366 41.8951 10.3349C41.5523 9.43313 40.5904 -0.674871 39.1049 1.1286C37.6194 2.93207 31.5815 11.6274 30.2103 11.6274C28.8391 11.6274 30.8959 5.52562 30.2103 4.32331C29.2976 2.72268 25.2186 6.39327 24.3951 4.32331C23.1375 1.16185 24.9809 14.9273 19.3353 7.93025C17.3951 5.52562 19.5725 5.6212 14.9931 10.3349C11.209 14.2299 10.1483 7.73453 7.45138 13.9418C6.53723 16.0459 7.20462 8.38111 5.60486 7.93025Z"
          fill="url(#paint0_linear_136_1897)" />
        <path
          d="M1.39514 16.0459C1.85222 15.1441 4.32505 7.56955 5.60486 7.93025C7.20462 8.38111 6.53723 16.0459 7.45138 13.9418C10.1483 7.73453 11.209 14.2299 14.9931 10.3349C19.5725 5.6212 17.3951 5.52562 19.3353 7.93025C24.9809 14.9273 23.1375 1.16185 24.3951 4.32331C25.2186 6.39327 29.2976 2.72268 30.2103 4.32331C30.8959 5.52562 28.8391 11.6274 30.2103 11.6274C31.5815 11.6274 37.6194 2.93207 39.1049 1.1286C40.5904 -0.674871 41.5523 9.43313 41.8951 10.3349C42.2379 11.2366 43.446 5.37533 44.8172 3.121C45.9142 1.31753 50.1859 12.6517 50.6049 14.2047C52.3591 13.4356 54.7517 -0.909323 55.4442 2.36955C56.5107 1.31753 59.0335 7.62967 59.6048 3.72215"
          stroke="#ED1261" stroke-linecap="round" stroke-linejoin="round" />
        <defs>
          <linearGradient id="paint0_linear_136_1897" x1="30.5" y1="0.913574" x2="30.5" y2="16.0459"
            gradientUnits="userSpaceOnUse">
            <stop stop-color="#ED1261" stop-opacity="0.54" />
            <stop offset="1" stop-color="#ff00a30f" stop-opacity="0" />
          </linearGradient>
        </defs>
      </svg>
    </section>
  </article>
</section>

<section class="grid grid-cols-2 gap-3 mb-3">
  <article class="group border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <header class="flex flex-col items-start px-3 pt-3 gap-2">
      <div class="flex items-center justify-between w-full">
        <svg width="36" height="36" viewBox="0 0 29 29" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="29" height="29" rx="14.5" fill="#10C643"/>
          <path d="M10.6334 10.3725C10.9748 9.92401 11.4881 9.62117 12.0623 9.52927C12.6365 9.43738 13.2258 9.56379 13.7028 9.88125C14.1799 10.1987 14.5066 10.6817 14.6124 11.2262C14.7182 11.7706 14.5947 12.3327 14.2684 12.7913L10.0262 18.5515C9.68661 19.0049 9.17237 19.3123 8.59549 19.4068C8.0186 19.5013 7.42581 19.3752 6.94627 19.056C6.46673 18.7368 6.13929 18.2504 6.0353 17.7027C5.93131 17.155 6.05919 16.5904 6.39108 16.132L10.6334 10.3725ZM16.9117 10.4343C17.2493 9.97604 17.7645 9.66401 18.3441 9.56689C18.9236 9.46977 19.52 9.59551 20.0021 9.91646C20.4841 10.2374 20.8123 10.7273 20.9145 11.2783C21.0166 11.8293 20.8844 12.3963 20.5468 12.8546L16.3045 18.6141C15.965 19.0675 15.4507 19.3749 14.8738 19.4694C14.297 19.5639 13.7042 19.4378 13.2246 19.1186C12.7451 18.7994 12.4177 18.313 12.3137 17.7653C12.2097 17.2176 12.3375 16.653 12.6694 16.1946L16.9117 10.4343ZM20.7812 19.3166C21.3697 19.3166 21.934 19.0943 22.3501 18.6987C22.7662 18.3031 23 17.7666 23 17.2071C23 16.6476 22.7662 16.1111 22.3501 15.7155C21.934 15.3199 21.3697 15.0976 20.7812 15.0976C20.1928 15.0976 19.6284 15.3199 19.2123 15.7155C18.7962 16.1111 18.5625 16.6476 18.5625 17.2071C18.5625 17.7666 18.7962 18.3031 19.2123 18.6987C19.6284 19.0943 20.1928 19.3166 20.7812 19.3166Z" fill="white"/>
        </svg>
        <svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2.5" width="18" height="18" class="text-current transition-transform duration-300 translate-y-1 -translate-x-1 group-hover:translate-x-0 group-hover:translate-y-0">
          <line class="fill-none stroke-current" x1="22" y1="2" x2="2" y2="22"></line>
          <polyline class="fill-none stroke-current" points="22 15.75 22 2 8.25 2"></polyline>
        </svg>
      </div>
      <div class="flex flex-col items-start">
        <h2 class="text-base font-bold">HubSpot</h2>
        <p class="text-xs text-gray-500">Las updates from HubSpot</p>
      </div>
    </header>
    <svg class="w-full" viewBox="0 0 96 36" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M96 1.94572C88.6165 -2.89 84.5392 12.3925 78.2605 12.3925C71.1686 12.3925 63.7091 6.04792 57.5672 8.03967C48.7597 10.8959 44.5128 21.6062 34.1005 20.1953C23.4441 18.7513 10.3968 21.6247 0 24V36H96V1.94572Z"
        fill="url(#paint0_linear_181_7869)" />
      <path
        d="M0 24C10.3968 21.6247 23.4441 18.7513 34.1005 20.1953C44.5128 21.6062 48.7597 10.8959 57.5672 8.03967C63.709 6.04792 71.1686 12.3925 78.2605 12.3925C84.5392 12.3925 88.6165 -2.89 96 1.94572"
        stroke="#10C643" stroke-linecap="round" />
      <defs>
        <linearGradient id="paint0_linear_181_7869" x1="48" y1="1" x2="48" y2="36"
          gradientUnits="userSpaceOnUse">
          <stop stop-color="#16FF73" stop-opacity="0.43" />
          <stop offset="1" stop-color="#08e80817" stop-opacity="0" />
        </linearGradient>
      </defs>
    </svg>
  </article>
  <article class="group border shadow-sm break-inside overflow-hidden relative flex flex-col gap-2 rounded-xl text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
    <header class="flex flex-col items-start px-3 pt-3 gap-2">
      <div class="flex items-center justify-between w-full">
        <svg width="36" height="36" viewBox="0 0 29 29" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="29" height="29" rx="14.5" fill="#F64282" />
          <path fill-rule="evenodd" clip-rule="evenodd"
            d="M14.5 6C9.808 6 6 9.808 6 14.5C6 19.192 9.808 23 14.5 23C19.1835 23 23 19.192 23 14.5C23 9.808 19.1835 6 14.5 6ZM20.1143 9.9185C21.1606 11.1927 21.7399 12.7864 21.7558 14.4352C21.5157 14.3895 19.1187 13.9008 16.7036 14.2046C16.6484 14.0856 16.6016 13.956 16.5464 13.8274C16.3987 13.4768 16.2329 13.1177 16.0672 12.7756C18.7404 11.6886 19.9581 10.1214 20.1153 9.91744L20.1143 9.9185ZM14.5 7.25375C16.3434 7.25375 18.0307 7.94438 19.3131 9.07912C19.1835 9.264 18.0859 10.7292 15.5051 11.6971C14.3151 9.51262 12.9976 7.72337 12.7947 7.44712C13.3537 7.3166 13.926 7.25171 14.5 7.25375ZM11.4113 7.93588C12.3842 9.28424 13.283 10.6846 14.1037 12.1306C10.7111 13.0338 7.71487 13.0157 7.39187 13.0157C7.62547 11.9168 8.10976 10.8867 8.80697 10.0057C9.50418 9.12475 10.3955 8.4157 11.4113 7.93588ZM7.23569 14.5106V14.2875C7.54912 14.2981 11.0713 14.3438 14.6944 13.2558C14.9059 13.6606 15.0992 14.0761 15.2841 14.4904L14.9973 14.5733C11.2551 15.7814 9.264 19.0815 9.09719 19.3588C7.8985 18.0281 7.23532 16.3005 7.23569 14.5096V14.5106ZM14.5 21.7643C12.8866 21.7668 11.3191 21.2281 10.0481 20.2343C10.1756 19.9666 11.6514 17.1276 15.7442 15.6985C15.7633 15.6889 15.7718 15.6889 15.7909 15.6804C16.4809 17.4616 16.9993 19.3045 17.339 21.1842C16.4422 21.5695 15.476 21.767 14.5 21.7643ZM18.5481 20.5201C18.4738 20.0771 18.0859 17.9574 17.1371 15.3479C19.4141 14.9888 21.4052 15.5784 21.6538 15.6613C21.499 16.6416 21.143 17.5793 20.6084 18.4155C20.0737 19.2517 19.3719 19.9682 18.5471 20.5201H18.5481Z"
            fill="white" />
        </svg>
        <svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2.5" width="18" height="18" class="text-current transition-transform duration-300 translate-y-1 -translate-x-1 group-hover:translate-x-0 group-hover:translate-y-0">
          <line class="fill-none stroke-current" x1="22" y1="2" x2="2" y2="22"></line>
          <polyline class="fill-none stroke-current" points="22 15.75 22 2 8.25 2"></polyline>
        </svg>
      </div>
      <div class="flex flex-col items-start">
        <h2 class="text-base font-bold">Dribbble</h2>
        <p class="text-xs text-gray-500">Las updates from Dribbble</p>
      </div>
    </header>
    <svg class="w-full" viewBox="0 0 96 35" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M0 22.9248C0.690421 23.2428 1.2633 23.7158 1.94134 24.0146C2.38781 24.2113 3.05733 24.1596 3.28427 24.63C3.55797 25.1974 3.94667 24.148 4.20971 23.9056C4.52829 23.6121 4.95594 22.8725 5.38564 22.9825C7.06035 23.4111 8.94068 23.2918 10.66 23.271C10.8447 23.2687 11.0218 23.1533 11.0218 23.3479C11.0218 23.3863 11.0272 23.4488 11.0255 23.5124C11.3036 23.3938 11.7249 23.2741 11.8011 23.271C12.7214 23.2333 12.9659 23.8577 13.7216 24.2326C14.2782 24.5087 14.2782 24.8276 14.2782 24.0787C14.2782 23.2089 14.7709 23.0256 15.2802 22.3478C15.4653 22.1015 15.6485 21.8301 15.9691 21.7644C16.3625 21.6839 16.6996 21.6629 17.1172 21.6426C19.0037 21.5511 20.8903 21.2492 22.7255 20.8477C23.6282 20.6502 24.5305 20.4258 25.4113 20.1553C25.6476 20.0828 25.6082 20.5318 25.6757 20.7067C25.7542 20.9099 26.1604 22.1811 26.302 22.1811C26.353 22.1811 26.302 22.0871 26.302 22.0401V21.3862C26.302 20.9829 26.3773 20.7298 26.6221 20.3861C26.8335 20.0892 28.1684 18.6481 28.3686 19.0783C28.5802 19.5332 28.5881 19.9153 28.9043 20.3348C28.982 20.4378 29.0464 20.7292 29.0644 20.4887C29.0929 20.1075 29.0299 19.1906 29.3705 18.9116C29.626 18.7024 31.023 21.9822 31.2562 22.4119C31.3076 22.5067 31.6643 23.2704 31.8407 23.0402C32.1933 22.5799 32.8688 22.2241 33.3228 21.8798C34.4138 21.0526 35.3802 20.1251 36.4262 19.2578C36.5064 19.1913 36.8464 19.2499 36.7462 19.2129C36.4007 19.0856 36.8496 18.4223 36.9132 18.2898C37.3919 17.2934 37.7031 16.2458 38.0474 15.2062C38.1892 14.7781 38.5414 14.2839 38.5762 13.8343C38.5896 13.6618 38.4765 13.1681 38.7015 13.1163C38.9627 13.0561 38.8079 12.2414 38.8337 12.0393C38.8726 11.7343 39.1751 12.4776 39.1886 12.5009C39.6104 13.2334 39.95 13.9822 40.3297 14.7318C40.4206 14.9113 40.6744 16.3603 40.9142 16.1743C41.5303 15.6962 41.9252 14.9787 42.5494 14.4882C43.2217 13.9598 43.4651 15.338 43.5931 15.7127C44.0028 16.9116 45.2773 20.4949 44.8664 19.2963C44.6805 18.7537 45.6555 17.8309 46.0633 17.5526C46.2035 17.4569 46.3564 17.5183 46.4599 17.6295C46.7558 17.9476 46.7742 17.6966 47.1487 17.4628C48.2273 16.7896 48.5579 19.832 49.2153 19.2642C49.3778 19.1239 49.4235 18.7997 49.6259 18.7065C49.9833 18.5418 50.4559 19.4824 50.5722 19.6681C50.6136 19.7342 50.948 20.3909 51.101 20.3028C51.3475 20.1608 51.398 20.0399 51.7272 20.0399C52.6205 20.0399 52.796 21.1019 53.0771 21.7708C53.3775 22.4857 53.789 22.9113 54.2739 23.5017C54.4601 23.7284 54.2323 23.294 54.3157 22.9376C54.5681 21.8586 55.334 21.0891 56.1526 20.3348C56.2502 20.2449 56.3383 20.0153 56.4866 20.0912C56.8465 20.2754 57.2706 18.3237 57.3077 18.168C57.3451 18.011 57.5795 15.8954 57.7669 15.905C58.3182 15.9332 58.7374 17.4404 58.915 17.7962C59.0712 18.1089 59.2312 18.4957 59.5204 18.0718C60.0521 17.2926 60.2572 16.1938 60.926 15.5139C61.2519 15.1826 61.4761 15.6983 61.6496 15.8858C61.9311 16.1899 62.2979 15.7749 62.5542 15.6293C63.2727 15.2213 64.5553 14.1692 65.1983 15.046C65.4445 15.3817 65.6389 15.8204 65.9776 16.0909C66.3237 16.3672 66.8874 15.1669 67.0213 15.0139C67.5342 14.4282 68.2563 14.0937 68.8305 13.5779C69.1197 13.3181 69.3286 12.9911 69.7072 12.8214C69.9066 12.732 70.0833 12.8586 70.1943 13.0073C70.5124 13.4337 71.1195 11.7619 71.231 11.5265C71.6489 10.6443 71.7504 11.5786 72.4279 11.1931C74.2118 10.1779 76.6941 10.0007 78.7529 10.0007C78.9015 10.0007 78.817 9.99221 78.7529 9.91094C78.5854 9.69884 79.0017 9.33634 79.1008 9.1673C79.3437 8.7526 79.4265 8.21661 79.6018 7.77617C79.6573 7.63657 79.7968 7.00046 80.0332 7.00046C80.443 7.00046 81.0571 8.4686 81.2021 8.71855C81.4402 9.12872 82.0371 10.4938 82.5938 10.6802C82.7084 10.7186 83.6099 7.62724 83.728 7.28895C83.8066 7.06362 84.0781 6.13816 84.4168 6.03885C84.5835 5.99 85.1352 6.91369 85.2379 7.03893C85.2429 7.04502 85.2477 7.05091 85.2523 7.05657C85.2273 7.01157 85.2049 6.95999 85.1962 6.91071C85.1369 6.5753 85.4412 6.27749 85.7389 6.1286C86.2928 5.85156 86.8788 6.64942 87.214 6.91712C87.604 7.22855 88.8823 7.59793 89.218 7.10304C89.9252 6.06057 89.6772 5.21909 89.6772 4.06434C89.6772 3.80371 90.3273 3.32457 90.554 3.21812C91.1654 2.93092 91.4126 3.41055 91.7368 3.84637C91.9436 4.12422 92.5547 5.32729 92.9754 5.39778C93.1673 5.42992 92.9168 5.03672 92.9476 4.85927C93.014 4.47695 93.315 4.18626 93.5529 3.88484C93.8623 3.49289 94.1444 2.97998 94.6175 2.7309C94.8258 2.62124 95.0448 2.11997 95.2855 1.94879C95.4748 1.81418 95.8045 1.6015 95.9396 1.37184V1C96.0283 1.12262 96.0115 1.24963 95.9396 1.37184V34.9024H0V22.9248Z"
        fill="url(#paint0_linear_181_7862)" />
      <path
        d="M0 22.9248C0.690421 23.2428 1.2633 23.7158 1.94134 24.0146C2.38781 24.2113 3.05733 24.1596 3.28427 24.63C3.55797 25.1974 3.94667 24.148 4.20971 23.9056C4.52829 23.6121 4.95594 22.8725 5.38564 22.9825C7.06035 23.4111 8.94068 23.2918 10.66 23.271C10.8447 23.2687 11.0218 23.1533 11.0218 23.3479C11.0218 23.4616 11.0688 23.7861 10.8409 23.7261C10.4923 23.6344 11.6687 23.2764 11.8011 23.271C12.7214 23.2333 12.9659 23.8577 13.7216 24.2326C14.2782 24.5087 14.2782 24.8276 14.2782 24.0787C14.2782 23.2089 14.7709 23.0256 15.2802 22.3478C15.4653 22.1015 15.6485 21.8301 15.9691 21.7644C16.3625 21.6839 16.6996 21.6629 17.1172 21.6426C19.0037 21.5511 20.8903 21.2492 22.7255 20.8477C23.6282 20.6502 24.5305 20.4258 25.4113 20.1553C25.6476 20.0828 25.6082 20.5318 25.6757 20.7067C25.7542 20.9099 26.1604 22.1811 26.302 22.1811C26.353 22.1811 26.302 22.0871 26.302 22.0401C26.302 21.8221 26.302 21.6042 26.302 21.3862C26.302 20.9829 26.3773 20.7298 26.6221 20.3861C26.8335 20.0892 28.1684 18.648 28.3686 19.0783C28.5802 19.5332 28.5881 19.9153 28.9043 20.3348C28.982 20.4378 29.0464 20.7292 29.0644 20.4887C29.0929 20.1075 29.0299 19.1906 29.3705 18.9116C29.626 18.7024 31.023 21.9822 31.2562 22.4119C31.3076 22.5067 31.6643 23.2704 31.8407 23.0402C32.1933 22.5799 32.8688 22.224 33.3228 21.8798C34.4138 21.0526 35.3802 20.1251 36.4262 19.2578C36.5064 19.1913 36.8464 19.2499 36.7462 19.2129C36.4007 19.0856 36.8496 18.4223 36.9132 18.2898C37.3919 17.2934 37.7031 16.2458 38.0474 15.2062C38.1892 14.7781 38.5414 14.2839 38.5762 13.8343C38.5896 13.6618 38.4765 13.1681 38.7015 13.1163C38.9627 13.0561 38.8079 12.2413 38.8337 12.0393C38.8726 11.7343 39.1751 12.4776 39.1886 12.5009C39.6104 13.2334 39.95 13.9822 40.3297 14.7318C40.4206 14.9113 40.6744 16.3603 40.9142 16.1742C41.5303 15.6962 41.9252 14.9787 42.5494 14.4882C43.2217 13.9598 43.4651 15.338 43.5931 15.7127C44.0028 16.9116 45.2773 20.4949 44.8664 19.2963C44.3483 17.7845 46.4906 17.8736 47.1487 17.4628C48.2273 16.7896 48.5579 19.832 49.2153 19.2642C49.3778 19.1239 49.4235 18.7997 49.6259 18.7065C49.9833 18.5418 50.4559 19.4824 50.5722 19.6681C50.6136 19.7342 50.948 20.3909 51.101 20.3028C51.3475 20.1608 51.398 20.0399 51.7272 20.0399C52.6205 20.0399 52.796 21.1019 53.0771 21.7708C53.3775 22.4857 53.789 22.9113 54.2739 23.5017C54.4601 23.7284 54.2323 23.294 54.3157 22.9376C54.5681 21.8586 55.334 21.0891 56.1526 20.3348C56.2502 20.2449 56.3383 20.0153 56.4866 20.0912C56.8465 20.2754 57.2706 18.3237 57.3077 18.168C57.3451 18.011 57.5795 15.8954 57.7669 15.905C58.3182 15.9332 58.7374 17.4404 58.915 17.7962C59.0712 18.1089 59.2312 18.4957 59.5204 18.0718C60.0521 17.2926 60.2572 16.1938 60.926 15.5139C60.9466 15.4929 65.0101 14.7894 65.1983 15.046C65.4445 15.3817 65.6389 15.8204 65.9776 16.0909C66.3237 16.3672 66.8874 15.1669 67.0213 15.0139C67.5342 14.4282 68.2563 14.0937 68.8305 13.5779C69.1197 13.3181 69.3286 12.9911 69.7072 12.8214C69.9066 12.732 70.0833 12.8586 70.1943 13.0073C70.5124 13.4337 71.1195 11.7619 71.231 11.5265C71.6489 10.6443 71.7504 11.5786 72.4279 11.1931C74.2119 10.1779 76.6941 10.0007 78.7529 10.0007C78.9015 10.0007 78.817 9.99221 78.7529 9.91094C78.5854 9.69884 79.0017 9.33634 79.1008 9.1673C79.3437 8.7526 79.4265 8.2166 79.6018 7.77616C79.6573 7.63657 79.7968 7.00046 80.0332 7.00046C80.443 7.00046 81.0571 8.4686 81.2021 8.71854C81.4402 9.12871 82.0371 10.4937 82.5938 10.6802C82.7084 10.7186 83.61 7.62724 83.728 7.28895C83.8066 7.06362 84.0781 6.13816 84.4168 6.03885C84.5835 5.99 85.1352 6.91369 85.2379 7.03893C85.4881 7.34402 85.2311 7.10867 85.1962 6.91071C85.1369 6.5753 85.4412 6.27749 85.7389 6.1286C86.2928 5.85156 86.8788 6.64942 87.214 6.91712C87.604 7.22855 88.8823 7.59792 89.218 7.10304C89.9252 6.06057 89.6772 5.21908 89.6772 4.06434C89.6772 3.80371 90.3273 3.32457 90.554 3.21812C91.1654 2.93092 91.4126 3.41055 91.7369 3.84637C91.9436 4.12422 92.5547 5.32729 92.9754 5.39778C93.1673 5.42992 92.9168 5.03672 92.9476 4.85927C93.014 4.47695 93.315 4.18626 93.5529 3.88484C93.8623 3.49289 94.1444 2.97998 94.6175 2.7309C94.8258 2.62124 95.0448 2.11997 95.2855 1.94879C95.5755 1.74256 96.1951 1.35306 95.9396 1"
        stroke="url(#paint1_linear_181_7862)" stroke-linecap="round" />
      <defs>
        <linearGradient id="paint0_linear_181_7862" x1="48" y1="-3.42775" x2="48" y2="34.9024"
          gradientUnits="userSpaceOnUse">
          <stop offset="0.144057" stop-color="#D60F63" stop-opacity="0.22" />
          <stop offset="0.983952" stop-color="white" stop-opacity="0" />
        </linearGradient>
        <linearGradient id="paint1_linear_181_7862" x1="94.5409" y1="2.97066" x2="4.92525" y2="33.212"
          gradientUnits="userSpaceOnUse">
          <stop offset="0.161546" stop-color="#D60F27" />
          <stop offset="1" stop-color="#EA0FBA" />
        </linearGradient>
      </defs>
    </svg>
  </article>
</section>

<article class="break-inside overflow-hidden relative flex items-center gap-2 rounded-xl text-sm mb-3 p-3 bg-gray-100 dark:text-white dark:bg-gray-900" data-filter="finance">
  <header class="flex items-center gap-3 flex-1 w-full">
    <span class="w-10 h-10 bg-blue-700 rounded-full flex items-center justify-center text-lg font-bold text-white">B</span>
    <div class="flex flex-col gap-0.5">
      <h3 class="text-sm font-semibold">International Bank</h3>
      <p class="text-xs text-gray-500">0,46 04Q &middot; 11,05 &euro; </p>
    </div>
  </header>
  <div class="flex flex-col items-end text-xs gap-0.5">
    <span class="font-medium">5,00 &euro;</span>
    <div class="flex items-center gap-0.5 text-xs">
      <svg data-icon="arrow-up" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2" width="16" height="16" class="text-green-500">
        <path fill="none" stroke="currentColor" d="M12,19V5"></path>
        <polyline fill="none" stroke="currentColor" points="5 12 12 5 19 12"></polyline>
      </svg>
      <span class="text-green-500">+ 0,46%</span>
    </div>
  </div>
</article>

<article class="break-inside overflow-hidden relative flex items-center gap-2 rounded-xl text-sm mb-3 p-3 bg-violet-200 dark:text-white dark:bg-violet-700/20" data-filter="finance">
  <header class="flex items-center gap-3 flex-1 w-full">
    <span class="w-10 h-10 bg-violet-700 rounded-full flex items-center justify-center text-lg font-bold text-white">A</span>
    <div class="flex flex-col gap-0.5">
      <h3 class="text-sm font-semibold">American Bank</h3>
      <p class="text-xs">0,16 04Q &middot; 88,00 &euro; </p>
    </div>
  </header>
  <div class="flex flex-col items-end text-xs gap-0.5">
    <span class="font-medium">5,00 &euro;</span>
    <div class="flex items-center gap-0.5 text-xs h-5 px-1 rounded bg-black/10 dark:bg-white/10">
      <svg data-icon="arrow-up" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke-width="2" width="16" height="16" class="text-violet-800 dark:text-violet-300">
        <path fill="none" stroke="currentColor" d="M12,19V5"></path>
        <polyline fill="none" stroke="currentColor" points="5 12 12 5 19 12"></polyline>
      </svg>
      <span class="text-violet-800 dark:text-violet-300">+ 0,46%</span>
    </div>
  </div>
</article>

<article class="break-inside flex items-center space-x-4 rounded overflow-hidden pr-4 mb-3 text-sm bg-purple-100 dark:bg-purple-500/20 dark:text-white" data-filter="finance">
  <header class="flex-1 flex items-center gap-2 lg:gap-4">
    <div class="flex items-center justify-center w-14 h-14 font-semibold text-lg bg-purple-200 dark:bg-purple-600/50">
      AB
    </div>
    <div class="flex-auto">
      <a href="#" class="font-medium block">Banking association</a>
      <span class="text-xs text-gray-600 dark:text-gray-400">UX/UI Designer</span>
    </div>
  </header>
  <button class="rounded-full flex flex-none items-center justify-center w-8 h-8 transition-all hover:bg-black/10 dark:hover:bg-white/10">
    <svg width="26" height="26" fill="none" stroke-width="2" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM12.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0ZM18.75 12a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"></path>
    </svg>
  </button>
</article>

<article class="border shadow-sm break-inside flex flex-col rounded-xl p-3 gap-2 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	<header class="flex items-center justify-between w-full">
		<div class="flex items-start flex-col">
      <h2 class="text-base font-medium block">Globlas sales</h2>
			<p class="text-xs text-gray-600 dark:text-gray-400">Update Ocober 2024 - 8:15 AM</p>
		</div>
		<button class="h-8 w-8 transition-colors duration-200 flex items-center justify-center rounded-full hover:bg-black/10 dark:hover:bg-white/10">
			<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 512 512">
        <circle cx="256" cy="256" r="32" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32" />
        <circle cx="416" cy="256" r="32" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32" />
        <circle cx="96" cy="256" r="32" fill="none" stroke="currentColor" stroke-miterlimit="10" stroke-width="32" />
      </svg>
		</button>
	</header>
	<section class="flex items-center w-full justify-between gap-2 p-2 mt-2 rounded-md bg-gray-100 dark:bg-gray-900">
    <div class="flex-1 flex items-center gap-2">
      <div class="flex-none w-9 h-9 rounded-full flex items-center justify-center text-lg font-semibold bg-gray-950 text-white dark:bg-gray-50 dark:text-black">G</div>
      <p class="w-full text-xs">Lorem ales psum dolor sit am...</p>
    </div>
    <div class="flex items-end">
      <svg class="w-20" viewBox="0 0 57 19" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M3.5 16.0771C2.22019 15.7164 0.957196 17.0165 0.500122 17.9182H56.4999V13.3571C55.9285 17.2646 54.0665 11.9405 53 12.9925C52.3075 9.71362 51.4641 15.308 49.7098 16.0771C49.2909 14.5241 46.202 11.5537 45.105 13.3571C43.7338 15.6115 41.3429 13.109 41.0001 12.2073C40.6573 11.3055 38.0905 10.0537 36.605 11.8571C35.1195 13.6606 35.4762 12.8724 34.105 12.8724C32.7338 12.8724 30.0009 7.39801 29.3153 6.1957C28.4025 4.59507 25.4284 14.9424 24.605 12.8724C23.3474 9.71093 26.1456 8.46015 20.5 1.46309C18.5598 -0.941537 18.6775 7.49359 14.0981 12.2073C10.314 16.1023 9.25324 9.60692 6.55636 15.8142C5.64221 17.9182 5.09976 16.528 3.5 16.0771Z" fill="url(#paint0_linear_136_2526)" />
        <path d="M0.500122 17.9182C0.957196 17.0165 2.22019 15.7164 3.5 16.0771C5.09976 16.528 5.64221 17.9182 6.55636 15.8142C9.25324 9.60692 10.314 16.1023 14.0981 12.2073C18.6775 7.49359 18.5598 -0.941537 20.5 1.46309C26.1456 8.46015 23.3474 9.71093 24.605 12.8724C25.4284 14.9424 28.4025 4.59507 29.3153 6.1957C30.0009 7.39801 32.7338 12.8724 34.105 12.8724C35.4762 12.8724 35.1195 13.6606 36.605 11.8571C38.0905 10.0537 40.6573 11.3055 41.0001 12.2073C41.3429 13.109 43.7338 15.6115 45.105 13.3571C46.202 11.5537 49.2909 14.5241 49.7098 16.0771C51.4641 15.308 52.3075 9.71362 53 12.9925C54.0665 11.9405 55.9285 17.2646 56.4999 13.3571" stroke="#2D81FF" stroke-linecap="round" stroke-linejoin="round" />
        <defs>
          <linearGradient id="paint0_linear_136_2526" x1="28.5" y1="1.04053" x2="28.5" y2="17.9182" gradientUnits="userSpaceOnUse">
            <stop stop-color="#2D81FF" stop-opacity="0.48" />
            <stop offset="1" stop-color="#F2F7FF01" stop-opacity="0.1" />
          </linearGradient>
        </defs>
      </svg>
    </div>
	</section>
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>

<article class="border shadow-sm break-inside flex items-center justify-between rounded-xl p-4 mb-3 text-sm bg-white dark:bg-gray-950 dark:text-white dark:border-gray-900" data-filter="finance">
	coming soon...
</article>