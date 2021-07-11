<template>
  <div class="summer-school">

    <div class="header-background">
    <div class="header-pic-img">
      <div class="header-content">
        <div class="header-article">
          <h1 class="tagline-header">Gradely Online<span> Summer</span><br> School</h1>
          <p class="tagline-paragraph">Help your child explore their curiosity in fun project-based
            virtual class led by dedicated and passionate professionals.</p>
            <button class="standard-button">Enroll</button>
        </div>
        <img class="sunset-image" src="../assets/waving_child.png">

      </div>
    </div>
  </div>
  <div class="second-page">
    <!-- <img src="../assets/activechild.png"> -->
    <iframe height="315" src="https://www.youtube.com/embed/6NMxADANn8k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <div class="second-article">
      <h2>Keep your child active and watch them grow.</h2>
      <p>Replace mindless videogaming and long boring hours with curiosity and creativity
        this summer. Engage your children's interests  with minimal demand of your time. </p>
        <button class="standard-button">Enroll</button>
    </div>
  </div>

  <div class="how-it-works">
    <h2>How it works</h2>
    <div class="icons">
    <div class="icon-box">
      <img src="../assets/magnifier.png" alt="Find a course">
      <div class="icon-box-article">
      <h3>Find a course</h3>
      <p>Join up to 3 classes based on your child's age group.</p>
    </div>
    </div>
    <div class="icon-box">
      <img src="../assets/learningGraph.png" alt="Project based lessons">
      <div class="icon-box-article">
      <h3>Project based lessons</h3>
      <p>Your child watches the weekly
        video lessons and practices the projects</p>
      </div>
    </div>
    <div class="icon-box">
      <img src="../assets/playVideo.png" alt="Weekly Q and A">
      <div class="icon-box-article">
      <h3>Weekly Q&amp;A</h3>
      <p>Your child joins the weekly group classes to get support
        from the facilitators.</p>
      </div>
    </div>
    <div class="icon-box">
      <img src="../assets/createProject.png" alt="Create Project">
      <div class="icon-box-article">
      <h3>Create project</h3>
      <p>Your child builds their project portfolio.</p>
    </div>
    </div>
  </div>
</div>

<div class="interest-led-classes">
  <h2>Interest-led classes your children will love!</h2>
  <div class="row">
    <div class="summerclass">
      <img class="summerclasses" src="../assets/coding.png" alt="">
      <h4>Coding</h4>
      <p>During these classes, your child
        will improve their logical thinking, creative thinking, and <span>...read more</span></p>
      <button class="standard-button">Enroll</button>
    </div>
    <div class="summerclass">
      <img  class="summerclasses" src="../assets/digitalDesign.png" alt="">
      <h4>Digital Design</h4>
      <p>Help your child release their creativity
        while building valuable communication skill for the  <span>...read more</span></p>
      <button class="standard-button">Enroll</button>
    </div>
    <div class="summerclass">
      <img  class="summerclasses" src="../assets/fineDining.png" alt="Plate of Food">
      <h4>Homemaking</h4>
      <p>This is for the enthusiastic
        food lovers that would like to engage their 5 senses. At the  <span>...read more</span></p>
      <button class="standard-button">Enroll</button>
    </div>
  </div>
  <div class="row">
    <div class="summerclass">
      <img  class="summerclasses" src="../assets/dance.png" alt="Girls dancing ballet in the sunlight">
      <h4>Dance</h4>
      <p>Your active and vibrant child will
        learn fun and enthralling dance styles that will come  <span>...read more</span></p>
      <button class="standard-button" @click="$refs.addchildName.openAddchild()">Enroll</button>
    </div>
    <div class="summerclass">
      <img  class="summerclasses" src="../assets/entrpreneurship.png" alt="">
      <h4>Entrepreneurship</h4>
      <p>For the creative problem solvers,
        this 5 week course will help your child understand  <span>...read more</span></p>
      <button class="standard-button" @click="$refs.connectName.openConnect()">Enroll</button>
    </div>
    <div   class="summerclass">
      <img class="summerclasses" src="../assets/videoProduction.png" alt="">
      <h4>Video production</h4>
      <p>Your child will learn to produce,
        create, and edit videos they can use for video adverts  <span>...read more</span></p>
      <button class="standard-button" @click="$refs.modalName.openModal()">Enroll</button>

    </div>
  </div>
