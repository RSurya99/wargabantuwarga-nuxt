<template>
  <li
    class="inline-flex flex-col items-center justify-center text-center relative shadow-lg rounded-lg py-3 px-2 cursor-pointer"
  >
    <div aria-hidden="true" class="flex items-center justify-center h-10 w-10 bg-blue-100 rounded-full">
      <img :src="require(`@/assets/img/icon/${menuCard.svg}`)" class="h-6 w-6 text-blue-700 fill-current" />
    </div>
    <a class="text-gray-900 font-semibold text-xs mt-3 helper-link-cover" :href="menuCard.href">{{ menuCard.title }}</a>
  </li>
</template>

<script>
export default {
  props: {
    menuCard: {
      type: Object,
      required: true,
    },
  },
}
</script>
