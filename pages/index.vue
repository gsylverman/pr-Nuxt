<template>
  <div class="home-page">
    <section class="intro">
      Home Page
      <h1>get the latest teck news</h1>
    </section>

    <section class="featured-posts">
      <PostPreview
        thumbnail="https://images.unsplash.com/photo-1508558936510-0af1e3cccbab?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60"
        id="1"
        title="Title"
        previwText="Some text"
      />
      <PostPreview
        thumbnail="https://images.unsplash.com/photo-1508558936510-0af1e3cccbab?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60"
        id="2"
        title="Title"
        previwText="Some text"
      />
      <PostPreview
        thumbnail="https://images.unsplash.com/photo-1508558936510-0af1e3cccbab?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60"
        id="3"
        title="Title"
        previwText="Some text"
      />
    </section>
  </div>
</template>

<script>
import PostPreview from "~/components/Posts/PostsPreview";
export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-image: url("~assets/images/somewalp.jpg");
  background-position: center;
  background-size: cover;
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

</style>
