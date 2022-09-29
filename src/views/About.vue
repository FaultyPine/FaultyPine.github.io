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

        
      <h2><u>Skill Highlights</u></h2>

      <h3>C++</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li>Fighting game (rollback) netcode with clock synchronization and integrated (in-client) matchmaking.</li>  
            <li>'Launcher' application that provides updates to basic users, and access to dev builds only for contributors/developers.</li> 
        </ul>
      </div>
      <h3>Python</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li><a href="https://github.com/FaultyPine/HeapRegionDiffGenerator">Script</a> that parses binary differences between files and outputs a file that contains the differences between them (special format for use with Brawlback)</li> 
            <li><a href="https://github.com/FaultyPine/Salty-to-Skyline-ACMD-Porting-Script">Script</a> that takes converts SSBU C++ "ACMD" code and outputs Rust "ACMD" macro code.</li> 
        </ul> 
      </div>
      <h3>Rust</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li>Built multiple <a href="https://github.com/skyline-dev">Skyline</a> plugins that modify code in Super Smash Bros Ultimate (including Twitch integration!).</li> 
            <li>Transferred the <a href="https://github.com/HDR-Development">HewDraw Remix</a> mod's codebase from C++ to Rust.</li> 
        </ul>
      <h3>JavaScript</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li>Researched and implemented the Wave Function Collapse algorithm</li> 
            Watch it generate random permutations <a href="https://github.com/FaultyPine/WaveFunctionCollapseVisualizer">here!</a>
            <!--<iframe src="WFC/index.html" frameborder="0" height="650" width="650"></iframe>-->
        </ul> 
      </div>
      </div>

    <!--
      <div class="skill-set">
        <h3>Programming Languages</h3>
        <SkillRate name="C++" :rate="5" />
        <SkillRate name="Python" :rate="5" />
        <SkillRate name="C" :rate="4" />
        <SkillRate name="Java" :rate="4" />
        <SkillRate name="Rust" :rate="4" />
        <SkillRate name="C#" :rate="3" />
        <SkillRate name="JavaScript" :rate="3" />
        <SkillRate name="HTML" :rate="3" />
        <SkillRate name="CSS" :rate="2" />
        <SkillRate name="Shell Scripting" :rate="2" />
        <SkillRate name="Batch Scripting" :rate="2" />
      </div>

      <div class="skill-set">
        <h3>Tools</h3>
        <SkillRate name="Git" :rate="4" />
        <SkillRate name="Trello" :rate="5" />
        <SkillRate name="VSCode" :rate="5" />
        <SkillRate name="Unix/Command Line" :rate="4" />
        <SkillRate name="GDB" :rate="3" />
        <SkillRate name="Github Actions" :rate="3" />
      </div>
      <div style="clear:both" />
      -->

      <h2><u>Education</u></h2>

      <h3>High School Diploma: 2016 - 2020</h3>
      <div>Graduated from Deerfield High School</div>

      <h3>University: 2020-Present</h3>
      <div>Currently enrolled at Indiana University Bloomington majoring in Computer Science</div>


      <h2><u>Extras</u></h2>
      <div>
        <h3>Soccer</h3>
        <div>Played since I was 7. Midfielder</div>

        <h3>Volleyball</h3>
        <div>Honarary libero/defender</div>

        <h3>Reading</h3>
        <div>Love me some fantasy books. Currently reading the Kingkiller Chronicles.</div>

      </div>

    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="My Avatar" width="250" height="250" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<script lang="ts">
import Vue from "vue";
//import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    //SkillRate,
  },
});
</script>

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