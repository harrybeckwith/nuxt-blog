<template>
  <section class="post-list">
    <PostPreview
      id="1"
      thumbnail="http://www.bpifrance.fr/var/bpifrance/storage/images/bpifrance/a-la-une/actualites/innovation-la-deep-tech-promet-des-changements-profonds-35589/712694-1-fre-FR/Innovation-la-deep-tech-promet-des-changements-profonds.png"
      title="hello"
      previewText="first post"
    />
    <PostPreview
      id="2"
      thumbnail="http://www.bpifrance.fr/var/bpifrance/storage/images/bpifrance/a-la-une/actualites/innovation-la-deep-tech-promet-des-changements-profonds-35589/712694-1-fre-FR/Innovation-la-deep-tech-promet-des-changements-profonds.png"
      title="hello"
      previewText="second post"
    />
    <PostPreview
      id="3"
      thumbnail="http://www.bpifrance.fr/var/bpifrance/storage/images/bpifrance/a-la-une/actualites/innovation-la-deep-tech-promet-des-changements-profonds-35589/712694-1-fre-FR/Innovation-la-deep-tech-promet-des-changements-profonds.png"
      title="hello"
      previewText="third post"
    />
  </section>
</template>


<script>
import PostPreview from "@/components/Posts/PostPreview";
export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>