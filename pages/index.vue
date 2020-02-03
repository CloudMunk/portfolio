<template>
  <v-layout class="hidden-sm-and-down">
    <v-flex md3 lg4 xl4>
      <h1 class="underline mb-5">Bio</h1>
      <v-img
        src="/moi2.jpg"
      >

      </v-img>
      <p class="mt-5">
       Fullstack Web developer | Writer | Entrepreneur | Polyglot
      </p>
      <p class="mt-5">
       Hi there, my name is Anestis!
      </p>
      <p class="mt-5">
        I'm a fullstack web-developer who leans towards the fron-end of things.
        I've worked and built projects with Javascript front-end frameworks like
        <strong>React.js</strong>, <strong>Vue.js</strong>,<strong>Nuxt.js</strong>,
        but also using classical set-ups in Vanilla JS with HTML5 and CSS3.
      </p>
    </v-flex>
    <v-divider
      class="mx-4"
      inset
      vertical
    ></v-divider>


  <!-- PROJECTS -->
    <v-flex md9 lg8 xl8>
      <v-layout justify-center class="mb-5">
         <h1 class="underline">Projects</h1>
      </v-layout>
      <v-layout>
        <!-- Mysteries of Existence -->
      <v-card
        class="ml-2 mr-2"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
          src="/pyramidMilkyWay.jpg"
        >
          <v-card-title>Mysteries Of Existence</v-card-title>
        </v-img>

        <v-card-text class="text--primary">

          <div>
            <p>
              Passion project built over the Christmas Holidays in 2019.
            </p>
            <p>
              Project was built utilizing Nuxt.js & Vuetify with Storyblok acting as a
              headless CMS for easy intergration to post content and articles.
            </p>
          </div>
        </v-card-text>
        <v-card-actions>
         <a
          href="https://www.mysteriesofexistence.com"
          target=_blank
          class="noDeco"
          >
            <v-btn
            color="orange"
            text
      
          >
            Go to Website
          </v-btn>
          </a>   
        </v-card-actions>
      </v-card>
      <!-- Robo Friends -->
      <v-card
        class="ml-2 mr-2"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
          src="/RoboFriends.png"
        >
          <v-card-title>RoboFriends</v-card-title>
        </v-img>

        <v-card-text class="text--primary">

          <div>
            <p>
              React.js Project that filters through Robots that are generated through an API request.
            </p>
            <p>
              Built this project back in early 2018 while I was learning how to use React.js and practice some
              search functionalities through API requests.
            </p>
          </div>
        </v-card-text>
        <v-card-actions>
         <a
          href="https://sad-kare-e79291.netlify.com/"
          target=_blank
          class="noDeco"
          >
            <v-btn
            color="orange"
            text
      
          >
            Go to Website
          </v-btn>
          </a>   
        </v-card-actions>
      </v-card>
      </v-layout>
     <v-layout>
       <v-card
        class="ml-2 mr-2 mt-5"
        max-width="400"
      >
        <v-img
          class="white--text align-end"
          height="200px"
          src="/RoboFriends.png"
        >
          <v-card-title>RoboFriends</v-card-title>
        </v-img>

        <v-card-text class="text--primary">

          <div>
            <p>
              React.js Project that filters through Robots that are generated through an API request.
            </p>
            <p>
              Built this project back in early 2018 while I was learning how to use React.js and practice some
              search functionalities through API requests.
            </p>
          </div>
        </v-card-text>
        <v-card-actions>
         <a
          href="https://sad-kare-e79291.netlify.com/"
          target=_blank
          class="noDeco"
          >
            <v-btn
            color="orange"
            text
      
          >
            Go to Website
          </v-btn>
          </a>   
        </v-card-actions>
      </v-card>
     </v-layout>
    </v-flex>
  </v-layout>
</template>

<script>


export default {
  components: {

  }
}
</script>

<style scoped>
.underline {
  text-decoration: underline;
}
.noDeco {
  text-decoration: none;
}
</style>
