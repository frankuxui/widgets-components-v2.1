---
layout: "../../layouts/ExpoLayout.astro"
slug: 'sport'
category: 'Sport'
tags: ['sport']
title: 'Widget components with tailwind CSS'
visible: false
---

<article class="shadow-sm break-inside flex flex-col justify-between rounded-full p-2 mb-3 text-base bg-[#D81A22] text-white" data-filter="sport">
  <div class="flex items-center justify-between space-x-3">
    <div class="flex items-center justify-center space-x-2">
      <div class="flex items-center justify-center rounded-full w-10 h-10 bg-white">
        <svg width="26" height="22" viewBox="0 0 26 22" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M25.4936 11.6486C25.4936 11.7132 25.451 11.7562 25.3232 11.8208L25.2807 11.8854V11.9284C25.2807 11.993 25.2807 11.993 25.2168 12.0576L25.1103 12.1007H24.9825V12.0576L24.8761 12.1007V12.1652C24.8761 12.2083 24.8761 12.2083 24.8335 12.2729L24.7057 12.3374H24.5992V12.2729C24.1946 12.5097 23.7049 12.6819 23.2577 12.8971V12.9617C23.2577 13.0048 23.2577 13.0048 23.1938 13.0693L23.0873 13.1339H22.9595L22.9169 13.0693L22.7466 13.1339L22.7892 13.177C22.7926 13.2004 22.7905 13.2243 22.7831 13.2467C22.7757 13.2691 22.7632 13.2895 22.7466 13.3061L22.6401 13.3492H22.5123L22.4698 13.3061C22.2355 13.4138 22.0226 13.4138 21.8522 13.0693C21.6819 12.7249 21.7883 12.5527 21.7244 12.3805C21.7087 12.3484 21.6844 12.3213 21.6543 12.3023C21.6243 12.2833 21.5896 12.2731 21.5541 12.2729C19.4246 11.8854 18.7432 12.3374 17.3377 11.993C16.8905 11.8854 16.6776 11.4764 16.1665 11.4764C15.0379 11.4118 14.6972 11.4764 13.4195 11.4118C13.3865 11.487 13.365 11.5669 13.3556 11.6486H8.96891L9.65034 11.993L9.86329 13.9304L9.65034 13.9735C9.71422 14.3825 9.71422 14.8776 9.75681 15.3511C9.7994 15.8247 9.8207 16.1907 9.8207 16.4705C9.82908 16.6491 9.79245 16.8268 9.71422 16.9872C9.64151 17.1369 9.52167 17.2581 9.37351 17.3316L8.96891 17.6114L8.41525 17.8913C8.41525 17.9558 8.45784 18.0204 8.45784 18.0635C5.81729 19.3766 2.51661 19.7641 1.45187 21.8736C1.32411 22.1104 0.876917 21.9813 0.876917 21.7014V21.314H0.834327C0.770443 21.314 0.770443 21.2494 0.770443 21.1848V21.0772C0.770443 21.0341 0.834327 20.9695 0.834327 20.9695H0.876917C0.876917 20.8619 0.940801 20.7327 0.940801 20.6251H0.876917C0.834327 20.6251 0.834327 20.5605 0.876917 20.5175L0.940801 20.3883C0.940801 20.3453 0.98339 20.2807 1.04727 20.3453H1.11116C1.28152 19.8932 1.66482 19.721 1.83518 19.269C1.77129 19.269 1.77129 19.2044 1.83518 19.1398L1.77129 19.0322C1.76565 19.015 1.76696 18.9963 1.77495 18.9802C1.78294 18.964 1.79694 18.9518 1.81388 18.9461C1.83083 18.9403 1.84932 18.9417 1.86529 18.9497C1.88127 18.9578 1.89342 18.972 1.89906 18.9891H1.94165C1.94165 18.9245 2.00554 18.86 2.06942 18.8169H2.00554C1.94165 18.8169 1.94165 18.7523 2.00554 18.6877L2.06942 18.5801C2.11201 18.5155 2.11201 18.5155 2.17589 18.5155L2.23978 18.4725C2.31866 18.4096 2.41617 18.3754 2.51661 18.3754C2.61705 18.3754 2.71456 18.4096 2.79344 18.4725C3.0172 18.6207 3.28374 18.6885 3.55023 18.6651C3.81672 18.6416 4.06768 18.5283 4.26278 18.3433C5.26363 17.3962 6.49872 16.1476 7.3931 16.083C7.18015 15.5664 6.73296 14.4255 6.66908 13.9735L6.39225 13.9304C6.22189 13.586 5.81729 11.993 5.71082 10.7445C5.71082 10.7445 5.60434 9.43138 5.71082 8.97932C5.63577 9.00632 5.56426 9.04246 5.49787 9.08696C5.32751 8.69948 5.88118 5.16915 6.39225 4.15741L7.22274 3.81298L4.9868 3.64077C4.09242 4.43725 3.13416 5.27678 2.5592 5.75036C2.45273 5.79341 2.34625 6.31005 2.34625 6.31005C2.19275 6.46048 2.02102 6.59068 1.83518 6.69752C1.49446 6.93431 0.770443 7.10653 0.600085 6.82668C0.429728 6.54684 0.536201 6.69752 0.600085 6.69752C0.66397 6.69752 1.15375 6.37463 1.32411 6.07326C1.11116 6.20242 0.834327 6.37463 0.600085 6.31005C0.572416 6.29887 0.548696 6.27956 0.531987 6.25462C0.515278 6.22968 0.506348 6.20025 0.506348 6.17013C0.506348 6.14 0.515278 6.11057 0.531987 6.08563C0.548696 6.06069 0.572416 6.04138 0.600085 6.0302C0.891233 5.93718 1.15971 5.78314 1.38799 5.57815C1.451 5.43893 1.5534 5.3217 1.68225 5.24124C1.81111 5.16079 1.96065 5.12072 2.11201 5.1261C2.11201 5.1261 3.58135 3.18872 4.41184 2.28461C4.64608 2.04782 5.09327 2.1124 5.09327 2.1124L5.15715 1.81103C5.15715 1.81103 8.07453 1.48813 9.47998 1.94019C9.4161 1.07913 9.8207 0.00280762 11.1197 0.00280762C11.7798 0.00280762 12.7381 0.627074 12.9084 1.31592C12.9723 1.53118 12.802 1.70339 12.7381 1.98324C12.6742 2.26308 12.802 2.90887 12.7381 3.01651C12.6742 3.12414 12.5677 3.12414 12.4612 3.29635C12.3548 3.46856 12.1844 3.81298 12.1844 3.81298L12.0141 4.20046L11.1197 4.15741C10.779 4.8893 10.0975 6.37463 9.86329 7.83842C10.6086 7.903 13.8667 8.35506 13.8667 8.35506L13.9093 8.6349C14.7657 8.75477 15.6032 8.98631 16.4008 9.32375C16.6137 9.3668 17.2951 9.25917 17.6784 9.49596L17.8062 9.3668C19.2543 9.84038 20.4893 10.6369 21.8948 10.9598L22.7892 11.1965C23.3003 11.3042 23.641 11.3042 23.9178 11.3688C24.2575 11.4013 24.5987 11.4157 24.9399 11.4118C25.1103 11.3688 25.451 11.3042 25.4936 11.6486Z" fill="#D20515"></path>
        </svg>
      </div>
      <span class="uppercase text-sm font-medium">Bundesliga</span>
    </div>
    <button class="flex items-center justify-between py-3 px-3 gap-2 text-xs rounded-full h-full font-medium bg-white text-black">
      <span>2020 - 2021</span>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2.5" stroke="currentColor" width="20" height="20">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5"></path>
      </svg>
    </button>
  </div>
