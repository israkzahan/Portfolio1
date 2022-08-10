<template>
<v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background}">
<navbar-world />

<v-container fluid>
  <v-row>
    <v-col cols="4">
      <v-img src="israk.jpg" contain max-height="500"> </v-img>
    </v-col>
    <v-col cols="6">
      <h2 class="blue--text text-darken-4 top">Assalamu Alaikum, I'm Israk Zahan Monisha</h2>
      <h1 class="green--text"> Graduate Student</h1>
      <p class="headline">
         I recently completed my BSc in Computer Science and Engineering from East West University, Bangladesh in May,2022.  Now I am looking for a job.
         My home town is Magura.
      </p>
      <v-btn tile color="#A7121D" dark> About me</v-btn>
    </v-col>
    <v-col cols="12" class="padd" id="education">
     <div class="first">
       <v-row>
         <h1 class="black--text ml-5 mt-10"> Education </h1>
         <v-col cols="12">
            <div class="child bgcolor1">
              <v-icon color="#A7121D" x-large class="ml-3">
                mdi-book-open-page-variant
                </v-icon>
                <h2 class="blue--text ml-3 mt-4"> B.Sc </h2>
                <p class="black--text ml-3 mt-6">
                  Completed my BSc degree<br> in Computer Science and <br> Engineering from East West University.
                </p>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
            <div class ="child bgcolor2">
               <v-icon  color="#A7121D" x-large class="ml-3" dark>
               mdi-book-open-page-variant
                </v-icon>
                <h2 class="blue--text ml-3 mt-4"> H.S.C </h2>
                <p class="black--text ml-3 mt-6">
                  HSC under Jessore board<br> from Science group with<br> GPA 4.17 out of 5. Passed in 2016.
                </p>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                </v-btn>
            </div>
            <div class ="child bgcolor1">
               <v-icon color="#A7121D" x-large class="ml-3" dark>
                mdi-book-open-page-variant
                </v-icon>
                <h2 class="blue--text ml-3 mt-4"> S.S.C </h2>
                <p class="black--text ml-3 mt-6">
                  SSC under Jessore board<br> from Science group with <br> GPA 5 out of 5. Passed in 2014
                </p>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                </v-btn>
            </div>
          </v-col>
          <h1 class="white-text ml-3 mt-4"> Skills </h1>
          <v-col cols="12" class="padd mt-10">
            <div class="child1" id="skills">
              <h2 class="blue--text ml-5 mt-10"> Programming Language </h2>
              <ul class="black--text ml-3 mt-6">
                  <li>	C/ C++, Python, PHP, JAVA, HTML  </li>
                </ul>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                  </v-btn>
            </div>
             <div class="child1">
              <h2 class="blue--text ml-5 mt-10"> Frameworks and Libraries </h2>
              <ul class="black--text ml-3 mt-6">
                  <li>Django: Proficient in making CRUD web application.<br></li>
                  <li>BOOTSTRAP-5: Understand the basic designing concept<br></li>
                  <li>CSS: Understand the basic designing concept.<br> </li>
                </ul>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                  </v-btn>
            </div>
            <div class="child1">
              <h2 class="blue--text ml-5 mt-10"> Software Testing Tools </h2>
              <ul class="black--text ml-3 mt-6">
                  <li>Postman: Proficient to create Test cases, Test plan.<br></li>
                  <li>Cypress: Proficient to write automated web test.<br></li>
                </ul>
                <v-btn color="#A7121D" dark text>
                  Know more 
                  <v-icon right> mdi-arrow-right</v-icon>
                  </v-btn>
            </div>
          </v-col>
          <h1 class="white-text ml-3 mt-4" id="projects"> Projects </h1>
          <v-col cols="12" class="mt-10">
            <div class="second">
              <h2 class="blue--text ml-3 mt-4"> Project Details </h2>
              <ul class="black--text ml-3 mt-6">
                <b>	1. “Course Management System”</b>-using python language and mongoDB database.<br><br>
                            <ul > 
                              <li>In this projects students can add their courses, delete  <br> their courses.
                              Also students can see their course list.
                              </li>   
                          </ul>
                      <br>
                <b>	2. Develop an E-Commerce site- “ReviewChecker” </b>-Using PHP and mysql database.<br><br>
                            <ul > 
                              <li>In this projects customer's can add their <br> product review, and see all product details.
                              </li>   
                          </ul>
                           
                      <br>
                <b>	3. Develop an E-Commerce site- “UnityTraveller”  </b>-Using python language and Django framework.<br><br>
                            <ul>
                              <li>In this projects customer's can add their <br> product review, and see all product details.
                              </li>   
                         </ul>
                </ul>
            </div>
          </v-col>
          <h1 class="black--text ml-3 mt-4"> Research-Work </h1>
          <v-col cols="12" class="mt-10">
            <div class="second1" id="researchwork" >
              <h2 class="blue--text ml-2 mt-2"> Research Topic- Text Mining </h2>
              <h4 class="black--text ml-3 mt-4"> A cluster-Based system for discovering the similar Text Documents. </h4>
              <b>Developed in:</b> Python Programming Language.<br>
              <b>Short Description:</b> Developed an API, where users will give a document as <br>
              input then they get a list of similar types of all documents as output.
            </div>
          </v-col> <br><br>
          <h1 class="white-text ml-3 mt-4"> Contact </h1> <br>
          <v-col cols="12" class="mt-10">
            <div class="second1" id="contact">
              <h2 class="blue--text ml-3 mt-4"> Contact Me </h2>
              Phone: +88 01753443558 <br>
              E-mail: israkzahan21@gmail.com
            </div>
          </v-col>
       </v-row>
     </div> 
    </v-col>
   </v-row>
  </v-container>
  <footer-world/>
</v-app>
</template>

<script>
  import NavbarWorld from '../components/NavbarWorld'
  import FooterWorld from '../components/FooterWorld'

  export default {
    name: 'HomeView',

    components: {
      NavbarWorld,
      FooterWorld
    },
  }
</script>
<style scoped>

.top{
  margin-top: 180px;
}

.topInverse{
  margin-top: -250px;
}
.topTolbar{
  margin-top: 100px;
  text-align:center;

}
.first {
  width:100%;
  height:100%;
  background:linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%,

  );
  text-align: center;
  padding: 2rem 2rem;
}


.second{
  width:100%;
  height:500px;
  background:'#90EE90';
  text-align: center;
  padding: 2rem 2rem;
}
.second1{
  width:100%;
  height:100px;
  background:'#00203FFF';
  text-align: center;
}

.secondchild{
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
bgcolor1{
  background-color: #1e1e1e
}
bgcolor2{
  background-color: #ce1d2a
}
.child1{
  display: inline-block;
  vertical-align: middle;
  margin-right: 5px;
  
}
.child2{
  display: inline-block;
  vertical-align: middle;
  width:245px;
}
.mRight{
  margin-right: 8px;
}
.mButton{
  margin-bottom: 8px
}
.padding{
  padding: 8px 0px;
}
.col-12.padd{
  padding: 12px 0 !important;
}
.col-12.childcol{
  padding: 0 !important;
}
h1.number{
  font-size: 50px;
  font-weight: bold;
}
.first1{
  width:100%;
  height:610px;
  background-color: '#90EE90';
}

</style>