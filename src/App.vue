<template>
<div id="app">
     <Sidebar/>
   <Content/>
</div>
  
</template>

<script>
import Sidebar from '../src/components/Sidebar';
import Content from '../src/components/Content';

export default {
  name: 'app',
  components: {
    Content,
    Sidebar
  },
 
  
}



</script>

<style  scoped>
#sidebar {
  height: 100vh;
    width: 300px;
    background-color: #bd5d38;
    float: left;
    position: fixed;
}

#content{
      margin-left: 330px;

}
#sidebar::after {
   content: '';
   display: table;
   clear: both;
}

</style>