<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Juan José Jiménez González</strong>, a computer science student at the Universidad de Málaga.<br/>
        I am passionate about video games, having been interested in developing games since a young age.
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">game jams</router-link> and <router-link to="/other-projects">personal projects</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently finishing my degree</strong> this academic year! You can reach me at <a href="mailto:juanfuego15@gmail.com">juanfuego15@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
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