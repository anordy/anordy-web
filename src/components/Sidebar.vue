<template>
    <div id="sidebar">
        <div class="img">
            <img src="https://img.freepik.com/free-vector/businessman-profile-cartoon_18591-58479.jpg?size=338&ext=jpg" height="180px" width="180px" class="img-fluid" alt="">
            </div>

           <b-nav class="text-center"  vertical v-b-scrollspy:nav-scroller>
           <b-nav-item href="#about" @click="scrollIntoView">ABOUT</b-nav-item>
           <b-nav-item href="#expirience" @click="scrollIntoView">EXPIRIENCE</b-nav-item>
           <b-nav-item href="#education" @click="scrollIntoView">EDUCATION</b-nav-item>
           <b-nav-item href="#skills" @click="scrollIntoView">SKILLS</b-nav-item>
           <b-nav-item href="#interest" @click="scrollIntoView">INTEREST</b-nav-item> 
           <b-nav-item href="#awards" @click="scrollIntoView">AWARDS</b-nav-item> 

           </b-nav>
        </div>
</template>


<script>

export default {
    name: 'sidebar',
    
}
</script>


<style  scoped>
*{
  box-sizing: border-box;
}
.img{
    margin-top: 190px;
    margin-left: 60px;
    background-color: rgba(255,255,255,.2);
    height: 190px;
    width: 190px;
    border-radius: 190px ;
    position: relative;


}
.active {
  color: white;
}
img{
  position: absolute;
  overflow: hidden;
  border-radius: 180px;
  padding-left: 15px;
  padding-top: 15px;
}
nav > ul{
  list-style-type: none;
}
li > a {
  color: rgba(255,255,255,.5);
  font-weight: 500;
}


</style>