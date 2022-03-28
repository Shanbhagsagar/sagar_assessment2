<template>
<v-app id="home" :style="{background: $vuetify.theme.themes.dark.background}">
 <MainNavbar />
 <v-container fluid>
   <v-row>
     <v-col cols="6">
      <v-img src="profile_photo.png" contain max-height="500"></v-img>
     </v-col>
     <v-col cols="6">
       <h3 class="red--text text-darken-4 top"> Hello I m Shanbhag Sagar Ravikiran</h3>
       <h2 class="white--text"> 
  <div class="wrapper">
    <div class="static-txt">I'm a</div>
    <ul class="dynamic-txts">
      <li><span>Web</span></li>
      <li><span>Java</span></li>
      <li><span>Flutter</span></li>
     </ul>&nbsp;&nbsp;
    <div class="static-txt">Developer</div>
  </div>
       </h2>
       <p class="grey--text">
        Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.
       </p>
       <center>
        <v-btn rounded large elevation="4" color="#A7121D" dark>About me</v-btn>
        </center>
     </v-col>
     <v-col cols="12" class="padd">
       <div class="first" id="about">
         <v-row>
           <v-col cols="12">
             <div class="child bgColor1" data-aos="fade-up" data-aos-delay="500">
                 <v-icon color="#A7121D" x-large class="ml-3">
                   mdi-palette-swatch
                 </v-icon>
                 <h3 class="white--text ml-3 mt-4">UI Design</h3>
                 <p class="grey--text ml-3 mt-6 text-justify">
Lorem ipsum is placeholder text <br/> commonly used in the graphic, <br/>print, and publishing industries <br/> for previewing layouts and visual <br/> mockups.
                 </p>
                 <v-btn color="#A7121D" dark text>
                   know more
                   <v-icon right>mdi-arrow-right</v-icon>
                 </v-btn>  
             </div>
              <div class="child bgColor2" data-aos="fade-up" data-aos-delay="500">
                 <v-icon color="#ffffff" x-large class="ml-3">
                   mdi-shopping
                 </v-icon>
                 <h3 class="white--text ml-3 mt-4">Product Design</h3>
                 <p class="grey--text ml-3 mt-6 text-justify">
                   Lorem ipsum is placeholder text <br/> commonly used in the graphic, <br/>print, and publishing industries <br/> for previewing layouts and visual <br/> mockups.
                 </p>
                 <v-btn class="white--text" dark text>
                   know more
                   <v-icon right>mdi-arrow-right</v-icon>
                 </v-btn>  
             </div>
             <div class="child bgColor1" data-aos="fade-up" data-aos-delay="500">
                 <v-icon color="#A7121D" x-large class="ml-3">
                   mdi-book-open-page-variant
                 </v-icon>
                 <h3 class="white--text ml-3 mt-4">Branding</h3>
                 <p class="grey--text ml-3 mt-6 text-justify">
                   Lorem ipsum is placeholder text <br/> commonly used in the graphic, <br/>print, and publishing industries <br/> for previewing layouts and visual <br/> mockups.
                 </p>
                 <v-btn color="#A7121D" dark text>
                   know more
                   <v-icon right>mdi-arrow-right</v-icon>
                 </v-btn>  
             </div>
           </v-col>
         </v-row>
         <v-row>
     <v-col cols="12" class="mt-10">
     <div class="child1">
       <h1 class="red--text text-darken-4 mt-4 number" data-aos="fade-up">1</h1>
       <h3 class="white--text mt-4">Years of Experience</h3>
     </div>
     <div class="child2">
       <v-row>
         <v-col cols="12" class="childcol">
           <div class="child2 mButton padding bgColor1">
             <h1 class="red--text text--darken-4" data-aos="fade-up">
               4+
             </h1>
             <p class="grey--text">Clients</p>
           </div>
         </v-col>
         <v-col cols="12" class="childcol">
           <div class="child2 padding bgColor1">
             <h1 class="red--text text--darken-4 counter" data-aos="fade-up">
               10+
             </h1>
             <p class="grey--text">Completed Projects</p>
           </div>
         </v-col>
       </v-row>
     </div>
         <div class="child2 mRight">
       <v-row>
         <v-col cols="12" class="childcol">
           <div class="child2 mButton padding bgColor1">
             <h1 class="red--text text--darken-4" data-aos="fade-up">
               10
             </h1>
             <p class="grey--text">Programming Languages</p>
           </div>
         </v-col>
         <v-col cols="12" class="childcol">
           <div class="child2 padding bgColor1">
             <h1 class="red--text text--darken-4" data-aos="fade-up">
               3+
             </h1>
             <p class="grey--text">Achievements</p>
           </div>
         </v-col>
       </v-row>
     </div>
        </v-col>
      </v-row>
       </div>
     </v-col>
     <v-col md="3" offset-md="3" id="project">
     <div data-aos="fade-up">
       <h4 class="white--text">FEATURED PROJECTS</h4>
       <p class="grey--text">Lorem ipsum is placeholder text</p>
    </div> 
     </v-col>
     <v-col md="3" class="text-end" data-aos="fade-up">
      <v-btn rounded color="#A7121D" dark>View All</v-btn>
     </v-col>
     <v-col md="3" offset-md="3">
       <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E" data-aos="fade-up" data-aos-delay="500">
         <v-img src="project1.png" height="220px"></v-img>
       </v-card>
     </v-col>
      <v-col md="3">
       <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E" data-aos="fade-up" data-aos-delay="500">
         <v-img src="project1.png" height="220px"></v-img>
       </v-card>
     </v-col>
      <v-col md="3" offset-md="3" data-aos="fade-up" data-aos-delay="500">
       <v-btn color="white" href="https://github.com/Shanbhagsagar/sahaayak_app" target="_blank" dark text class="ml-n4">
         Sahaayak
       </v-btn><br/>
       <v-btn color="#A7121D" dark text class="ml-n4">
         Know more
         <v-icon right>mdi-arrow-right</v-icon>
       </v-btn>
     </v-col>
      <v-col md="3" data-aos="fade-up" data-aos-delay="500">
       <v-btn color="white" dark text class="ml-n4">
         Hotel Management System
       </v-btn><br/>
       <v-btn color="#A7121D" href="https://github.com/Shanbhagsagar/HotelManagementSystem" target="_blank" dark text class="ml-n4">
         Know more
         <v-icon right>mdi-arrow-right</v-icon>
       </v-btn>
     </v-col>
     <v-col md="3" offset-md="3">
       <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E" data-aos="fade-up" data-aos-delay="500">
         <v-img src="project1.png" height="220px"></v-img>
       </v-card>
     </v-col>
      <v-col md="3">
       <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E" data-aos="fade-up" data-aos-delay="500">
         <v-img src="project1.png" height="220px"></v-img>
       </v-card>
     </v-col>
      <v-col md="3" offset-md="3" data-aos="fade-up" data-aos-delay="500">
       <v-btn color="white" dark text class="ml-n4">
         SDBMS
       </v-btn><br/>
       <v-btn color="#A7121D" href="https://github.com/Shanbhagsagar/StudentDatabaseManagementSystem" target="_blank" dark text class="ml-n4">
         Know more
         <v-icon right>mdi-arrow-right</v-icon>
       </v-btn>
     </v-col>
      <v-col md="3" data-aos="fade-up" data-aos-delay="500">
       <v-btn color="white" dark text class="ml-n4">
         Covid-19 App 
       </v-btn><br/>
       <v-btn color="#A7121D" href="https://github.com/Shanbhagsagar/Covid19_App" target="_blank" dark text class="ml-n4">
         Know more
         <v-icon right>mdi-arrow-right</v-icon>
       </v-btn>
     </v-col>
     <v-col cols="12" class="padd topInverse">
       <div class="second" >
         <div class="secondchild1" id="contact" data-aos="fade-up" data-aos-delay="500">
         <v-row>
           <v-col cols="7" >
             <h1 class="white--text">
               Let's work together on your next project
             </h1>
             <br/>
             <p class="white--text">
             Lorem ipsum is placeholder text Lorem ipsum is placeholder text<br/>
             </p>
           </v-col>
           <v-col cols="5">
             <v-btn rounded large color="#A7121D" dark class="mt-14" elevation="4" style="margin-left:150px">Contact</v-btn>
           </v-col>
         </v-row>
       </div>
       </div>
       <v-toolbar class="topTolbar" color="#111111" dark flat data-aos="fade-up" data-aos-delay="500">
         <div style="position: absolute; margin-left: auto; margin-right: auto; left: 0; right:0; text-align:center;">
           <v-btn text @click="scroll('home')">Home</v-btn>
           <v-btn text @click="scroll('project')">Project</v-btn>
           <v-btn text @click="scroll('about')">About</v-btn>
           <v-btn text @click="scroll('contact')">Contact</v-btn>
         </div>
       </v-toolbar>  
    </v-col>
   </v-row>
 </v-container>
 <MainFooter />
