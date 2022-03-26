<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Grayson Clark</strong>, a hobbyist Game Developer studying Computer Science at Indiana University.<br/>
        I spend my time working on coding projects that range from games from scratch, to mods for popular games, to production-grade software.
      </div>

      <div style="margin-top: 20px;">Here's the  <router-link to="/game-projects">game-related projects</router-link>, i've worked on, as well as my <router-link to="/other-projects">other projects</router-link>.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for a job</strong> as a Computer Scientist/Software Engineer/Game Developer. You can reach me at <a href="mailto:gclark1013@gmail.com">gclark1013@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="My Avatar" width="250" height="250" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
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
    padding: 10px;
    padding-left: 80px;
  }
}

</style>