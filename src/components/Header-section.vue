<script setup>

</script>

<template>
        <header class="header">
      <img class="logo" src="@/assets/MyImage/logo.png" alt="the brand logo">

      <nav class="header__nav">
        <ul class="header__nav-list">
          <li class="header__nav-item">About</li>
          <li class="header__nav-item">Services</li>
          <li class="header__nav-item">Projects</li>
          <li class="header__nav-item"><button>Contacts</button></li>
        </ul>
      </nav>
    </header>
</template>

<style scoped>



.header {
  background-color: #4abdf3;
  display: flex;
  align-items: center;
  min-height: 3.5rem;
  padding-top: 2.125rem;
  padding-left: 2.5rem;
  padding-right: 2.5rem;
  max-width: 1340px;
  margin: auto 0;
  max-width: 1440px;
}

.header__nav {
  margin-left: auto;
}

.header__nav-list {
  display: flex;
  align-items: center;
  list-style: none;
}


.header__nav-item {
  margin-right: 2.938rem;
  color: #fff;
  font-size: 15px;
  text-transform: capitalize;
}

.header__nav-item button {
  font-family: 'Fraunces';
  font-weight: 700;
  padding: 1rem 2rem;
  background-color: #fff;
  border: none;
  border-radius: 1.75rem;
  text-transform: uppercase;
}
</style>
