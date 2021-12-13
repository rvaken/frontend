<template>
  <section class="blogpost">test</section>
</template>

<script>
export default {
  name: "Blogpost",

  props: {
    username: {
      type: String,
      default: "DefaultUser",
    },

    blogpost: {
      type: String,
      default: "",
    },
  },
};
</script>

<style lang="scss">
.blogpost {
}
</style>
