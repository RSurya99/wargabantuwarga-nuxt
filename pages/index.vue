<template>
  <div>
    <div class="bg-white mb-3">
      <!-- Section Banner -->
      <section class="relative">
        <img :src="require('@/assets/img/hero-banner.png')" alt="" />
        <div
          class="w-full h-full p-4 absolute top-0 flex flex-col flex-1 items-start justify-between"
        >
          <img
            :src="require('@/assets/img/logo/logo.svg')"
            class="h-8 h-10"
            alt=""
          />
          <div class="w-[60%] sm:w-[55%] space-y-1">
            <h1 class="text-blue-700 text-lg sm:text-2xl">
              Warga<span class="font-semibold">Bantu</span>Warga
            </h1>
            <p class="text-xs sm:text-sm">
              Inisiatif warga untuk berbagi informasi dan membantu warga yang
              terdampak Covid-19.
            </p>
          </div>
        </div>
      </section>

      <!-- Section Telusuri Sekarang -->
      <section class="px-4 py-8">
        <h2 class="text-lg sm:text-xl font-semibold sm:mx-6 text-center">
          Cek database RS, Puskesmas, Ambulans, Oksigen, dan kontak penting
          lainnya
        </h2>
        <a
          class="flex flex-row px-4 py-2 text-base rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 mt-4"
          >Telusuri sekarang</a
        >
      </section>

      <!-- Section Big Card -->
      <div class="px-4">
        <div class="rounded-sm">
          <div
            class="flex flex-row relative py-5 px-4 border-gray-100 border-2 rounded-lg justify-between"
          >
            <div class="flex flex-row items-center">
              <div
                aria-hidden="true"
                class="flex flex-none items-center justify-center w-12 h-12 bg-blue-50 rounded-full"
              >
                <img
                  :src="require('@/assets/img/icon/card.svg')"
                  class="w-6 h-6"
                  alt=""
                />
              </div>
              <div class="ml-4 space-y-1">
                <h3 class="text-base leading-5 font-semibold">
                  <a class="helper-link-cover" href="/kontak-darurat"
                    >Kontak Darurat</a
                  >
                </h3>
                <p class="text-sm leading-4 text-gray-500">
                  Situs dan kontak penting terkait COVID-19
                </p>
              </div>
            </div>
            <div
              aria-hidden="true"
              class="flex flex-none items-center justify-center ml-2"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
                aria-hidden="true"
                class="w-6 h-6 text-blue-700"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
          </div>
        </div>
      </div>

      <!-- Section Cards -->
      <div class="px-4 py-6">
        <ul class="grid grid-cols-2 gap-3 sm:gap-6 sm:grid-cols-4">
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                viewBox="0 0 24 25"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <path
                  clip-rule="evenodd"
                  d="M13.157 1.857a1.157 1.157 0 10-2.314 0v.986h-.986a1.157 1.157 0 000 2.314h.986v.986a1.157 1.157 0 102.314 0v-.986h.986a1.157 1.157 0 000-2.314h-.986v-.986z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M7.5 3.171c-1.087 0-2.025.859-2.025 1.986v.385c-.936.156-1.687.95-1.687 1.958v14.514h-.225c-.777 0-1.463.616-1.463 1.443 0 .828.686 1.443 1.463 1.443h16.875c.776 0 1.462-.615 1.462-1.443 0-.828-.686-1.443-1.462-1.443h-.225V7.5c0-1.008-.751-1.802-1.688-1.958v-.385c0-1.127-.938-1.986-2.025-1.986a.9.9 0 100 1.8c.151 0 .225.11.225.186v1.257a.9.9 0 00.9.9h.563c.151 0 .225.11.225.186v15.414c0 .064.006.126.019.186H14.25v-1.267c0-.598-.504-1.083-1.125-1.083h-2.25c-.621 0-1.125.485-1.125 1.083V23.1H5.568a.902.902 0 00.02-.186V7.5c0-.076.073-.186.225-.186h.562a.9.9 0 00.9-.9V5.157c0-.076.074-.186.225-.186a.9.9 0 000-1.8z"
                  fill="currentColor"
                ></path>
                <path
                  d="M8.625 10c-.621 0-1.125.485-1.125 1.083v1.084c0 .598.504 1.083 1.125 1.083s1.125-.485 1.125-1.083v-1.084c0-.598-.504-1.083-1.125-1.083zM8.625 14.333c-.621 0-1.125.485-1.125 1.084V16.5c0 .598.504 1.083 1.125 1.083S9.75 17.098 9.75 16.5v-1.083c0-.599-.504-1.084-1.125-1.084zM10.875 11.083c0-.598.504-1.083 1.125-1.083s1.125.485 1.125 1.083v1.084c0 .598-.504 1.083-1.125 1.083s-1.125-.485-1.125-1.083v-1.084zM12 14.333c-.621 0-1.125.485-1.125 1.084V16.5c0 .598.504 1.083 1.125 1.083s1.125-.485 1.125-1.083v-1.083c0-.599-.504-1.084-1.125-1.084zM14.25 11.083c0-.598.504-1.083 1.125-1.083s1.125.485 1.125 1.083v1.084c0 .598-.504 1.083-1.125 1.083s-1.125-.485-1.125-1.083v-1.084zM15.375 14.333c-.621 0-1.125.485-1.125 1.084V16.5c0 .598.504 1.083 1.125 1.083S16.5 17.098 16.5 16.5v-1.083c0-.599-.504-1.084-1.125-1.084z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/provinces?kebutuhan=Rumah%20sakit"
              >Rumah Sakit</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                viewBox="0 0 26 24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <circle
                  cx="18.2583"
                  cy="18.4"
                  r="1.85"
                  stroke="currentColor"
                  stroke-width="1.8"
                ></circle>
                <path
                  clip-rule="evenodd"
                  d="M20.458 6.33V5.292a2.292 2.292 0 10-4.583 0v.916l-.456-1.139a1.833 1.833 0 00-1.702-1.152H3.958c-1.012 0-1.833.82-1.833 1.833v11c0 1.012.82 1.833 1.833 1.833H5.34a2.75 2.75 0 005.488 0h3.306c.031 0 .062-.001.092-.005a.824.824 0 00.917-.82V8.095c0-.13.106-.237.237-.237h4.423c.069 0 .131.038.163.1l2.49 4.8c.013.027.02.056.02.085v3.907a.183.183 0 01-.183.183H22.2a.825.825 0 000 1.65h.092c1.012 0 1.833-.82 1.833-1.833v-3.907c0-.294-.07-.583-.206-.844l-2.49-4.801c-.21-.405-.558-.71-.97-.868zm-2.291-1.955a.917.917 0 00-.917.917v.916h1.833v-.916a.917.917 0 00-.916-.917zM10.41 16.933h3.082V6.483a.917.917 0 00-.917-.916H3.958a.183.183 0 00-.183.183v11c0 .101.082.183.183.183h1.799a2.748 2.748 0 014.653 0zM8.083 19.5a1.1 1.1 0 100-2.2 1.1 1.1 0 000 2.2z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M8.633 8.042c.456 0 .825.369.825.825v3.666a.825.825 0 01-1.65 0V8.867c0-.456.37-.825.825-.825z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M5.975 10.7c0-.456.37-.825.825-.825h3.667a.825.825 0 110 1.65H6.8a.825.825 0 01-.825-.825z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/provinces?kebutuhan=Ambulans"
              >Ambulans</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <ellipse
                  cx="8.98281"
                  cy="17.0626"
                  fill="currentColor"
                  rx="1.38076"
                  ry="1.38076"
                ></ellipse>
                <ellipse
                  cx="10.3642"
                  cy="13.3346"
                  fill="currentColor"
                  rx="1.38076"
                  ry="1.38076"
                ></ellipse>
                <circle
                  cx="7.14219"
                  cy="13.795"
                  fill="currentColor"
                  r="0.920506"
                ></circle>
                <path
                  clip-rule="evenodd"
                  d="M17.268 7.535a1.565 1.565 0 100-3.13 1.565 1.565 0 000 3.13zm0 1.657a3.222 3.222 0 100-6.443 3.222 3.222 0 000 6.443z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M5.67 2.841v-.552a.828.828 0 10-1.657 0V5.05a.828.828 0 001.656 0v-.552h1.105v2.354A5.985 5.985 0 003 12.414v9.665c0 .509.412.921.92.921h10.126a.92.92 0 00.92-.92v-9.666a5.985 5.985 0 00-3.773-5.562V4.498h.092c1.077 0 2.038.228 2.87.64a3.218 3.218 0 01.827-1.438c-1.073-.551-2.315-.859-3.697-.859h-.123a2.21 2.21 0 00-4.357 0H5.669zM8.43 6.456a6.058 6.058 0 011.105 0V3.209a.552.552 0 00-1.105 0v3.247zm3.879 14.887a1 1 0 001-1v-7.929a4.326 4.326 0 00-8.653 0v7.93a1 1 0 001 1h6.653z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M18.997 8.69c-.459.292-.997.472-1.576.499a9.43 9.43 0 01.4 2.765v10.218a.829.829 0 001.656 0V11.954c0-1.15-.165-2.251-.48-3.265z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/provinces?kebutuhan=Oksigen"
              >Info Oksigen</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                height="24"
                viewBox="0 0 24 24"
                width="24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <path
                  clip-rule="evenodd"
                  d="M16.609 15.12a4.094 4.094 0 100-8.189 4.094 4.094 0 000 8.188zm0 1.754a5.849 5.849 0 100-11.697 5.849 5.849 0 000 11.697z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M9.785 23c3.677 0 6.794-2.113 7.878-5.038a.476.476 0 00-.459-.601h-.62a.949.949 0 00-.909.677l-.02.07c-1.028 1.797-3.172 3.137-5.87 3.137-3.82 0-6.53-2.687-6.53-5.556 0-.12.004-.239.013-.356l.115-1.55c.285-1.655 1.026-3.499 2.063-5.315 1.302-2.28 2.962-4.33 4.404-5.66 1.217 1.029 2.487 2.541 3.583 4.274a5.807 5.807 0 011.71-.571c-1.255-2.061-2.777-3.905-4.285-5.148a1.594 1.594 0 00-2.096.062c-2.843 2.58-6.32 7.567-7.101 12.022-.07.4-.119.796-.143 1.185a9.142 9.142 0 00-.018.569v.001h.018a6.55 6.55 0 000 .975C1.802 19.987 5.395 23 9.785 23z"
                  fill="currentColor"
                ></path>
                <path
                  d="M17.73 9.495a.877.877 0 00-1.755 0v.585h-.585a.877.877 0 100 1.754h.585v.585a.877.877 0 001.754 0v-.585h.585a.877.877 0 100-1.755h-.585v-.584z"
                  fill="currentColor"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M5.887 13.282c.484 0 .877.393.877.877v.975c0 1.4 1.134 2.534 2.534 2.534h.488a.877.877 0 010 1.755h-.488a4.289 4.289 0 01-4.289-4.29v-.974c0-.484.393-.877.878-.877z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/provinces?kebutuhan=Donor%20plasma"
              >Donor Plasma</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <path
                  d="M13.752 2.5a1 1 0 011-1h.684c.038 0 .39 0 .764.002.52.002.92.408.92.929v5.494l-1.313-.787a.722.722 0 00-.742 0l-1.313.787V2.5z"
                  fill="currentColor"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M3.5 5.254v14.455A2.791 2.791 0 006.291 22.5h11.551a2.791 2.791 0 002.792-2.791V5.254a3.75 3.75 0 00-1.564-3.049.866.866 0 00-1.012 1.407c.512.368.843.966.843 1.642v10.699a3.771 3.771 0 00-.578-.044H5.81c-.196 0-.389.015-.577.044V5.254c0-1.116.905-2.021 2.021-2.021h5.053a.866.866 0 000-1.733H7.254A3.754 3.754 0 003.5 5.254zm1.733 13.492v.963c0 .584.474 1.058 1.058 1.058h11.551c.45 0 .833-.279.987-.673H7.254a.866.866 0 010-1.733h11.575a1.06 1.06 0 00-.987-.674H6.292c-.585 0-1.06.474-1.06 1.059z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/edukasi"
              >Edukasi</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                height="24"
                viewBox="0 0 24 24"
                width="24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <path
                  d="M13.58.315L9.433 5.36h7.146l1.386-1.849c.029-.038.06-.073.091-.109a.953.953 0 00-.232-1.439L14.78.136a.953.953 0 00-1.198.18z"
                  fill="currentColor"
                ></path>
                <path
                  d="M10.535 10.646c0-.469.38-.85.85-.85h.858c.47 0 .85.381.85.85v1.859a1.28 1.28 0 11-2.558 0v-1.859z"
                  fill="currentColor"
                  stroke="currentColor"
                  stroke-width="0.3"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M20.627 6.502H3a1 1 0 100 2.001h17.627a1 1 0 100-2z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M8.24 9.504H3.382a1 1 0 00-1 1v7.065C2.381 20.121 4.705 22 7.322 22h8.984c2.617 0 4.94-1.879 4.94-4.43v-7.066a1 1 0 00-1-1h-4.859a.858.858 0 000 1.715h3.145a1 1 0 011 1v5.35c0 1.397-1.335 2.716-3.226 2.716H7.322c-1.891 0-3.226-1.319-3.226-2.716v-5.35a1 1 0 011-1h3.145a.858.858 0 100-1.715z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="/donasi"
              >Donasi</a
            >
          </li>
          <li
            class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2"
          >
            <div
              aria-hidden="true"
              class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full"
            >
              <svg
                fill="none"
                viewBox="0 0 16 20"
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-blue-700"
              >
                <path
                  d="M8 9C7.44772 9 7 9.44771 7 10C7 10.5523 7.44772 11 8 11V9ZM11 11C11.5523 11 12 10.5523 12 10C12 9.44771 11.5523 9 11 9V11ZM8 13C7.44772 13 7 13.4477 7 14C7 14.5523 7.44772 15 8 15V13ZM11 15C11.5523 15 12 14.5523 12 14C12 13.4477 11.5523 13 11 13V15ZM5 9C4.44772 9 4 9.44771 4 10C4 10.5523 4.44772 11 5 11V9ZM5.01 11C5.56228 11 6.01 10.5523 6.01 10C6.01 9.44771 5.56228 9 5.01 9V11ZM5 13C4.44772 13 4 13.4477 4 14C4 14.5523 4.44772 15 5 15V13ZM5.01 15C5.56228 15 6.01 14.5523 6.01 14C6.01 13.4477 5.56228 13 5.01 13V15ZM14 5V17H16V5H14ZM13 18H3V20H13V18ZM2 17V5H0V17H2ZM3 4H5V2H3V4ZM11 4H13V2H11V4ZM3 18C2.44772 18 2 17.5523 2 17H0C0 18.6569 1.34315 20 3 20V18ZM14 17C14 17.5523 13.5523 18 13 18V20C14.6569 20 16 18.6569 16 17H14ZM16 5C16 3.34315 14.6569 2 13 2V4C13.5523 4 14 4.44772 14 5H16ZM2 5C2 4.44772 2.44772 4 3 4V2C1.34315 2 0 3.34315 0 5H2ZM8 11H11V9H8V11ZM8 15H11V13H8V15ZM7 2H9V0H7V2ZM9 4H7V6H9V4ZM7 4C6.44772 4 6 3.55228 6 3H4C4 4.65685 5.34315 6 7 6V4ZM10 3C10 3.55228 9.55228 4 9 4V6C10.6569 6 12 4.65685 12 3H10ZM9 2C9.55228 2 10 2.44772 10 3H12C12 1.34315 10.6569 0 9 0V2ZM7 0C5.34315 0 4 1.34315 4 3H6C6 2.44772 6.44772 2 7 2V0ZM5 11H5.01V9H5V11ZM5 15H5.01V13H5V15Z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <a
              class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover"
              href="https://www.indorelawan.org/activity/60e2ed45164da80018b0e246"
              rel="noopener noreferrer nofollow"
              target="_blank"
              >Kontribusi</a
            >
          </li>
        </ul>
      </div>

      <!-- Section Banner 2 -->
      <div class="px-4 py-6">
        <a
          href="https://sembako.wargabantuwarga.com"
          rel="nofollow noopener noreferrer"
          target="_blank"
        >
          <div>
            <img
              alt="Ajukan bantuan sembako jika positif Covid-19 - Daftar Sekarang"
              :src="require('@/assets/img/banner-2.png')"
              class="w-full"
            />
          </div>
        </a>
      </div>
    </div>

    <div class="bg-white mb-3">
      <!-- Section Informasi Terbaru -->
      <section class="bg-white overflow-hidden px-4 py-6 space-y-4">
        <h2 class="text-lg sm:text-xl font-semibold">Informasi Terbaru</h2>
        <article class="border border-gray-200 rounded-md p-4 space-y-4">
          <div class="space-y-2">
            <div class="flex flex-row text-base">
              <h3 class="flex-1 font-semibold text-gray-700 truncate">
                Rumah Oksigen Gotong Royong (ROGR)
              </h3>
              <span class="inline-block flex-none text-gray-500 ml-4"
                >4 Agustus 2021</span
              >
            </div>
            <div class="text-gray-600 text-sm">
              <p>
                Pendaftaran Rumah Oksigen Gotong Royong (ROGR) telah dibuka.
                ROGR adalah fasilitas kesehatan semi-permanen yang khusus
                dilengkapi dengan peralatan suplai oksigen dan tempat tidur
                perawatan bagi warga terpapar COVID-19 dengan gejala ringan.
              </p>
            </div>
          </div>
          <a
            class="flex flex-row-reverse px-4 py-2 text-sm rounded-md items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
            href="https://halodoc.page.link/gpbaUJdzJM3UrRQp9"
            rel="nofollow noopener noreferrer"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
              class="ml-2 -mr-1 h-5 w-5"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
              ></path></svg
            >Daftar ROGR di aplikasi Halodoc</a
          >
        </article>
        <article class="border border-gray-200 rounded-md p-4 space-y-4">
          <div class="space-y-2">
            <div class="flex flex-row text-base">
              <h3 class="flex-1 font-semibold text-gray-700 truncate">
                Wilayah Jakarta
              </h3>
              <span class="inline-block flex-none text-gray-500 ml-4"
                >25 Juli 2021</span
              >
            </div>
            <div class="text-gray-600 text-sm">
              <p>
                Daftar Vaksin di Sentra Vaksinasi SINERGI SEHAT untuk masyarakat
                usia 12 tahun ke atas. Pelaksanaan Vaksin pada 22 Juli-15
                September 2021 (Senin-Jumat pukul 08.30-15.00 WIB). Lokasi
                pelasanaan di The Media Hotel &amp; Towers (Jln. Gunung Sahari
                No. 3, RT 16/RW 3, Gunung Sahari).
              </p>
            </div>
          </div>
          <a
            class="flex flex-row-reverse px-4 py-2 text-sm rounded-md items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
            href="https://sinergisehat.vaksin.siapdok.id/#/"
            rel="nofollow noopener noreferrer"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
              class="ml-2 -mr-1 h-5 w-5"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
              ></path></svg
            >Daftar vaksin SINERGI SEHAT</a
          >
        </article>
        <article class="border border-gray-200 rounded-md p-4 space-y-4">
          <div class="space-y-2">
            <div class="flex flex-row text-base">
              <h3 class="flex-1 font-semibold text-gray-700 truncate">
                Kementerian Kesehatan
              </h3>
              <span class="inline-block flex-none text-gray-500 ml-4"
                >14 Juli 2021</span
              >
            </div>
            <div class="text-gray-600 text-sm">
              <p>
                Kementerian Kesehatan meluncurkan SIRANAP terbaru versi 3.0.
                Melalui SIRANAP 3.0, kita dapat memeriksa
                <strong class="font-bold text-gray-900"
                  >ketersediaan IGD di seluruh Indonesia</strong
                >. Khusus untuk wilayah Jakarta ketersediaan IGD diperbarui
                setiap 3 jam sekali oleh para relawan lapangan.
              </p>
            </div>
          </div>
          <a
            class="flex flex-row-reverse px-4 py-2 text-sm rounded-md items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
            href="https://yankes.kemkes.go.id/app/siranap/rumah_sakit?jenis=1&amp;propinsi=31prop&amp;kabkota="
            rel="nofollow noopener noreferrer"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              aria-hidden="true"
              class="ml-2 -mr-1 h-5 w-5"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
              ></path></svg
            >Cek ketersediaan IGD Jakarta</a
          >
        </article>
      </section>
    </div>

    <!-- Section Cara Berkontribusi -->
    <div class="bg-white mb-3">
      <section class="bg-white overflow-hidden px-4 py-6 space-y-4">
        <h2 class="text-lg sm:text-xl font-semibold">Cara Berkontribusi</h2>
        <ul class="rounded-sm">
          <li
            class="flex flex-row relative py-4 border-b border-gray-100 last-of-type:border-b-0"
          >
            <div
              aria-hidden="true"
              class="flex flex-none items-center justify-center w-12 h-12 bg-blue-50 rounded-full"
            >
              <svg
                fill="none"
                height="24"
                viewBox="0 0 24 24"
                width="24"
                xmlns="http://www.w3.org/2000/svg"
                class="w-6 h-6 text-blue-700"
              >
                <path
                  clip-rule="evenodd"
                  d="M16.609 15.12a4.094 4.094 0 100-8.189 4.094 4.094 0 000 8.188zm0 1.754a5.849 5.849 0 100-11.697 5.849 5.849 0 000 11.697z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
                <path
                  d="M9.785 23c3.677 0 6.794-2.113 7.878-5.038a.476.476 0 00-.459-.601h-.62a.949.949 0 00-.909.677l-.02.07c-1.028 1.797-3.172 3.137-5.87 3.137-3.82 0-6.53-2.687-6.53-5.556 0-.12.004-.239.013-.356l.115-1.55c.285-1.655 1.026-3.499 2.063-5.315 1.302-2.28 2.962-4.33 4.404-5.66 1.217 1.029 2.487 2.541 3.583 4.274a5.807 5.807 0 011.71-.571c-1.255-2.061-2.777-3.905-4.285-5.148a1.594 1.594 0 00-2.096.062c-2.843 2.58-6.32 7.567-7.101 12.022-.07.4-.119.796-.143 1.185a9.142 9.142 0 00-.018.569v.001h.018a6.55 6.55 0 000 .975C1.802 19.987 5.395 23 9.785 23z"
                  fill="currentColor"
                ></path>
                <path
                  d="M17.73 9.495a.877.877 0 00-1.755 0v.585h-.585a.877.877 0 100 1.754h.585v.585a.877.877 0 001.754 0v-.585h.585a.877.877 0 100-1.755h-.585v-.584z"
                  fill="currentColor"
                ></path>
                <path
                  clip-rule="evenodd"
                  d="M5.887 13.282c.484 0 .877.393.877.877v.975c0 1.4 1.134 2.534 2.534 2.534h.488a.877.877 0 010 1.755h-.488a4.289 4.289 0 01-4.289-4.29v-.974c0-.484.393-.877.878-.877z"
                  fill="currentColor"
                  fill-rule="evenodd"
                ></path>
              </svg>
            </div>
            <div class="ml-4 space-y-1">
              <h3 class="text-base leading-5 font-semibold">
                <a
                  class="helper-link-cover"
                  href="https://docs.google.com/forms/d/e/1FAIpQLScDShI4BtBcA3dgMJhCJPs2fBl5wXoaR7kMspapNZdYKFOugA/viewform"
                  rel="nofollow noopener noreferrer"
                  target="_blank"
                  >Daftar Donor Darah</a
                >
              </h3>
              <p class="text-sm leading-4 text-gray-500">
                Berdonor darah plasma konvalesen (hanya diisi oleh calon
                pendonor)
              </p>
            </div>
            <div
              aria-hidden="true"
              class="flex flex-none items-center justify-center ml-2"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
                aria-hidden="true"
                class="w-6 h-6 text-blue-700"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
          </li>
          <li
            class="flex flex-row relative py-4 border-b border-gray-100 last-of-type:border-b-0"
          >
            <div
              aria-hidden="true"
              class="flex flex-none items-center justify-center w-12 h-12 bg-blue-50 rounded-full"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
                class="w-6 h-6 text-blue-700"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"
                ></path>
              </svg>
            </div>
            <div class="ml-4 space-y-1">
              <h3 class="text-base leading-5 font-semibold">
                <a
                  class="helper-link-cover"
                  href="https://www.indorelawan.org/activity/60e2ed45164da80018b0e246"
                  rel="nofollow noopener noreferrer"
                  target="_blank"
                  >Daftar Jadi Relawan</a
                >
              </h3>
              <p class="text-sm leading-4 text-gray-500">
                Gabung jadi relawan untuk mengumpulkan data dan menjawab
                pertanyaan warga via hotline
              </p>
            </div>
            <div
              aria-hidden="true"
              class="flex flex-none items-center justify-center ml-2"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
                aria-hidden="true"
                class="w-6 h-6 text-blue-700"
              >
                <path
                  fill-rule="evenodd"
                  d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </div>
          </li>
        </ul>
        <div class="p-4 bg-blue-50 text-center rounded-md space-y-3">
          <p class="text-base leading-6 font-semibold">Mau Upload Info?</p>
          <a
            class="flex flex-row px-4 py-2 text-base rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
            href="https://docs.google.com/forms/d/e/1FAIpQLSc_m0WyokBk8xv9jBwYFN1zAt4_u-kE2TI9ZBrAokB4E08AGw/viewform"
            rel="nofollow noopener noreferrer"
            target="_blank"
            >Tambahkan info di sini</a
          >
        </div>
      </section>
    </div>

    <!-- Section Donasi Warga Terdampak -->
    <div class="bg-white mb-3">
      <section class="overflow-hidden px-4 py-6 pb-4 space-y-4">
        <h2 class="text-lg sm:text-xl font-semibold">Donasi Warga Terdampak</h2>
        <div class="grid grid-cols-2 gap-4">
          <div
            class="flex flex-col shadow-md rounded-md overflow-hidden max-w-xs"
          >
            <div class="flex-shrink-0">
              <div
                style="
                  display: inline-block;
                  max-width: 100%;
                  overflow: hidden;
                  position: relative;
                  box-sizing: border-box;
                  margin: 0;
                "
              >
                <div
                  style="
                    box-sizing: border-box;
                    display: block;
                    max-width: 100%;
                  "
                >
                  <img
                    alt=""
                    aria-hidden="true"
                    :src="require('@/assets/img/card/card-image1.jpg')"
                  />
                </div>
              </div>
            </div>
            <div class="p-3 space-y-1 h-0 flex-1">
              <p class="text-gray-500 text-xs sm:text-sm">COVID-19</p>
              <h3 class="font-semibold text-gray-700 text-sm sm:text-base">
                Donasi untuk berbagai kebutuhan (RS, puskesmas, nakes, dan warga
                terdampak)
              </h3>
            </div>
            <div class="p-3 justify-center">
              <a
                class="flex flex-row px-2.5 py-1.5 text-xs rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 font-normal"
                data-testid="donation-button-Donasi untuk berbagai kebutuhan (RS, puskesmas, nakes, dan warga terdampak)"
                href="https://kitabisa.com/campaign/daruratcovid2021"
                rel="nofollow noopener noreferrer"
                target="_blank"
                >Donasi Sekarang</a
              >
            </div>
          </div>
          <div
            class="flex flex-col shadow-md rounded-md overflow-hidden max-w-xs"
          >
            <div class="flex-shrink-0">
              <div
                style="
                  display: inline-block;
                  max-width: 100%;
                  overflow: hidden;
                  position: relative;
                  box-sizing: border-box;
                  margin: 0;
                "
              >
                <div
                  style="
                    box-sizing: border-box;
                    display: block;
                    max-width: 100%;
                  "
                >
                  <img
                    style="
                      max-width: 100%;
                      display: block;
                      margin: 0;
                      border: none;
                      padding: 0;
                    "
                    alt=""
                    aria-hidden="true"
                    :src="require('@/assets/img/card/card-image2.jpg')"
                  />
                </div>
              </div>
            </div>
            <div class="p-3 space-y-1 h-0 flex-1">
              <p class="text-gray-500 text-xs sm:text-sm">COVID-19</p>
              <h3 class="font-semibold text-gray-700 text-sm sm:text-base">
                Donasi untuk Inisiatif #WargaBantuWarga
              </h3>
            </div>
            <div class="p-3 justify-center">
              <a
                class="flex flex-row px-2.5 py-1.5 text-xs rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 font-normal"
                data-testid="donation-button-Donasi untuk Inisiatif #WargaBantuWarga"
                href="https://kitabisa.com/campaign/wargabantuwarga"
                rel="nofollow noopener noreferrer"
                target="_blank"
                >Donasi Sekarang</a
              >
            </div>
          </div>
        </div>
        <div class="p-4 text-center space-y-3">
          <h3 class="text-blue-700 leading-5 font-semibold">
            <a href="/donasi">Lihat Selengkapnya</a>
          </h3>
        </div>
      </section>
    </div>

    <div class="bg-white mb-3">
      <div class="px-4 py-6">
        <a
          href="https://sembako.wargabantuwarga.com"
          rel="nofollow noopener noreferrer"
          target="_blank"
        >
          <div>
            <img
              alt="Telemedicine Gratis (Inisiatif Beberapa Dokter) - Cek Sekarang"
              :src="require('@/assets/img/banner-3.png')"
              class="w-full"
            />
          </div>
        </a>
      </div>
    </div>

    <div class="bg-white mb-3">
      <div class="px-4 py-6 text-center overflow-hidden space-y-4">
        <h2 class="font-semibold">
          Download aplikasi telemedicine yang <br />
          didukung Kemenkes:
        </h2>
        <ul class="grid grid-cols-2 gap-2 sm:gap-4 sm:grid-cols-4">
          <li
            v-for="(sponsor, index) in sponsors"
            :key="index"
            class="inline-flex flex-col items-center justify-center text-center relative"
          >
            <a
              href="https://bit.ly/alodokter-isoman"
              class="border-solid border-2 border-gray-300 border-opacity-75 rounded-lg hover:border-blue-700 min-w-full h-20 relative"
              target="_blank"
            >
              <div class="inline-block max-w-full box-border">
                <div class="box-border block max-w-full">
                  <img
                    :src="require(`@/assets/img/sponsor/${sponsor.img}`)"
                    :alt="sponsor.alt"
                    class="rounded-md absolute top-0 bottom-0 left-0 right-0 box-border px-6 m-auto block object-contain min-w-full max-w-full min-h-full max-h-full"
                  />
                </div>
              </div>
            </a>
          </li>
        </ul>
        <div class="p-4 bg-blue-50 text-center rounded-md space-y-3">
          <p class="text-base leading-6 font-semibold">
            Butuh Konseling Bagi Pasien, Keluarga Pasien, atau Tenaga Kesehatan
            Terdampak COVID-19?
          </p>
          <a
            class="flex flex-row px-4 py-2 text-base rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
            href="/telekonseling"
            >Lihat daftar di sini</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'IndexPage',
  data() {
    return {
      sponsors: [
        {
          img: 'Alodokter.png',
          alt: 'Alodokter',
        },
        {
          img: 'Halodoc.png',
          alt: 'Halodoc',
        },
        {
          img: 'Getwell.png',
          alt: 'Getwell',
        },
        {
          img: 'Klinikgo.png',
          alt: 'Klinikgo',
        },
        {
          img: 'Klikdokter.png',
          alt: 'Klikdokter',
        },
        {
          img: 'GrabHealth.png',
          alt: 'GrabHealth',
        },
        {
          img: 'LinkSehat.png',
          alt: 'LinkSehat',
        },
        {
          img: 'GoodDoctor.png',
          alt: 'GoodDoctor',
        },
        {
          img: 'Milvik.png',
          alt: 'Milvik',
        },
        {
          img: 'Prosehat.png',
          alt: 'Prosehat',
        },
        {
          img: 'SehatQ.png',
          alt: 'SehatQ',
        },
        {
          img: 'YesDok.png',
          alt: 'YesDok',
        },
      ],
    }
  },
}
</script>
