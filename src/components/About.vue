<template>
    <div id="about">
          <!--about-->
    <section id="about">
          <h1 class="display-4 bold" id="anord">ANORD <Span style="color: #bd5d38;">PATRICK</Span></h1>
          <h6 class="display-6 " style="color: #868e96;">04 KOBE STREET SINZA, PO 1069 +255 (765) 39 (173) <a>anordypatrick98@gmail.com</a></h6>
          <p class="mt-5" style="color: #868e96;">I am experienced in leveraging agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to <br> corporate strategy foster collaborative thinking to further the overall value proposition.
   </p>

   <div class="social-icon">
      <div class="row">
     <a class="social"><i class="fab fa-linkedin-in"></i></a>
     <a class="social"><i class="fab fa-github"></i></a>
    <a class="social"><i class="fab fa-twitter"></i></a>
     <a class="social"><i class="fab fa-facebook-f"></i></a>



      </div>
   </div>
   
       
   

    </section>

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
 
}
.social {
    height: 60px;
    width: 60px;
    background-color: #495057;
    border-radius: 60px;
    margin: 10px;
}
.social:hover {
    background-color: #bd5d38;
    cursor: pointer;
}

</style>