</div>

<div class="meet-partners">
  <h3>Meet our partners</h3>
  <div class="rows">
    <div class="partner">
      <img src="../assets/azubikeAni.png" alt="Azubike Ani">
      <h5>Azubike Ani</h5>
      <p>Year 12 / SSS 3 Mathematics. <br>British &amp; Nigerian Curriculum</p>
    </div>
    <div class="partner">
      <img src="../assets/khadijatAkinade.png" alt="Khadijat Akinade">
      <h5>Khadijat Akinade</h5>
      <p>Year 7 / JSS 1 Mathematics.<br>British Curriculum</p>
    </div>
    <div class="partner">
      <img src="../assets/imisiayoOloyede.png" alt="Imisiayo Oloyede">
      <h5>Imisiayo Oloyede</h5>
      <p>Upper primary school classes.</p>
    </div>
    <div class="partner">
      <img src="../assets/deleGbede.png" alt="Dele Gbede">
      <h5>Dele Gbede</h5>
      <p>Year 9/JSS 3 Mathematics.<br>Nigerian Curriculum</p>
    </div>
  </div>
</div>
<div class="header-background">

  <div class="header-content sun">
    <div class="header-article">
      <h1 class="tagline-header">Partner with Gradely for your summer school</h1>
      <p class="tagline-paragraph">Bring your summer school to life with Gradely by offering much more without any additional demands on your teachers. Your students’ can explore and engage their
        interests right at their fingertips from anywhere they are.</p>
        <div class="rows">
        <div class="whites-button"><img src="../assets/whatsappIcon.svg"><p><a href="https://wa.link/ydy5yo">Book a tutor</a></p></div>
        <div class="whites-button broch"><img src="../assets/cardThumb.png"><p>Download Brochure</p></div>
      </div>
    </div>

    <img class="sunset-image" src="../assets/sunset.png">


</div>
</div>

<div class="curriculum">

    <h2>Get quality tutors
      at the best price and at <br>the convenience of your room.</h2>

      <div class="classes">
      <div class="general-class">

        <h3>General classes</h3>
        <p><span class="material-icons-outlined">done</span>Access
          to video lessons for 3 skills.</p>
        <p><span class="material-icons-outlined">done</span>Join
          2 live group tutoring sessions per week.</p>
        <p><span class="material-icons-outlined">close</span>Support with
          building project portfolio</p>
        <p><span class="material-icons-outlined">close</span>Flexible
          learning schedules</p>

        <div class="offer">
          <h2 class="push-down">5000</h2>
          <p class="small-font">per month</p>
          <button class="white-button">ENROLL</button>
        </div>
      </div>
      <div class="personalized-class">

        <h3>Personalized Classes</h3>
        <p><span class="material-icons-outlined">done</span>Access
          to video lessons for 3 skills.</p>
        <p><span class="material-icons-outlined">done</span>Join
          2 live group tutoring sessions per week.</p>
        <p><span class="material-icons-outlined">done</span>Support
          with building project portfolio</p>
        <p><span class="material-icons-outlined">done</span>
          Flexible learning schedules</p>

        <div class="offer">
          <p class="small-font">starting from</p>
          <h2>3000</h2>
          <p class="small-font">per class hour</p>
          <div class="white-button"><img src="../assets/whatsappIcon.svg"><p><a href="https://wa.link/ydy5yo">Book a tutor</a></p></div>
      </div>
    </div>
      </div>
      <div class="question-box">
      <h3>Have more Questions?</h3>
      <div class="white-button"><img src="../assets/whatsappIcon.svg"><p>CONTACT US</p></div>
      <div><img src="../assets/wavy-line.png" alt=""></div>
      <p class="contact-info">Or you can call us on: <span>(+234) 810 059 8268</span></p>
    </div>
</div>

