<template>
  <div id="wrapper">
    <!-- Sidebar -->
    <div id="sidebar-wrapper">
      <ul class="sidebar-nav">
        <br><br><br>
        <nuxt-link to="/loginPath">
          <b-button class="ml-4"> Back </b-button>
        </nuxt-link>
        <li>
          <a href="#">
            <i class="fas fa-caret-right white"></i> ลักษณะงานของ HR
          </a>
        </li>
        <li class="ml-5">
          <a href="#HR1">การวางแผน</a>
        </li>
        <li class="ml-5">
          <a href="#HR2">งานพัฒนาบุคคลากร</a>
        </li>
        <li class="ml-5">
          <a href="#HR3">การสรรหาคัดเลือกบุคคล</a>
        </li>

        <li>
          <a href="#HR4">
            <i class="fas fa-caret-right white"></i> คุณสมบัติที่ HR ควรมี
          </a>
        </li>
        <li class="ml-5">
          <a href="#HR5">Critical & Enquiring Thinker</a>
        </li>
        <li class="ml-5">
          <a href="#HR6">Solution Driven</a>
        </li>
        <li class="ml-5">
          <a href="#HR7">Courageous</a>
        </li>
        <li class="ml-5">
          <a href="#HR8">Collaboration</a>
        </li>
        <li class="ml-5">
          <a href="#HR9">Understand</a>
        </li>
        <li class="ml-5">
          <a href="#HR10">Resolve Issues </a>
        </li>
        <li class="ml-5">
          <a href="#HR11">Credible</a>
        </li>
        <li class="ml-5">
          <a href="#HR12">Care</a>
        </li>
        <li class="ml-5">
          <a href="#HR13">Future Oriented </a>
        </li>
        <li class="ml-5">
          <a href="#HR14">Influencer</a>
        </li>

        <li>
          <a href="#HR15">
            <i class="fas fa-caret-right white"></i> หน่วยงานเอกชนที่น่าสนใจ
          </a>
        </li>
        <li class="ml-5">
          <a href="#HR16">บริษัท ปตท.จำกัด(มหาชน</a>
        </li>
        <li class="ml-5">
          <a href="#HR17">บริษัท ปูนซีเมนต์ไทย</a>
        </li>
        <li class="ml-5">
          <a href="#HR18">บริษัท เครือเจริญโภคภัณฑ์</a>
        </li>
        <li class="ml-5">
          <a href="#HR19">Google</a>
        </li>
        <li class="ml-5">
          <a href="#HR20">การบินไทย</a>
        </li>

      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/*!
 * Start Bootstrap - Simple Sidebar (https://startbootstrap.com/template-overviews/simple-sidebar)
 * Copyright 2013-2017 Start Bootstrap
 * Licensed under MIT 

(https://github.com/BlackrockDigital/startbootstrap-simple-sidebar/blob/master/LICENSE)
 */

#menu-toggle {
  color: white;
  position: absolute;
  top: 46px;
  left: -45.75px;
  transform: rotate(90deg);
  background: black;
}

#wrapper {
  padding-left: 250px;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

#wrapper.toggled {
  padding-left: 0px;
}

#sidebar-wrapper {
  position: fixed;

  left: 230px;

  width: 260px;

  height: 100%;

  margin-left: -250px;

  overflow-x: hidden;
  background: #000;

  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

#wrapper.toggled #sidebar-wrapper {
  width: 0px;
}

#page-content-wrapper {
  width: auto;
  position: absolute;
  padding: 50px;
}

#wrapper.toggled #page-content-wrapper {
  position: absolute;
  margin-right: -250px;
  width: 100%;
}

/* Sidebar Styles */

.sidebar-nav {
  position: absolute;
  top: 0;
  width: 250px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.sidebar-nav li {
  text-indent: 20px;
  line-height: 40px;
}

.sidebar-nav li a {
  display: block;
  text-decoration: none;
  color: #ffff;
}

.sidebar-nav li a:hover {
  text-decoration: none;
  color: #fff;
  background: rgba(255, 255, 255, 0.2);
}

.sidebar-nav li a:active,
.sidebar-nav li a:focus {
  text-decoration: none;
}

.sidebar-nav > .sidebar-brand {
  height: 65px;
  font-size: 18px;
  line-height: 60px;
}

.sidebar-nav > .sidebar-brand a {
  color: #999999;
}

.sidebar-nav > .sidebar-brand a:hover {
  color: #fff;
  background: none;
}

@media (min-width: 768px) {
  #wrapper {
    padding-left: 0;
  }

  #wrapper.toggled {
    padding-left: 0px;
  }

  #sidebar-wrapper {
    width: 250px;
  }

  #wrapper.toggled #sidebar-wrapper {
    width: 250px;
  }

  #page-content-wrapper {
    padding-left: 50px;
    position: relative;
  }

  #wrapper.toggled #page-content-wrapper {
    position: relative;
    margin-right: 0;
    padding-left: 35px;
  }
}

**/ .footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: black;
  color: white;
  text-align: center;
}

.row {
  margin-right: 0px;
  margin-left: 0px;
}
</style>