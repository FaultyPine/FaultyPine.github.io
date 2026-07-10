<template>
  <div style="margin-bottom: 80px;">
    <h1>Grayson Clark</h1>

    <div class="paragraph">

      <div style="margin-top: 40px;">
        I'm currently employed as a <strong>Game Engine Programmer</strong>. 
        You can reach me at <a href="mailto:gclark1013@gmail.com">gclark1013@gmail.com</a> or <router-link to="/contact">through one of these</router-link>.
      </div>

        
      <h2><u>Skill Highlights</u></h2>

      <h3>C++</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li><a href="https://github.com/FaultyPine/tiny_engine">Tiny Engine</a> - a toy rendering engine backed by OpenGL</li>
            <li>Fighting game (rollback) netcode with clock synchronization and integrated (in-client) matchmaking. See <a href="https://github.com/FaultyPine/Brawlback">Brawlback asm repo</a> and <a href="https://github.com/FaultyPine/dolphin">the dolphin fork</a>.</li>  
            <li><a href="https://github.com/FaultyPine/HDR-Installer-Homebrew">HDR-Installer</a> - a Nintendo Switch homebrew application that allows users to install, update, and modify the Hewdraw Remix mod directly from their switch with a simple TUI-esc menu</li>
            <li><a href="https://github.com/FaultyPine/UltimateModShop">UltimateModShop</a> - a Nintendo Switch homebrew application that allows users to install, update, remove, and browse Smash Ultimate mods from <a href="https://gamebanana.com/games/6498">GameBanana</a> directly on their switch.</li>
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
            <li>Built multiple <a href="https://github.com/skyline-dev">Skyline</a> plugins that modify code in Super Smash Bros Ultimate (including <a href="https://github.com/FaultyPine/SSBU_Twitch_Integration">Twitch integration</a>!).</li> 
            <li>Transferred the <a href="https://github.com/HDR-Development">HewDraw Remix</a> mod's codebase from C++ to Rust.</li> 
        </ul>
      <h3>JavaScript</h3>
      <div class="margin-top: 40px;">
        <ul>
            <li>Researched and implemented the Wave Function Collapse algorithm</li> 
            Watch it generate random permutations <a href="https://github.com/FaultyPine/WaveFunctionCollapseVisualizer/blob/master/wfc.gif">here!</a>
            <!--<iframe src="WFC/index.html" frameborder="0" height="650" width="650"></iframe>-->
        </ul> 
      </div>
      </div>

      <h2><u>Education</u></h2>

      <h3>University: 2020-2024</h3>
      <div>Graduated from Indiana University Bloomington with a major in Computer Science and a specialization in Game Development</div>

      <h3>High School Diploma: 2016 - 2020</h3>
      <div>Graduated from Deerfield High School</div>

      <h2><u>Extras</u></h2>
      <div>
        <h3>Soccer</h3>
        <div>Played since I was 7. Midfielder. Still play pickup games on Sundays!</div>

        <h3>Volleyball</h3>
        <div>Libero/defender. Been into Beach volleyball lately</div>

        <h3>Reading</h3>
        <div>Love me some fantasy books. Currently reading the Stormlight Archive by Brandon Sanderson.</div>

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