<div class="faq">
  <h2>Frequently Asked Questions</h2>
  <div class="faqs">
    <h5>What are the technical requirements for Gradely?</h5>
    <p>All you need to get started is a computer, tablet, or phone with a connection to the Internet.</p>
  </div>
  <div class="faqs">
    <h5>What age group is this meant for?</h5>
    <p>Gradely summer school is
      for students age 5 and above.</p>

  </div>
  <div class="faqs">
    <h5>When do the virtual live sessions hold?</h5>
    <p>Each class has scheduled days for the live classes which can be found in the class calendar.
    Also, if you miss a class, you can watch the recorded version on your class feed and,
    post on the feed if you have any questions for your facilitator.</p>

  </div>
</div>


<div class="footer">


  <div class="footer-list">
      <div>
      <img src="../assets/logoMark.png" alt="Gradly logo mark">
    </div>

  <div>
    <p class="heading">Inside Gradely</p>
    <p>Home</p>
    <p>About Gradely</p>
    <p>Blog</p>
    <p>Contact Us</p>
    <p>Guides &amp; How-tos</p>
  </div>
  <div>
    <p class="heading">Products</p>
    <p>For Schools</p>
    <p>For Parents</p>
    <p>Tutoring</p>
    <p>CatchUp!</p>
    <p>Covid-19</p>
  </div>
  <div>
    <p class="heading">Account</p>
    <p>Sign up as a Student</p>
    <p>Sign up as a Parent</p>
    <p>Sign up as a Teacher</p>
    <p>Sign up as a School</p>
    <p>Become a Tutor</p>
  </div>
  <div>
    <p class="heading"><span></span>Support</p>
    <p><span></span>support@gradely.ng</p>
    <p><span></span>(+234) 810 059 8268</p>
    <p><span></span>Visit Help center </p>
    <p><span></span></p>
  </div>



</div>
<ul class="copyright">
  <li class="gradely-copyright">Copyright 2020, Gradely Inc.. All rights reserved.</li>
  <li class="terms">Terms &amp; Conditions</li>
  <li class="terms">Privacy Policies</li>
</ul>
</div>

<modal ref="modalName">

  <template v-slot:closing>
      <p @click="$refs.modalName.closeModal()"><span class="material-icons-outlined">
close
</span></p>
  </template>


<template v-slot:body>
  <img src="../assets/success.png">
  <h2>Success!</h2>
  <p>Thank you for joining Gradely Online Summer School.
    We look forward to a fun learnig experience with you.</p>

</template>


</modal>

<connect ref="connectName">

  <template v-slot:closing>
    <h3>ADD A CHILD</h3>
      <p @click="$refs.connectName.closeConnect()"><span class="material-icons-outlined">
close
</span></p>
  </template>


<template v-slot:body>
  <div class="addyourchild">
    <div>
    <img src="../assets/warning.png">
  </div>
    <p>Can't find you child?<a href="#"> Sign up your Child</a></p>
  </div>
</template>

<template v-slot:inputted>
  <div class="addstudent">
    <div class="input-title">
      <p>Student Code</p>
      <div>
        <img src="../assets/info.png">
      </div>
    </div>
    <div class="input-field">
    <input v-model="message" placeholder="XYZ/2019/2998">

  <button class="standard-button">Verify Code</button>
</div>

<div class="input-title">
  <p>Student Code</p>
</div>
<div class="input-field">
<select v-model="selected">
  <option v-for="option in options" v-bind:key="option.value">
    {{ option.text }}
  </option>
</select>

</div>
</div>

<div class="profileinfo">
  <div>
  <img src="../assets/profilephoto.png">
</div>
  <div>
    <h3>Omolade Giwa</h3>
    <p>IMMAD College (JSS1 - Gold)</p>
  </div>
</div>

<div  class="addanotherchild">
  <div class="addImage">
  <a href="#"><img src="../assets/Shape.png"></a>
</div>
  <div>
    <p><a href="#">Add Another Child</a></p>
  </div>
</div>

<div class="enroll-button">
<button class="standard-button">CONNECT</button>
</div>

</template>




</connect>

<addchild ref="addchildName">

  <template v-slot:closing>
    <h3>JOIN CLASS FORM</h3>
      <p @click="$refs.addchildName.closeAddchild()"><span class="material-icons-outlined">
