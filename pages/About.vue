<template>
    <div class="About">
      <Navbar />
      <section class="content">
        <h2>About Me</h2>
        <p>
          I am a student pursuing a Bachelor's Degree in Information Technology. I have a passion for technology, coding, and continuous learning. This portfolio showcases some of my projects and skills.
        </p>
        <p>
          In my studies, I have focused on areas such as data analysis, software development, and information management. I am always eager to take on new challenges and expand my knowledge.
        </p>
        <h3> Skills
            <p class="TSkills">
                Technical skills:
                <ul>
                    <li>Programming Languages: Java, Python, C++, C#, JavaScript</li>
                    <li>Web Development: HTML, CSS, Nuxt, Vue</li>
                    <li>Database Management: SQL, PostgreSQL, SQLite</li>
                    <li>Tools and Technologies: Git, GitHub</li>
                    <li>Operating Systems: Windows</li>
                </ul>
            </p>

            <p class="SSkills">
                Soft skills:
                <ul>
                    <li>Problem Solving</li>
                    <li>Teamwork and Collaboration</li>
                    <li>Communication Skills</li>
                    <li>Time Management</li>
                    
                </ul>
            </p>

        </h3>
      </section>
    </div>
  </template>
  
  <script>
  import Navbar from './Navbar.vue'
  
  export default {
    components: {
      Navbar
    }
  }
  </script>
  
  <style scoped>
  .About {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f0f0f0;
    color: #333;
  }
  
  .content {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  h2 {
    text-align: center;
    margin-bottom: 1em;
  }
  
  p {
    margin-bottom: 1em;
    line-height: 1.6;
  }

.h3{
    margin-bottom: 1em;
    line-height: 1.6;
    font-size: 1.5em;
    font-style: bold;
}
li{
    font-size: 0.9em;
}

.SSkills, .TSkills{
    text-align: left;
}

  </style>
  