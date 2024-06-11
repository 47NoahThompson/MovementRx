<template>
    <div>
        <h1>Article Search</h1>
    
        <div name="ArticleSearch">
            <div name="searchBar"> <p>Search Bar</p> </div>
            <div name="searchButton"> <button>Search</button> </div>
            <div name="searchFilter"> <p>☰</p> </div>
        </div>

        <div name="topThreeArticles">
            <div name="topArticle1">
                <p>Image</p>
                <p>Article 1</p>
            </div>
            <div name="topArticle2">
                <p>Image</p>
                <p>Article 2</p>
            </div>
            <div name="topArticle3">
                <p>Image</p>
                <p>Article 3</p>
            </div>
        </div>

        <div name="articleList">
            <div name="reading1">
                <p>Title</p>
                <p>Description</p>
            </div>
            <div name="reading2">
                <p>Title</p>
                <p>Description</p>
            </div>
            <div name="reading3">
                <p>Title</p>
                <p>Description</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>