close
</span></p>
  </template>



  <template v-slot:body>
    <div class="addyourchild">
      <div>
      <img src="../assets/warning.png">
    </div>
      <p>Is your child already using Gradly<a href="#"> Enter student code</a></p>
    </div>
    <div>
      <p class="entername">Enter the name of your child and your contact details.
        We need the your contact information to send the child’s login details. <a href="#">Learn more about how we use the parent’s contact here.</a></p>
    </div>
  </template>

  <template v-slot:inputted>
<div>
    <div class="input-parent-detail">
    <div>
    <h3>Parent's email</h3>
    <div class="input-field">
    <input v-model="message" placeholder="E.g David Oshinaga">
  </div>

  </div>

  <div>
  <h3>Parent's password</h3>
  <div class="input-field">
  <input v-model="message" placeholder="Enter password">
</div>


</div>



</div>
<div>
  <h3>Students</h3>
  <p class="entername">Copy
Enter your child’s name and class and select up to three courses they have interest in.</p>
</div>

</div>
    <div class="addstudent">
      <div class="input-child-detail">
      <div>
      <h3>Parent's email</h3>
      <div class="input-field">
      <input v-model="message" placeholder="E.g David Oshinaga">
    </div>

    </div>

    <div>
    <h3>Parent's password</h3>
    <div class="input-field">
    <input v-model="message" placeholder="Enter password">
  </div>




  </div>

  <div>
  <h3>Parent's password</h3>
  <div class="input-field">
  <input v-model="message" placeholder="Enter password">
</div>




</div>
</div>


  <div class="input-title">
    <p>Student Code</p>
  </div>
  <div class="input-field">
  <select v-model="selected">
    <option v-for="option in options" v-bind:key="option.value">
      {{ option.text }}
    </option>
  </select>

  </div>
  </div>


  <div  class="addanotherchild">
    <div class="addImage">
    <a href="#"><img src="../assets/Shape.png"></a>
  </div>
    <div>
      <p><a href="#">Add Another Child</a></p>
    </div>
  </div>

  <div class="enroll-button">
  <button class="standard-button">CONNECT</button>
  </div>

  </template>


</addchild>


  </div>

</template>
<script>
import Modal from "./Modal";
import Connect from "./ConnectModal";
import Addchild from "./Addchild";
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
     Modal,
     Connect,
     Addchild
  }, data() {
    return {
        selected: 'A',
      options: [
        {text: 'Coding', value: 'A'},
        {text: 'Digital Design', value: 'B'},
        {text: 'Homemaking', value: 'C'},
        {text: 'Dance', value: 'D'},
        {text: 'Entrepreneurship', value: 'E'},
        {text: 'Video Production', value: 'F'},
      ]
    }

  }
}
</script>

<style>
div.addyourchild {
  width: 90%;
  color: #113255;
  background-color: #FCEACF;
  border: 1px solid #FAA017;
  display:flex;
  margin: auto;
  border-radius: 5px;

}

div.modal__body  p.entername {
  text-align: left;
  font-size: 12px;
}
div.modal__closing h3, div.modal__closing p {
  font-weight: 1000;
  margin: 0;
  padding: 0;

}

div.modal__input div.input-field{
  display: flex;
  justify-content: space-between;
  margin: 10px;
}

div.modal__input div.input-field input {
  padding: 10px;
  border: 1px solid #D5D5D5;
  border-radius: 5px;

}

div.input-title {
  display: flex;
  margin: 10px;
}

div.modal__input div.input-field select {
  padding: 10px 190px 10px 10px;
  width: 90%;
  border: 1px solid #D5D5D5;
  border-radius: 5px;
}

div.input-title p, div.input-title img {
  margin: 0;
  font-size: 14px;
  font-weight: 700;
  padding: 0
}
div.input-title img {
  margin-left: 20px;
}
div.modal__input  div.input-field button {
  margin: auto;
  background-color:#11BDCF;
}

div.input-parent-detail {
  display: flex;
}

div.input-child-detail {
  display: flex;
}

div.input-parent-detail input{
  padding: 0;
  width: 100%;
  height: 30px;
  width: 250px;
  padding: 10px;
}

div.input-child-detail input{
  padding: 0;
  width: 100%;
  height: 30px;
  width: 150px;
  padding: 10px;
}
div.profileinfo {
  display: flex;
  max-height: 20px;
  padding: 40px 0;
}

