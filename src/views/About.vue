<template>
  <div style="margin-bottom: 80px;">
    <h1>Hey there!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Grayson Clark</strong>, a hobbyist Game Developer studying Computer Science at Indiana University.<br/>
        I spend most of my free time working on coding projects that range from game development, to mods for popular games, to production-grade software.
        <br/>
        When I'm not coding, I like playing Soccer, Volleyball, or videogames. Some of my favorite games are:
        <ul class="games_list">
            <li>
                <img src="https://cdn2.steamgriddb.com/file/sgdb-cdn/icon/e0688d13958a19e087e123148555e4b4.png" width="50" height="50"/>Smash
            </li>
            <li>
                <img src="https://img.icons8.com/color/480/rocket-league.png" width="50" height="50"/>Rocket League
            </li>
            <li>
                <img src="https://icon-library.com/images/overwatch-logo-icon/overwatch-logo-icon-28.jpg" width="50" height="50"/>Overwatch
            </li>
        </ul>
      </div>

      <div style="margin-top: 20px;">
          
      </div>

      <div style="margin-top: 40px;">
        I'm <strong>currently looking for a job</strong> as a Computer Scientist/Software Engineer/Game Developer. 
        You can reach me at <a href="mailto:gclark1013@gmail.com">gclark1013@gmail.com</a> or <router-link to="/contact">through one of these</router-link>.
      </div>
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

.games_list {
    list-style: none
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