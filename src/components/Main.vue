<template>
<main class="main">
        <img src="/src/assets/gLogo.png" class="logo" />

        <div class="searchBar">
            <img src="src/assets/search.png" class="searchIcon" />
            <input type="search" class="searchInput" />
            <img src="/src/assets/keyboard.png" class="keyboardIcon" />
            <img src="/src/assets/mic.png" class="micIcon" />
        </div>

        <div class="buttons">
            <button class="button">Căutare Google</button>
            <button class="button">Mă simt norocos</button>
        </div>

        <div class="languages">
            <p>Google oferit în: </p>
            <div class="language">
                <a class="lang" href="">English</a>
                <a class="lang" href="">magyar</a>
                <a class="lang" href="">Deutsch</a>
            </div>
        </div>
    </main>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<style>
@import '/src/styles/main.css';
</style>