div.profileinfo h3, div.profileinfo p {
  margin: 0;
  padding: 0 10px;
  font-size: 14px;
}


div.addyourchild img {
  margin: 20px;
}

div.addyourchild a {
  font-weight: 600;
  color: #113255;
  letter-spacing: 0.5px;
}

div.addanotherchild {
  display: flex;
}

div.addanotherchild p a{
  margin-left: 10px;
  font-size: 14px;
  font-weight: 700;
  color: #FAA017;
}

div.enroll-button {
  width: 100%;
  display: flex;
  margin: auto;
}

div.enroll-button button.standard-button {
  margin: auto;
}

div.addImage {
  margin: auto 0;
  padding-right: 5px;
  padding-left: 5px;
  border: 1px solid #FAA017;
  border-radius: 50%;
}


div.summer-school {
  width: 100%;
}

div.sun {
  padding: 30px 0;
}

span.material-icons-outlined {
  cursor: pointer;
}

div.header-background {
  width: 100%;
  background-color: #FCEACF;
}

div.header-pic-img {
  width: 100%;
  max-height: 602px;
  background: url("../assets/headerPic.png");
}

div.header-content {
  display: flex;
  width: 100%;

}

div.header-article {
  display: block;
  margin-left: 5%;
  margin-right: 10%;
  margin-top: auto;
  margin-bottom: auto;
  padding-top: 60px;
  width: 40%;
}

div.header-content img {
  width: 40%;
}

div.header-article h1.tagline-header {
  font-size: 2.5rem;
  color: #113255;
  font-weight: 700;
}

div.header-article h1.tagline-header span {
  color: #FAA017;

}


div.header-article p.tagline-paragraph {
  font-size: 1.2rem;
  color: #353535;
  font-weight: 500;

}

button.standard-button {
  background-color:#FAA017;
  font-size: 14px;
  font-weight: 700;
  border-radius: 20px;
  padding: 13px 35px;
  border: none;
  color: #113255;
  text-transform: uppercase;
  margin-bottom: 10px;
  transition: background-color ease 1s;

}

div.second-page {
  display: flex;
  width: 100%;
  background-color: #fff;
  
}

div.second-page iframe {
  margin: auto;
  padding: ;
  width: 40%;
  padding: 20px;
 
}

div.second-article {
  display: block;
  margin: auto 20px;
  width: 40%;

}

div.second-article h2 {
  font-size: 1.8rem;
  color: #113255;
  font-weight: 700;
  max-width: 521px;
}

div.second-article p {
  font-size: 1rem;
  color: #353535;
  font-weight: 500;
  max-width: 521px;
}

div.second-article button {
  margin-top: 20px;
}

div.how-it-works {
  display: block;
  text-align: center;
  color: #113255;
  width: 80%;
  margin: auto;
  margin-top: 6px;
}
div.how-it-works h2 {
  margin-top: 0;
  margin-bottom: 40px;
  font-size: 1.8rem;
  font-weight: 700;
}
div.how-it-works p {
  margin: 20px auto;
  text-align: center;
}

div.icons {
  display: flex;
  justify-content: space-between;
}
div.icon-box {
  width: 20%;
}

div.icon-box-article {
  display: block;
}

div.icon-box h3 {
  font-size: 1rem;
  font-weight: 600;
  color: #113255;

}



div.icon-box p {
  font-size: 0.9rem;
  font-weight: 500;
  color: #555555;
  max-width: 269px;
}

div.interest-led-classes {
  display: block;
  text-align: center;
  color: #113255;
  width: 80%;
  margin: auto;
  margin-top: 100px;
}

div.row {
  display: flex;
  justify-content: space-between;
}



div.interest-led-classes h2 {
  margin-bottom: 60px;
  font-size: 1.5rem;
}
div.summerclass {
  background: #fff;
  width: 25%;
  padding: 10px;
  margin-bottom: 20px;
  box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.3);
  -webkit-box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.3);
  -moz-box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.3);
}

div.summerclass img.summerclasses {
  margin: 10px;
  width: 80%;
}

div.summerclass h4 {
  margin: 0;
  font-size: 1.1rem;
}