</v-app>
 
</template>

<script>
  import MainNavbar from '../components/MainNavbar'
  import MainFooter from '../components/MainFooter'

  export default {
    name: 'HomeView',
    components: {
      MainNavbar,
      MainFooter
    },
    methods: {
            scroll(refName) {
                const element = document.getElementById(refName);
                element.scrollIntoView({behavior: "smooth"});
            }
      }
  }
</script>
<style scoped>

.top{
  margin-top: 180px;
}  

.topInverse{
  margin-top:  -250px;
}

.topTolbar{
  margin-top: 100px;
  text-align: center;
}

.first{
  width: 100%;
  height: 710px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}

.second{
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1{
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.child{
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.bgColor1{
  background-color: #1e1e1e;
}

.bgColor2{
  background-color: #ce1d2a;
}

.child1{
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2{
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight{
  margin-right: 8px;
}

.mButton{
  margin-bottom: 8px;
}

.padding{
  padding: 12px 0 !important;
}

.col-12 .padd{
  padding: 12px 0 !important;
}

.col-12 .childcol{
  padding: 0 !important;
}

h1.number{
  font-size: 50px;
  font-weight: bold;
}

.wrapper{
  display: flex;
}
.wrapper .static-txt{
  color: #fff;
  font-size: 60px;
  font-weight: 400;
}
.wrapper .dynamic-txts{
  margin-left:  0px;
  height: 90px;
  line-height: 90px;
  overflow: hidden;
}
.dynamic-txts li{
  list-style: none;
  color: #ffffff;
  font-size: 60px;
  font-weight: 500;
  position: relative;
  top: 0;
  animation: slide 12s steps(4) infinite;
}
@keyframes slide {
  100%{
    top: -360px;
  }
}
.dynamic-txts li span{
  position: relative;
  margin: 2px 0;
  line-height: 90px;
}
.dynamic-txts li span::after{
  content: "";
  position: absolute;
  left: 0;
  height: 100%;
  width: 100%;
  background: #111111;
  border-left: 2px solid #ffffff;
  animation: typing 3s steps(10) infinite;
}
@keyframes typing {
  40%, 60%{
    left: calc(100% + 30px);
  }
  100%{
    left: 0;
  }
}
</style>