</article>

<article class="shadow-sm break-inside flex flex-col justify-between rounded-full p-2 mb-3 text-base bg-[#9903DF] text-white" data-filter="sport">
  <div class="flex items-center justify-between space-x-3">
    <div class="flex items-center justify-center space-x-2">
      <div class="flex items-center justify-center rounded-full w-10 h-10 bg-white">
        <svg width="24" height="30" viewBox="0 0 24 30" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M11.0053 0.499817C11.0053 0.499817 10.1824 2.84157 9.95765 3.55328C9.39578 3.16057 7.63403 1.94257 6.90178 1.43628C7.07094 2.41019 7.33194 4.00278 7.38874 4.3399C7.2389 4.22753 6.39669 3.49648 5.12311 2.89715C5.83482 3.72123 6.34111 4.99482 6.6589 6.02432C8.58803 4.92837 10.7695 4.35407 12.9882 4.35803C14.1687 4.35803 15.3323 4.52719 16.4367 4.84498C16.5491 3.77682 16.7739 2.46698 17.2608 1.5124C16.1552 2.39207 15.4797 3.32853 15.3867 3.4409C15.3492 3.21615 15.2743 1.60423 15.1813 0.499817C14.7318 0.986775 13.0063 2.93582 12.6885 3.23548C12.4649 2.84157 11.0053 0.499817 11.0053 0.499817ZM13.028 5.16398C11.0053 5.16398 9.04053 5.6304 7.35369 6.51128C8.21524 6.56686 8.83269 7.31844 9.03932 7.91778C8.36507 7.37403 7.2969 7.11182 6.64078 7.82353C6.02332 8.53523 6.08011 9.86319 6.69757 10.9314C5.25603 10.2003 5.25482 8.29115 5.76111 7.46707C4.10425 8.66822 2.76606 10.2561 1.86303 12.0926L3.15594 12.3004C1.65761 14.0235 0.609985 17.0769 0.609985 18.5185L2.72457 17.8624C2.34999 19.1359 2.24003 23.4231 3.51361 25.5776C3.51361 25.5776 5.18111 24.4176 7.07215 21.5139C7.85757 24.136 7.50232 26.3292 7.07215 28.4824C10.4797 30.3928 14.4309 29.3234 16.7533 27.6571L17.1847 29.2884C19.901 27.4892 21.3994 24.9045 21.6797 21.8885L22.6911 23.0123C24.245 18.3856 23.0294 14.6953 20.8 11.5307L20.7058 12.3004L19.7512 11.2492C19.7512 11.2492 19.9566 11.1561 20.1258 10.9314C20.162 10.8371 20.0702 10.3332 19.6775 9.99611C19.3029 10.0904 19.0008 10.3151 18.851 10.5399C18.5159 10.2597 18.136 10.0378 17.7272 9.88373C17.8022 9.97678 18.4571 10.8383 18.5127 11.1005C19.0757 11.5694 19.8442 12.1119 20.3493 12.7862C19.9385 12.2992 17.952 12.1856 17.053 12.6919C17.053 12.6919 16.154 11.6431 15.3299 10.912C15.1607 10.2946 15.7238 9.75203 15.7238 9.75203C15.7238 9.75203 15.1438 9.71578 14.6001 10.2595C13.776 9.64086 12.7272 9.35932 12.7272 9.35932C11.5659 9.52848 10.7793 10.3502 10.7793 10.3502C11.0415 10.5193 11.398 10.7453 11.717 10.8576C12.3344 11.1199 12.9326 11.0256 13.3265 11.0256C13.6443 11.0256 14.095 11.1199 14.095 11.1199C14.095 11.1199 14.8623 11.718 15.986 13.0109C14.2629 12.3173 12.4637 13.0858 11.1902 12.4672C9.69182 11.718 9.8054 10.5399 9.8054 10.5399C9.8054 10.5399 8.79524 10.4069 8.79524 10.3695C8.79524 10.3695 9.54199 9.37865 10.6657 9.04032L10.1051 8.55457C10.7793 7.99269 11.9587 7.24353 13.869 7.05623C13.869 7.05623 14.6943 7.37282 16.4186 8.60894C16.6989 8.21503 16.7908 7.39094 16.7908 7.39094C17.6704 7.69061 19.4697 9.00165 20.1814 9.78828C19.7887 8.87115 19.5059 8.31048 19.4129 7.3559C18.9815 6.92453 17.9145 6.02553 15.7045 5.48178C16.0609 6.21282 16.0235 6.82907 16.0235 6.82907C15.6127 6.28532 14.7487 5.44432 14.1506 5.21957C13.7941 5.20144 13.4195 5.16278 13.0268 5.16278L13.028 5.16398ZM16.9805 13.7045C17.4359 14.0679 17.9488 14.3526 18.4982 14.5467V16.1755C17.9363 16.6625 16.0996 18.1995 14.8635 18.0678C14.1711 16.7386 13.5162 15.5218 13.5162 15.5218C13.5162 15.5218 15.4072 13.9292 16.9805 13.7045ZM20.5753 13.7419C21.1372 15.1086 21.2882 16.7386 20.6695 17.8249C20.3312 17.0939 19.901 16.6806 19.4515 16.1937V14.566C19.4515 14.566 19.9566 14.247 20.5753 13.7419ZM19.3947 17.8442C19.9566 18.4617 20.0702 19.1347 20.0702 19.1347C19.8261 20.5014 19.06 21.3653 18.4982 21.7206C18.5537 20.7285 18.2903 19.8851 18.2903 19.8851C17.8795 20.3346 16.9249 20.7829 16.3618 20.8953L15.5196 19.3244C16.5129 19.2858 18.1792 17.8817 18.1792 17.8817L19.3947 17.8442Z" fill="#9903DF"></path>
        </svg>
      </div>
      <span class="uppercase text-sm font-medium">Premier</span>
    </div>
    <button class="flex items-center justify-between py-3 px-3 gap-2 text-xs rounded-full h-full font-medium bg-white text-black">
      <span>2020 - 2021</span>
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2.5" stroke="currentColor" width="20" height="20">
        <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5"></path>
      </svg>
    </button>
  </div>
</article>