div.summerclass p span {
  color: #113255;
  font-weight: 700;
}
div.summerclass p {
  font-size: 1rem;
  font-weight: 500;
  margin: 30px 10px;
  text-align: left;
  color: #353535;
  height: 120px;
}
div.meet-partners {
  display: block;
  padding-top: 100px;
  width: 80%;
  margin: auto;
  padding-bottom: 100px;
}
div.meet-partners h3 {
  text-align: center;
  color: #113255;
  font-weight: 600;
  font-size: 1.5rem;
}

div.rows {
  width: 100%;
  display: flex;
  margin: auto;

}
div.partner {
  display: inline-block;
  width: 20%;
  margin: 20px;
}

div.partner h3 {
  margin: 40px 0;
}
div.partner h5 {
  font-size: 1rem;
  color: #2A4F77;
  margin: 10px auto;
  text-align: center;
}

div.partner p {
  margin: auto;
  max-width: 240px;
  font-size: 14px;
  text-align: center;
  color: #757575;
}

div.partner img {
  width: 100%;
}

div.curriculum {
  display: block;
  width: 100%;
  margin: 90px auto;
  text-align: center;
  color: #353535;
  font-size: 1rem;
}

div.classes {
  display: flex;
  width: 60%;
  margin: auto;

}

div.general-class , div.personalized-class {
  display: block;
  padding: 20px;
  margin: auto 20px;
  min-height: 600px;
  text-align: left;
  border: 1px solid #11BDCF;
  border-radius: 15px;
  width: 70%;
  font-size: 16px;
  color: #555555;
}

div.general-class p, div.personalized-class p{
  margin: auto;
  display: flex;
  padding: 20px;
}

div.general-class h3, div.personalized-class h3 {
  text-align: center;
}
span.material-icons-outlined {
  color: #113255;
  padding-right: 20px;

}


button.white-button {
  background-color:#FFF;
  font-size: 14px;
  font-weight: 700;
  border-radius: 20px;
  padding: 10px 20px;
  border: 1px solid #959595;
  color: #353535;
  text-transform: uppercase;



}

div.whites-button {
  display: flex;
  justify-content: center;
  font-weight: 600;
  padding: 2px 14px;
  border: 1px solid #959595;
  border-radius: 25px;
  max-width: 190px;



}

div.whites-button a {
  color: #353535;
  text-decoration: none;
  text-transform: uppercase;
}

div.broch {
  margin-left: 10px;
  border: none;
}

div.whites-button img {
  height: 22.98px;
  width: 22.87px;
  margin: auto 0;
  margin-right: 10px;
}

.standard-button:hover{
  cursor: pointer;
  background-color: #11BDCF;
  color: #113255;
  box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.6);
  -webkit-box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.6);
  -moz-box-shadow: 1px -1px 27px -8px rgba(0,0,0,0.6);
}



div.white-button {
  display: flex;
  width: 45%;
  margin: auto;
  text-align: left;
}


div.offer {
  display: block;
  text-align: center;
  margin: auto;
}

div.offer p {
  display: block;
  text-align: center;
  margin: 0 auto;
  padding: 0;
}

p.small-font {
  color: #353535;
  margin-bottom: 0;
  font-size: 0.7rem;
}
div.offer h2 {
  padding: 0;
  margin: 0;
}

div.question-box {
  display: block;

}

button.white-button, div.white-button {
  background-color:#FFF;
  font-size: 14px;
  font-weight: 700;
  border-radius: 20px;
  padding: 10px 20px;
  border: 1px solid #959595;
  color: #353535;
  text-transform: uppercase;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;
  width: 50%;

}

div.white-button {
  display: flex;

  justify-content: space-around;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;

}

div.white-button p a {
  margin: 0;
  color: #353535;
  text-decoration: none;
}

div.links button.login-button:hover {
  color: #113255;
  background-color: #11BDCF;
  cursor: pointer;
  transition: background-color ease 1s;
}
div.offer {
  display: block;
  text-align: center;
  margin: 30px auto;
}

div.offer p {
  display: block;
  text-align: center;
  margin: 0 auto;
  padding: 0;
}


