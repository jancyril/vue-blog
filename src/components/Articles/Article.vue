<template>
  <div class="article-component">
    <div class="card article">
        <article-details></article-details>
        <article-contents></article-contents>
      </div>
    </div>
  </div>
</template>


<script>
import ArticleDetails from './ArticleDetails'
import ArticleContents from './ArticleContents'

export default {
    components: {
        ArticleDetails,
        ArticleContents
    }
}
</script>
