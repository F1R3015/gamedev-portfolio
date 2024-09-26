<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      I'm <strong>Juan José Jiménez González</strong>, a computer science student at the Universidad de Málaga.
      Since a young age, I've been involved in the world of game development, and now I am currently developing some personal project while completing my degree.
      <br />
      <br />I have a grade point average of 7.94 out of 10 in my academic record and recived honors in 3 subjects. I have participated in game jams and in university programming contests.
  
      <br />
      <br />Besides games, I have interest in films, books and sports.

      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/cv-en.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF 🇬🇧</a>
        <a class="download-link" href="d/cv-es.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Descargar como PDF 🇪🇸</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="photo">
      <img src="img/resume-photo.png" alt="Photo" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
     

      <h2>Skills</h2>

      <div class="skill-set">
        <h3>Languages</h3>
        <div class="skill">C#</div>
        <div class="skill">C++</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Java</div>
        <div class="skill">TypeScript</div>
        <div class="skill">SQL</div>
        <div class="skill">Python</div>
        <div class="skill">Haskell</div>
        <div class="skill">GameMaker Language</div>
      </div>

      <div class="skill-set">
        <h3>Gamedev</h3>
        <div class="skill">Unity</div>
        <div class="skill">GameMaker</div>
        <div class="skill">Godot</div>
        <div class="skill">Unreal</div>
      </div>
      <div class="skill-set">
        <h3>Web and Fullstack</h3>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">Angular</div>
      </div>
      <div style="clear:both" />

      <h2>Education</h2>

      <h3>University of Malaga</h3>
      <h4>Computer Science degree</h4>

      <h2>Languages</h2>

      <h3>Spanish</h3>
      <div>Native</div>

      <h3>English</h3>
      <div>C1</div>


      <h2>Besides...</h2>
      <div>
        <h3>I ❤️ Videogames</h3>
        <div>My favourite game: Outer Wilds, if you haven't played, go blind.</div>

        <h3>I 🧡 Sports</h3>
        <div>I like to do water sports like sailing and windsurf ( Have been champion in my hometown ), but also like others like basketball and volleyball.</div>

        <h3>I 💛 Anime and Manga</h3>
        <div>I enjoy series such as Vagabond, Berserk, Dragon Ball, Dandadan...</div>

        <h3>I 💚 Cinema</h3>
        <div>The xenomorph is a terrifying creature. I love it.</div>

        <h3>I 💜 Cooking</h3>
        <div>Making my own food is a delicious task.</div>

      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    
  },
});
</script>

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
  height: 300px;
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