div.offer h2 {
  padding: 0;
  margin: 0;
  color: #113255;
  font-size: 2rem;
  letter-spacing: 2px;
  margin-bottom: 0;
}

p.small-font {
  color: #353535;
  margin-bottom: 0;
  font-size: 0.7rem;
}
div.offer h2.push-down {
  padding-top: 20px;
}

div.question-box {
  display: block;
  margin: 50px auto;
  max-width: 350px;
}

p.contact-info {
  font-size: 12px;
  font-weight: 600;
}

p.contact-info span {
  color: #FE747D;
}

div.faq {
  display: block;
  margin: auto;
  width: 100%;
  text-align: center;
  background: url('../assets/footerPic.png');
  padding-bottom: 160px;
}

div.faq h2 {
  color: #113255;
  font-size: 42px;
}
div.faqs {
  display: flex;
  margin: auto;
  padding: 20px;
  max-width: 60%;
  border-bottom: 1px solid #D5D5D5;
}

div.faqs h5 {
  font-size: 1.2rem;
  width: 40%;
  text-align: left;
}

div.faqs p {
  font-size: 16px;
  max-width: 40%;
  text-align: left;
  margin: auto;
  padding-left: 120px;

}

div.footer {
  display: block;
  width: 100%;
  background-color: #113255;
  padding-top: 60px;
  padding-bottom: 60px;
  color: #DBF5F8;
  font-size: 14px;

}

div.footer-list {
  display: flex;
  width: 90%;
  justify-content: space-between;
  margin: auto;
  justify-content: center;


}

div.footer-list img {
  margin-right: 20px;
}
div.footer-list p {
  max-width: 400px;
  color: #F5F5F5;
  margin-right: 40px;
}





p.heading {
  color: #F5F5F5;
  font-weight: 600;
  opacity: 90%;
  padding-bottom: 15px;
}

/* div.footer-list p {
  list-style: none;
  font-size: 12px;
  font-weight: 300;
  opacity: 80%;
} */

ul.copyright {
  list-style: none;
  color: #F5F5F5;
  max-width: 1200px;
  margin: auto 30px;
  margin-top: 30px;
  color: #DBF5F8;

}

li.gradely-copyright {
    float: left;
}

li.terms {
  float: right;
  margin: 0;
  margin-right: 10px;
  padding: 0;
}


@media screen and (max-width:650px) {
  div.modal__input div.input-field{
    display: block;
    margin: 10px;
  }

  div.modal__input div.input-field input {
    margin-bottom: 10px;
  }



      div.header-content {
        display: flex;
        flex-direction: column;

    } div.header-article {
        width: 80%;
        margin: auto;
        order: 2;
        margin-top: 0;
        padding-top: 0;


    } div.header-content img.sunset-image {
      width: 80%;

      border-radius: 50%;
      order: 1;
    }div.header-pic-img{
      max-height: 100%;
    }
    div.second-page {
        display: block;
        margin: auto 0;
        padding: 0;
    } div.second-article {
        width: 80%;
        
    } div.second-page iframe {
        width: 80%;
    }
    div.row {
        display: block;
    } div.summerclass {
      width: 90%;
      margin: auto;
      margin-bottom: 20px;
    } div.classes {
      display: block;
    } div.general-class, div.personalized-class {
      min-height: 200px;
      width: 100%;
      margin: 0;

      margin-bottom: 20px;
    } div.curriculum h2 {
      text-align: left;
      margin: auto;
      font-size: 30px;
      max-width: 300px;
      margin-bottom: 20px;
      }div.rows {
      display: block;
    } div.partner {
      width: 80%;
    } div.offer h2 {
      padding: 0;
      margin: 0;
    }div.faqs h5{
      font-size: 10px;
      width: 100%;
    } div.faqs p {
      font-size: 10px;
      padding-left: 30px;
      }div.footer {
      width: 100%;
      padding: 0;

      flex-direction: column;
    } div.footer-list {
      display: block;
      padding-right: 10px;

    }
    li.terms {
      text-align: left;
      float: none;
      margin: 0;
      padding: 0;
    }div.offer h2 {
      text-align: center;
    } div.icons {
      display: block;
    } div.icon-box {
      width: 80%;
      margin: auto;
    }

}


</style>
