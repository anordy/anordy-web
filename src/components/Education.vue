<template>
    <div id="education">
      <h1 class="display-5 mt-5">EDUCATION</h1>
       <b-row cols="2">
          <b-col>
             <h5 class="display-6">UNIVERSTY OF DAR ES SALAAM</h5>
          </b-col>
          <b-col>
            <p class="display-6" id="date" style="color: #bd5d38;">
              August 2006 - May-2010  
            </p>
          </b-col>
        </b-row>

        <h5 class="display-6" style="color:  #868e96;">BACHELOR OF SCIENCE WITH COMPUTER SCIENCE</h5>

        <p class="mt-4" >
         Computer Science - Web Development Track
        </p>

         <b-row class="mt-5" cols="2">
          <b-col>
             <h5 class="display-6">COLLEGE OF INFORMATION COMUNICATION AND TECHNOLOGY</h5>
          </b-col>
          <b-col>
            <p class="display-6" id="date" style="color: #bd5d38;">
              August 2006 - May-2010  
            </p>
          </b-col>
        </b-row>

        <h5 class="display-6" style="color:  #868e96;">BUSNESS SOFTWARE</h5>

        <p class="mt-3" >
        <br> generation X is on the runway heading towards a streamlined cloud solution. User generated content in 
        </p>
        <hr class="hr">
    </div>

</template>


<script>

export default {
    name: 'education'
}
</script>



<style  scoped>
#education {
    padding-top: 280px;
}
#date {
    float: right;
    margin-right: 160px;
}
p{
    color: #868e96;
}
.hr{
    margin-top: 180px;
}
</style>