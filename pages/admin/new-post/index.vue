<template>
  <div class="admin-page">
    <section class="new-post">
      <button>Create Post</button>
    </section>
    <section class="existing-posts">
      <h1>Existing</h1>
      <Postlist />
    </section>
  </div>
</template>

<script>
import PostList from "~/components/Posts/PostList";
export default {
  components: {
    Postlist
  }
};
</script>
