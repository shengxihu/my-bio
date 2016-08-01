<template>
  <div class="container">
    <info></info>
    <experience></experience>
    <skill></skill>
    <education></education>
    <more></more>
  </div>
</template>

<script>
import info from './components/info';
import experience from './components/experience';
import skill from './components/skill';
import education from './components/education';
import more from './components/more';

export default {
  components: {
    info,
    experience,
    skill,
    education,
    more
  }
}
</script>

<style>
html, body {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
  font-size: 16px;
  overflow: hidden; }

.container {
  width: 100%;
  height: 100%; 
  vertical-align: middle;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  -ms-transition: all 0.5s ease;
  transition: all 0.5s ease; }

.container > section {
  width: 100%;
  height: 100%;
  position: relative;
  background: #5cc3ae; }

#info {
   }

#experience {
   }

#skill {
   }

#education {
   }

#more {
   }
.content {
  width: 100%;
  text-align: center;
  color: #fffcf5;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  }
.name {
  font-size: 3.75rem;
  text-shadow: 4px 2px 1px #008A75,5px 3px 2px #CFECF3;
}
h4 {
  font-size: 1.25rem;
}
h3 {
  font-size: 1.75rem;
}
h1 {
  margin: 1rem 0;
}
p {
  font-size: 1.125rem;
}
ul {
  font-size: 1.125rem;
  list-style: none;
  padding: 0;
}
.slide_to_1 {
  transform: translateY(0%); }

.slide_to_2 {
  transform: translateY(-100%); }

.slide_to_3 {
  transform: translateY(-200%); }

.slide_to_4 {
  transform: translateY(-300%); }

.slide_to_5 {
  transform: translateY(-400%); }

</style>
