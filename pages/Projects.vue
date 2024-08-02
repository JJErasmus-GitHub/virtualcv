<template>
    <div class="Projects">
        
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



    
        const projects = ref ([
          { id: 1, title: 'CMPG 223 Group Project', description: 'Description of project one.' },
          
          
        ])
      
</script>







<style>

.Projects{
    max-width: 800px;
    background-color: rgba(95, 94, 94, 0.6);
    padding: 20px;
    color: black;
    margin: 0 auto;
    justify-content: center;

}
  
  
h2{
    text-align: center;
    color: white;
}

.Info, .Titles{
    text-align: center;
    margin-top: 2em;
    background: #222;
    padding: 20px;
    border-radius: 10px;
}




</style>














