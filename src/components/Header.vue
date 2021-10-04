<template>
  <header class="header">
    <div class="header__nav container">
        <a href="" class="logo">GoTrieop</a>
      <nav :class="{active: isActive}" class="nav">
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">Services</a></li>
          <li><a href="">Pricing</a></li>
          <li><a href="">Contact</a></li>
        </ul>
        <div class="header__btns">
          <button class="header__btn signup">Sign up</button>
          <button class="header__btn login">Login</button>
        </div>
      </nav>
      <div  class="burger">
        <span></span><span></span><span></span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
@import url(../assets/scss/header.scss);
@import url(../assets/scss/responsive.scss);
</style>
