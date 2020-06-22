<template>
  <div>
    <img :src="article.image" alt="flat 1" />
    <div>
      <h3>{{ article.title }}</h3>
      <p>
        {{ article.description }}
      </p>
      <button>
        Book a visit
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "ArticleItem",
  props: {
    article: Object
  }
};
</script>

<style scoped></style>
