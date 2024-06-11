<template>
    <div>
        <div style="height: 75px;"><Navigation pageTitle="Article"></Navigation></div>

        <div style="height:5vh;">
            <div name="ArticleSearch" class="article-search">
                <div name="searchBar" style="display: inline;">
                    <input type="text" class="search-bar">
                </div>
                <div name="searchButton" style="display: inline;">
                    <button class="search-btn">Search</button>
                </div>
                <div name="searchFilter" style="display: inline;">
                    <button class="filter-btn">☰</button>
                </div>
            </div>
        </div>

        <div name="ArticleNavigation" class="sidebar-left">
            <p>Article Nav</p>
        </div>

        <div name="RelatedArticles" class="sidebar-right"> <p>Related Articles</p> </div>

        <div name="Article" class="article">
            <div name="articleTitle" class="article-title">
                <h1>Title</h1>
            </div>
            <div name="articleImage">
                <div name="img" class="article-image">
                    <img src="https://globalnews.ca/wp-content/uploads/2021/02/The-Tragically-Hip-Press-Photo-1.jpg?quality=85&strip=all" class="image-size">
                </div>
                <div name="imgDescription" class="image-description">
                    <p name="imgDescription" class="image-description">Image Description</p>
                </div>
            </div>
            <div name="articleContent" class="article-content">
                <p class="article-subtitle">H1</p>
                <p class="article-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                <p class="article-subtitle">H1</p>
                <p class="article-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

.article-search {
    background-color: #F4f4f4;
    position: fixed;
    width: 100%;
    padding-top: 1%;
    padding-bottom: 1%;
    align-items: center;
    text-align: center;
}

.search-bar {
    margin-right: 0.5%;
    width: 50%;
    font-size: large;
}

.search-btn {
    padding: 0.5%;
    margin-left: 0.5%;
    margin-right: 0.5%;
    font-size: large;
    border-style: none;
    border-radius: 5px;
    background-color: #0665AA;
    color: white;
}

.filter-btn {
    margin-left: 0.5%;
    height: 100%;
    font-size: large;
    border-style: none;
    border-radius: 5px;
    color: black;
    font-weight: bold;
}

.article {
    height: 85.5vh;
    overflow-y: scroll;
    -ms-overflow-style: none;  /* IE and Edge */
    scrollbar-width: none; 
}

.article-title {
    text-align: center;
}

.article-image {
    align-items: center;
    text-align: center;
}

.image-size {
    height: 40vh;
    max-width: 100%;
}

.image-description {
    text-align: center;
    font-size: medium;
}

.article-content {
    margin-left: 17%;
    margin-right: 17%;
}

.article-subtitle {
    font-size: x-large;
    font-weight: bold;
}

.article-text {
    font-size: large;
}

.sidebar-left {
    margin: 0;
    margin-left: 0.5%;
    padding: 0;
    width: 15%;
    background-color: #BDE3FF;
    position: fixed;
    height: 85%;
    overflow: auto;
    border-radius: 1dvh;
}

.sidebar-right {
    margin: 0;
    margin-right: 0.5%;
    padding: 0;
    right: 0;
    width: 15%;
    background-color: #0665AA;
    position: fixed;
    height: 85%;
    overflow: auto;
    border-radius: 1dvh;
}

/* Hide scrollbar but still allow scrolling */
.article::-webkit-scrollbar {
    width: 0;
    height: 0;
}

.article {
    -ms-overflow-style: none;  /* IE and Edge */
    scrollbar-width: none;  /* Firefox */
}

</style>
