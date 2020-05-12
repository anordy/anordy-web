<template>
    <div id="content">
        <About/>
       <Expirience/>
        <Education/>
         <Skills/>
        <Interest/>
         <Awards/>

    </div>
</template>


<script>
import About from './About';
import Expirience from './Expirience';
import Education from './Education';
import Skills from './Skills';
import Interest from './Interest';
import Awards from './Awards';




export default {
    name: 'content',
    components: {
        About,
     Expirience,
      Education,
        Skills,
        Interest,
        Awards,

    }
}
</script>



<style scoped>
*{
    box-sizing: border-box;
}
    
</style>