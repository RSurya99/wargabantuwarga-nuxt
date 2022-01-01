<template>
  <article class="border border-gray-200 rounded-md p-4 space-y-4">
    <div class="space-y-2">
      <div class="flex flex-row text-base">
        <h3 class="flex-1 font-semibold text-gray-700 truncate">{{ article.title }}</h3>
        <span class="inline-block flex-none text-gray-500 ml-4">{{ article.date }}</span>
      </div>
      <div class="text-gray-600 text-sm">
        <p>{{ article.description }}</p>
      </div>
    </div>
    <a
      class="flex flex-row-reverse px-4 py-2 text-sm rounded-md items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
      :href="article.link"
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
      >{{ article.linkTitle }}</a
    >
  </article>
</template>
<script>
export default {
  props: {
    article: {
      type: Object,
      required: true,
    },
  },
}
</script>
