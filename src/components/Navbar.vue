<template>
  <nav class="nav-bar">
    <img class="logo" src="../assets/gradelyLogo.png" alt="Gradely Logo">
    <div class="links">

      <a class="link" href="https://gradely.ng/for-parents/">For Parents</a>
      <a class="link" href="https://gradely.ng/for-schools/">For Schools</a>
      <Dropdown title="More" :items="services"/>
      <a class="link" href="https://app.gradely.ng/signup/lander?_ga=2.201818968.816886629.1625990452-418383553.1625543476">Sign Up</a>

      <button class="login-button"><a  href="https://app.gradely.ng/login">LOG IN</a></button>
      <Hamburger title="more" :items="menue"/>
      <!-- <a class="dropdown"><span class="material-icons-outlined">menu</span></a> -->


    </div>

  </nav>
</template>

<script>
import Dropdown from './Dropdown';
import Hamburger from './Hamburger';
export default {
  name: 'navbar',
  components:{
    Dropdown,
    Hamburger
  },
  data() {
      return {
        services: [
          {
            title: 'About Us',
            link: 'https://gradely.ng/about/'
          },
          {
            title: 'Blog',
            link: 'https://gradely.ng/blog/'
          },
          {
            title: 'Help Centre',
            link: 'https://gradely.ng/help-centre/'
          },
          {
            title: 'Contact Us',
            link: 'https://gradely.ng/contact-us/'
          },
        ],  menue: [
            {
              title: 'For Parents',
              link: 'https://gradely.ng/for-parents/'
            },
            {
              title: 'For Schools',
              link: 'https://gradely.ng/for-schools/'
            },
            {
              title: 'Sign Up',
              link: 'https://app.gradely.ng/signup/lander?_ga=2.201818968.816886629.1625990452-418383553.1625543476'
            },
            {
              title: 'Log In',
              link: 'https://app.gradely.ng/login'
            },
            {
              title: 'About Us',
              link: 'https://gradely.ng/about/'
            },
            {
              title: 'Blog',
              link: 'https://gradely.ng/blog/'
            },
            {
              title: 'Help Centre',
              link: 'https://gradely.ng/help-centre/'
            },
            {
              title: 'Contact Us',
              link: 'https://gradely.ng/contact-us/'
            }
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

a.dropdown {
  visibility: hidden;
  display: none;
}

span.material-icons {
  margin: 0;
  top: 0;
  line-height: 0.8;
  padding: 0;
  color: #113255;
}

div.sub-menus {
  display: none;
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
    } div.sub-menus {
      display: block;
      } div.links a.dropdown {
      display: unset;
      visibility: visible;
      opacity: 100% !important;

      margin: auto;
      padding: 15px;
      color: #555555;
      font-weight: 600;
      font-size: 13px;
      display: block;
      cursor: pointer;
      text-decoration: none;
      position: relative;
    }

    a.dropdown {
      margin: auto;
    }
     button.login-button {
      padding: 0;
      }
   

}
</style>
