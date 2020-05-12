<template>
    <div id="sidebar">
        <div class="img">
            <img src="https://img.freepik.com/free-vector/businessman-profile-cartoon_18591-58479.jpg?size=338&ext=jpg" height="180px" width="180px" class="img-fluid" alt="">
            </div>

           <nav class="navbar text-center" >
              <ul class="nav-bar">
                <li class="nav-item"><a href="#about"  class="nav-link active">ABOUT</a></li>
               <li class="nav-item"><a href="#expirience" class="nav-link">EXPIRIENCE</a></li>
                <li class="nav-item"><a href="#education" class="nav-link"> EDUCATION</a></li>
                <li class="nav-item"><a href="#skills" class="nav-link">SKILLS</a></li>
                <li class="nav-item"><a href="#interest" class="nav-link">INTEREST</a></li>
                <li class="nav-item"><a href="#awards" class="nav-link">AWARDS</a></li>

              </ul>
           </nav>
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
    margin-left: 40px;
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