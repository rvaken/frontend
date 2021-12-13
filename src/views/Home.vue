<template>
  <div class="home">
    <div class="home-header"></div>
    <div class="home-body">
      <Blogpost
        class="body-post"
        v-for="post in posts"
        :key="post.id"
        :username="post.username"
        :blogpost="post.blogpost"
      />
    </div>
    <div class="home-footer"></div>
  </div>
</template>

<script>
import Blogpost from "@/components/Blogpost.vue";

export default {
  name: "Home",
  components: {
    Blogpost,
  },
};
</script>

<style lang="scss">
.home {
  .home-header {
  }

  .home-body {
    .body-post {
    }
  }

  .home-footer {
  }
}
</style>
