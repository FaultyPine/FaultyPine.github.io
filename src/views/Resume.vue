<template>
  <div>
    <h1><u>Resume</u></h1>

    <i>You can find my official resume here.</i>
    <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/Resume.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF</a>
        <div style="clear:both"></div>
        <iframe src="d/Resume.pdf" frameborder="0" height="900" width="100%"></iframe>
    </div>

    <div class="paragraph">
      I'm <strong>Grayson Clark</strong>, a student at Indiana University studying Computer Science.
      <br />I am pursuing Computer Science / Game Development because there's something really magical about working with computers.
      <br />Coding is like my way of weilding my magic wand, and the more I learn the more I am fascinated by this technological world.
      <br />I love working with other people and consider myself a great team player, but can also fly solo if need be.
      <br />
      <br />Feel free to 
      <router-link to="/contact">contact me</router-link>.
      <br />
      <br />Besides coding, I'm passionate about Soccer, Volleyball, and fantasy books.

    </div>
    <div class="photo">
      <img src="img/resume-photo.jpg" alt="Photo of Me"/>
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2><u>Work experience</u></h2>

    <div>
      <h3>Summer Camp Counselor</h3>
      <h4>2016-2020</h4>

      <div>I worked as a Camp Counselor for a summer camp for kids K-5th grade. 
          It taught me how to respond quickly and decisively, and how to think on my feet.
          I learned great leadership skills from taking care of a group of kids, and created activities and
          schedules for them throughout each week.
          I also interacted with parents and talked to them about their kids, which taught me how to convey information
          effectively and how to deal with demands from a customer.
      </div>
      <div class="tech-stack">Teamwork, leadership, creativity, client-provider interactions, quick decision-making</div>
    </div>
    
    <div>
      <h3>Rollback Netcode Consultant</h3>
      <h4>2022-Present</h4>

      <div>I am currently a consultant for <a href="https://thirdpixelinteractive.com/#0">ThirdPixel Interactive</a> where I provide advice and
      guidance regarding videogame networking for their upcoming game <a href="https://store.steampowered.com/app/1739300/Smack_Studio/?utm_source=thirdpixelinteractive.com&utm_medium=link&utm_campaign=work">Smack Studio</a>.
      </div>
      <div class="tech-stack">Computer Networking, Teamwork, Version Control, Coordination, Communication</div>
    </div>


    </div>
  </div>
</template>


<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 400px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>