<template>
  <nav class="nav-bar">
    <img class="logo" src="../assets/gradelyLogo.png" alt="Gradely Logo">
    <div class="links">
      <a class="link" href="#">For Parents</a>
      <a class="link" href="#">For Schools</a>
      <Dropdown title="More" :items="services"/>
      <a class="link" href="#">Sign Up</a>
      <button class="login-button">LOG IN</button>
      <a class="dropdown"><span class="material-icons-outlined">menu</span></a>


    </div>

  </nav>
</template>

<script>
import Dropdown from './Dropdown';
export default {
  name: 'navbar',
  components:{
    Dropdown
  },
  data() {
      return {
        services: [
          {
            title: 'About Us',
            link: '#'
          },
          {
            title: 'Blog',
            link: '#'
          },
          {
            title: 'Help Centre',
            link: '#'
          },
          {
            title: 'Contact Us',
            link: '#'
          },
        ]
      }
  }
}
</script>

<style>

.nav-bar {
  width: 100%;
  height: 60px;
  background-color: #fff;
  position: fixed;
  z-index: 1;
}
.logo {
  display: inline-block;
  vertical-align: top;
  float: left;
  margin: 5px;
  padding-left: calc(0rem + 4vw);
}

div.links {
  display: inline-flex;
  float: right;
  padding-right: 0
}
div.links a {
  margin: 0;
  padding: 15px;
  color: #555555;
  font-weight: 600;
  font-size: 13px;
  cursor: pointer;
  text-decoration: none;
  position: relative;
}

div.links a.more {
  display: flex;
  margin: 0;
}

span.material-icons {
  margin: 0;
  top: 0;
  line-height: 0.8;
  padding: 0;
  color: #113255;
}

div.links button.login-button {

  background-color:#FAA017;
  font-size: 14px;
  font-weight: 700;
  border-radius: 20px;
  height: 10%;
  padding: 10px 20px;
  margin: 10px;
  border: none;
  color: #113255;
  position: relative;

}


@media screen and (max-width:700px) {
      div.links a.link, div.links a.more {
        display: none;
    } div.links a.dropdown {
      display: block;
      visibility: visible;
      opacity: 100%;
      margin: auto 0;
      padding: 0;
    }
     button.login-button {
      padding: 0;
      }
      div.sub-menu {
        display: none;
      }
}
</style>
