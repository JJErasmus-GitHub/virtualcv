<template>
    <div class="home">
        <Navbar/>
      <header class="header">
        <img src="/assets/CV_image.jpg" alt="Profile Picture" class="profile-picture">
        <h1 class="name">Hanno Erasmus</h1>
        <p class="tagline">Aspiring Software Developer</p>
      </header>
  
      <section class="about">
        <h2>About Me</h2>
        <p>
          I am a student pursuing a Bachelor's Degree in Information Science. I have a passion for technology, coding, and continuous learning.
        </p>
      </section>
  
      <section class="projects">
        <h2>Projects</h2>
        <div class="project-list">
          <div class="project" v-for="project in projects" :key="project.id">
            <h3>{{ project.title }}</h3>
            <p>{{ project.description }}</p>
          </div>
        </div>
      </section>
  
      <section class="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:worsteinerasmus@gmail.com">worsteinerasmus@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/hanno-erasmus-709b19295/" target="_blank">Hanno Erasmus</a></p>
      </section>
    </div>
  </template>
  
  <script>

  import Navbar from './Navbar.vue';


  export default {
    components: {
        Navbar
    },
    data() {
      return {
        projects: [
          { id: 1, title: 'CMPG 212 Group Project', description: 'Description of project one.' },
          
          // Add more projects here
        ]
      }
    }
  }
  </script>
  
  <style scoped>
  .home {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  .header {
    text-align: center;
  }
  
  .profile-picture {
    border-radius: 50%;
    width: 150px;
    height: 150px;
  }
  
  .name {
    font-size: 2em;
    margin: 0.5em 0;
  }
  
  .tagline {
    color: #777;
  }
  
  .about, .projects, .contact {
    margin-top: 2em;
  }
  
  .project-list {
    display: flex;
    flex-direction: column;
  }
  
  .project {
    border: 1px solid #ccc;
    padding: 1em;
    margin-bottom: 1em;
  }
  
  a {
    color: #007bff;
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  </style>
  