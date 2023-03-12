<template>
  <div id="education">
    <h1 class="display-5 mt-5">EDUCATION</h1>
    <b-row cols="2">
      <b-col>
        <h5 class="display-6">UNIVERSTY OF DAR ES SALAAM</h5>
      </b-col>
      <b-col>
        <p class="display-6" id="date" style="color: #bd5d38;">
          Oct 2017 - June-2020
        </p>
      </b-col>
    </b-row>

    <h5 class="display-6" style="color:  #868e96;">BACHELOR OF SCIENCE WITH COMPUTER SCIENCE</h5>

    <p class="mt-4">
      Computer Science - Web Development Track
    </p>

    <b-row class="mt-5" cols="2">
      <b-col>
        <h5 class="display-6">PUGU SECONDARY SCHOOL</h5>
      </b-col>
      <b-col>
        <p class="display-6" id="date" style="color: #bd5d38;">
          May 2015 - May-2017
        </p>
      </b-col>
    </b-row>
    <h5 class="display-6" style="color:  #868e96;">A LEVEL</h5>

    <p class="mt-4">
      Science subjects Physics , Chemistry and Mathematics (PCM)
    </p>

    <b-row class="mt-5" cols="2">
      <b-col>
        <h5 class="display-6">KAYANGA SECONDARY SCHOOL</h5>
      </b-col>
      <b-col>
        <p class="display-6" id="date" style="color: #bd5d38;">
          Jan 2011 - Nov-2014
        </p>
      </b-col>
    </b-row>
    <h5 class="display-6" style="color:  #868e96;">O'LEVEL</h5>

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
  padding-top: 50px;
}

#date {
  float: right;
  margin-right: 160px;
}

p {
  color: #868e96;
}

.hr {
  margin-top: 180px;
}
</style>