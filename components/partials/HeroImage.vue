<template>
  <a :href="href" rel="nofollow noopener noreferrer" target="_blank">
    <div>
      <img alt="alt" :src="require(`@/assets/img/${imgSrc}`)" class="w-full" />
    </div>
  </a>
</template>

<script>
export default {
  props: {
    href: {
      type: String,
      required: true,
    },
    alt: {
      type: String,
      default: '',
    },
    imgSrc: {
      type: String,
      required: true,
    },
  },
}
</script>
