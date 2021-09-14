<template>
<header class="header">
        <nav class="navBar">
            <ul class="navLinks">
                <li><a href="#" class="navLink">Gmail</a></li>
                <li><a href="#" class="navLink">Imagini</a></li>
            </ul>
            <div class="aplicatii">
                <img src="../assets/aplicatii.png" />
            </div>
            <div class="cont">
                <img src="../assets/cont.png" style="border-radius: 50%;" />
            </div>
        </nav>
    </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<style>
@import '/src/styles/header.css';
</style>