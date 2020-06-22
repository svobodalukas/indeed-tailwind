<template>
  <section id="properties">
    <h2>Properties</h2>
    <div>
      <article-item
        :article="item"
        v-for="item in articles"
        v-bind:key="item.title"
      />
    </div>
  </section>
</template>

<script>
import ArticleItem from "./ArticleItem";
export default {
  name: "Articles",
  components: {
    ArticleItem
  },
  data() {
    return {
      articles: [
        {
          title: "Super fancy flat",
          description:
            "A fully stocked kitchen with all modern amenities provides a peaceful cooking environment.",
          image: "./static/flat1.jpg"
        },
        {
          title: "Bright and sunny house",
          description:
            "A fully stocked kitchen with all modern amenities provides a peaceful cooking environment.",
          image: "./static/flat2.jpg"
        },
        {
          title: "Spacious and warm flat",
          description:
            "With three newly updated bedrooms you will be sleeping soundly during your stay.",
          image: "./static/flat3.jpg"
        },
        {
          title: "Perfect house in countryside",
          description:
            "A fully stocked kitchen with all modern amenities provides a peaceful cooking environment.",
          image: "./static/flat2.jpg"
        },
        {
          title: "Prague centre flat",
          description:
            "With three newly updated bedrooms you will be sleeping soundly during your stay.",
          image: "./static/flat3.jpg"
        },
        {
          title: "Krakovská street offices",
          description:
            "A fully stocked kitchen with all modern amenities provides a peaceful cooking environment.",
          image: "./static/flat1.jpg"
        }
      ]
    };
  }
};
</script>

<style scoped></style>
