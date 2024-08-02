<template>
    <nav class="navbar">
      <ul class="nav-list">
        <li class="nav-item">
          <nuxt-link to="/" exact-active-class="active">Home</nuxt-link>
        </li>

        <li class="nav-item">
          <nuxt-link to="/About" exact-active-class="active">About</nuxt-link>
        </li>

        <li class="nav-item">
          <nuxt-link to="/Projects" exact-active-class="active">Projects</nuxt-link>
        </li>

        <li class="nav-item">
          <nuxt-link to="/Contact" exact-active-class="active">Contact</nuxt-link>
        </li>

        <li class="nav-item">
            <nuxt-link to="/Education" exact-active-class="active">Education</nuxt-link>
        </li>

      </ul>
    </nav>

  </template>







  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>





  
  <style scoped>
  .navbar {
    background-color: #696565;
    padding: 1em;
  }
  
  .nav-list {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 0;
    padding: 5px;
    border: #696565;
  }
  
  .nav-item {
    margin: 0 1em;
  }
  
  .nav-item a {
    color: #fff;
    text-decoration: none;
  }
  
  .nav-item a.active {
    border-bottom: 2px solid #fff;
  }
  
  .nav-item a:hover {
    border-bottom: 2px solid #bbb;
  }
  </style>
  