<template>
  <div class="px-4">
    <div class="rounded-sm">
      <a
        href="/kontak-darurat"
        class="flex flex-row relative py-5 px-4 border-gray-100 border-2 rounded-lg justify-between cursor-pointer"
      >
        <div class="flex flex-row items-center">
          <div aria-hidden="true" class="flex flex-none items-center justify-center w-12 h-12 bg-blue-50 rounded-full">
            <img :src="require('@/assets/img/icon/card.svg')" class="w-6 h-6" alt="" />
          </div>
          <div class="ml-4 space-y-1">
            <h3 class="text-base leading-5 font-semibold">
              <a class="helper-link-cover" href="/kontak-darurat">Kontak Darurat</a>
            </h3>
            <p class="text-sm leading-4 text-gray-500">Situs dan kontak penting terkait COVID-19</p>
          </div>
        </div>
        <div aria-hidden="true" class="flex flex-none items-center justify-center ml-2">
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
      </a>
    </div>
  </div>
</template>
