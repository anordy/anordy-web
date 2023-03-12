<template>
    <div id="about">
          <h1 class="display-4 bold" id="anord">ANORD <Span style="color: #bd5d38;">PATRICK</Span></h1>
          <h6 class="display-6 " style="color: #868e96;">KOBE STREET SINZA, +255 (716) 121 (689), +255 (765) 639 (173) <a>anordypatrick98@gmail.com</a></h6>
          <p class="mt-5" style="color: #868e96;">I am a highly competent IT professional with a proven track record in designing and developing <br>
             Web application , mobile applications, websites, APIs and managing databases. I have strong <br> technical skills as well as excellent interpersonal skills, enabling me to interact with a wide <br> range of people. 
   </p>

   <div class="social-icon">
      <div class="row">
     <a class="social" href="https://www.linkedin.com/in/anord-patrick-96a294157/"><i class="fab fa-linkedin-in"></i></a>
     <a class="social" href="https://github.com/anordy"><i class="fab fa-github"></i></a>
    <!-- <a class="social"><i class="fab fa-twitter"></i></a> -->
     <!-- <a class="social"><i class="fab fa-facebook-f"></i></a> -->
      </div>
   </div>
   
       
   

    </div>
</template>


<script>

export default {
    name: 'about'
}
</script>


<style  scoped>
#about {
    padding-top: 140px;
}
.bold {
    font-weight: 600;
}

i{
    padding: 17px;
    color: white;
    font-size: 25px;
}
.social-icon {
    height: 70px;
    width: 400px;
    margin-left: 20px;
 
}
.social {
    height: 60px;
    width: 60px;
    background-color: #495057;
    border-radius: 60px;
    margin-left: 10px;
}
.social:hover {
    background-color: #bd5d38;
    cursor: pointer;
}

</style>