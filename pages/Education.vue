<template>
    
    <div class="Education">
        <Navbar/>

        <section class="content">
            <h1>Education</h1>
                <p>
                    Outeniqua Highschool (2017-2021)
                </p>
                <p>
                    North-West University (2022-2024)
                </p>

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








<style>

.Education {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f0f0f0;
    color: #333;
  }

.content{
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1{
    text-align: center;
    margin-bottom: 1em;
}

p{
    text-align: center;
}

</style>






