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
        I'm a fullstack web-developer who leans towards the front-end of things.
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
        </v-img>

        <v-card-text class="text--primary">

          <div>
            <h2 class="mb-3">
              Mysteries Of Existence 
            </h2>
            <h4 style="color:#38ef7d">
                Google Adsense | Analytics | SSR | Scores 100 on SEO & as a PWA app |
            </h4>
            <p class="mt-3">
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
            style="margin-top: 1.6em;"
      
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

        </v-img>

        <v-card-text class="text--primary">
          <h2 class="mb-3">
            RoboFriends 
          </h2>
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
      <!-- Second Row -->
      <v-layout>
        <!-- Weather App -->
        <v-card
          class="ml-2 mr-2 mt-5"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="/weatherFinder.png"
          >
          </v-img>

          <v-card-text class="text--primary">

            <div>
              <h2 class="mb-3">
              Weather App
              </h2>
              <p>
                Built with React.js, the app makes an API request and filters to the given City and Country.
                Then display's the weather data.
              </p>
              <p>
                Was built back in 2018 while I was initially learning React.js.
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
        <!-- TGIF -->
        <v-card
          class="ml-2 mr-2 mt-5"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="/TGIF.png"
          >
          
          </v-img>

          <v-card-text class="text--primary">

            <div>
            <h2 class="mb-3">
              Thank God It's Fair
              </h2>
              <p>
                This was a practice exercise we had 4 days to solve during my coding bootcamp in Barcelona
                in early 2019.
              </p>
              <p>
                The website is built with classical HTML5, CSS3 and Vanilla JS, and was a fun project
                where I learnt a lot about filtering and proper implementation of Higher Order Functions.
              </p>
            </div>
          </v-card-text>
          <v-card-actions>
          <a
            href="https://zealous-fermat-8090e8.netlify.com/"
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
      <!-- Third Row -->
       <v-layout>
        <!-- Bookstore  -->
        <v-card
          class="ml-2 mr-2 mt-5"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="/bookStore.png"
          >
          </v-img>

          <v-card-text class="text--primary">

            <div>
              <h2 class="mb-3">
                Bookstore
              </h2>
              <p>
                Built during my coding bootcamp in Barcelona. 
              </p> 
              <p> 
                This is a Bookstore App written
                with HTML5, CSS3 & Vanilla JS. It also filters through books, has custom built animations
                and a carousel library.
              </p>
              <p>
                Built in early 2019
              </p>
            </div>
          </v-card-text>
          <v-card-actions>
          <a
            href="https://dazzling-shaw-83cb49.netlify.com/"
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
        <!-- TGIF -->
        <v-card
          class="ml-2 mr-2 mt-5"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="/TGIF.png"
          >
          
          </v-img>

          <v-card-text class="text--primary">

            <div>
            <h2 class="mb-3">
              Thank God It's Fair
              </h2>
              <p>
                This was a practice exercise we had 4 days to solve during my coding bootcamp in Barcelona
                in early 2019.
              </p>
              <p>
                The website is built with classical HTML5, CSS3 and Vanilla JS, and was a fun project
                where I learnt a lot about filtering and proper implementation of Higher Order Functions.
              </p>
            </div>
          </v-card-text>
          <v-card-actions>
          <a
            href="https://zealous-fermat-8090e8.netlify.com/"
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
