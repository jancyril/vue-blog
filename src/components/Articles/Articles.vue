<template>
    <div class="container articles-component">
        <section class="articles">
            <div class="column is-8 is-offset-2">
               <article-card></article-card>
            </div>
        </section>
    </div>
</template>

<script>
import ArticleCard from './Article'

export default {
    components: {
        ArticleCard
    }
}
</script>
