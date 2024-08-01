<template>
    <div class="Projects">
        <Navbar/>
        <section class="Titles">
            <h2>Projects</h2>
                <div class="project-list">
                    <div class="project" v-for="project in projects" :key="project.id">
                        <h3>{{ project.title }}</h3>
                    </div>
                </div>
        </section>


        
        <section class="Info">
            <h2>Info</h2>
                <div class="project-list">
                    <div class="project" v-for="project in projects" :key="project.id">
                        <h3>{{ project.description }}</h3>
                    </div>
                </div>
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
          
          
        ]
      }
    }
  }

</script>







<style>

.Projects{
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f0f0f0;
    color: #333;
  }
  
h2{
    text-align: center;
}

.Info, .Titles{
    text-align: center;
    margin-top: 2em;
    background: rgba(189, 183, 183, 0.6);
    padding: 20px;
    border-radius: 10px;
}




</style>














