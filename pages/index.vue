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
      <!-- First Row -->
      <v-layout>
        <!-- Mysteries of Existence -->
        <a href="https://www.mysteriesofexistence.com"
            target=_blank
            class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 box"
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
            
                <v-btn
                  color="orange"
                  text
                  style="margin-top: 1.6em;"
              >
                Go to Website
              </v-btn> 
            </v-card-actions>
          </v-card>
        </a> 
        <!-- Robo Friends -->
        <a href="https://sad-kare-e79291.netlify.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 box"
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
              <h4 style="color:#38ef7d">
                    React.js | API | Vanilla JS | Search Filtering |
              </h4>
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
                <v-btn
                color="orange"
                text
                style="margin-top: 33px;"
              >
                Go to Website
              </v-btn> 
            </v-card-actions>
          </v-card>
        </a>
      </v-layout>
      <!-- Second Row -->
      <v-layout>
        <!-- Weather App -->
        <a href="https://adoring-goodall-ad12b9.netlify.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
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
                <h4 style="color:#38ef7d">
                    React.js | API | Vanilla JS | API Filtering |
                </h4>
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
                <v-btn
                color="orange"
                text
          
              >
                Go to Website
              </v-btn> 
            </v-card-actions>
          </v-card>
        </a>
        <!-- TGIF -->
        <a href="https://zealous-fermat-8090e8.netlify.com/"
            target=_blank
            class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
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
                <h4 style="color:#38ef7d">
                    HTML5| CSS3 | Vanilla JS |
                </h4>
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
                <v-btn
                color="orange"
                text
          
              >
                Go to Website
              </v-btn>
            </v-card-actions>
          </v-card>
        </a> 
      </v-layout>
      <!-- Third Row -->
       <v-layout>
        <!-- Bookstore  -->
        <a href="https://dazzling-shaw-83cb49.netlify.com/"
            target=_blank
            class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
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
                <h4 style="color:#38ef7d">
                    HTML5 | CSS3 | Vanilla JS |
                </h4>
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
                <v-btn
                color="orange"
                text
          
              >
                Go to Website
              </v-btn>  
            </v-card-actions>
          </v-card>
        </a> 
        <!-- NYSL -->
        <a href="https://compassionate-goodall-11cadd.netlify.com/"
          target=_blank
          class="noDeco"
        >
        <v-card
          class="ml-2 mr-2 mt-5 box"
          max-width="400"
        >
          <v-img
            class="white--text align-end"
            height="200px"
            src="/NYSL.png"
          >
          </v-img>
          <v-card-text class="text--primary">
            <div>
              <h2 class="mb-3">
                North Side Soccer League 
              </h2>
              <h4 style="color:#38ef7d">
                  HTML5 | CSS3 | Vanilla JS | Registration Forms |
              </h4>
              <p>
                A little leagues football page I built during my bootcamp in Barcelona, early 2019.
              </p>
              <p>
                The website is built with classical HTML5, CSS3 and Vanilla JS. 
                It takes in forms(registrations), displays google locations for where matches will take place,
                as well as serve as a contact point for the leagues parents.
              </p>
            </div>
          </v-card-text>
          <v-card-actions>
              <v-btn
              color="orange"
              text
            >
              Go to Website
            </v-btn>   
          </v-card-actions>
        </v-card>
      </a>
      </v-layout>
      <!-- Fourth Row -->
      <v-layout>
        <!-- Background Generator  -->
        <a
          href="https://eloquent-pare-0bde7f.netlify.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="/bgGenerator.jpg"
            >
            </v-img>
            <v-card-text class="text--primary">
              <div>
                <h2 class="mb-3">
                  Background Generator for CSS linear Gradients
                </h2>
                <h4 style="color:#38ef7d">
                    HTML5 | CSS3 | Vanilla JS |
                </h4>
                <p>
                  Built this to simplify creating linear backgrounds for my apps and also as practice.
                </p> 
                <p>
                  Written with HTML5, CSS3 & Vanilla JS. 
                </p>
                <p>
                  Built in early 2019
                </p>
              </div>
            </v-card-text>
            <v-card-actions>
                <v-btn
                color="orange"
                text
              >
                Go to Website
              </v-btn>  
            </v-card-actions>
          </v-card>
        </a>
        <!-- Sanity Blog -->
        <!-- <a
          href="https://sanity-gatsby-blog-web-prcn9bgo.netlify.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="/SanityBlog.png"
            >
            </v-img>
            <v-card-text class="text--primary">
              <div>
                <h2 class="mb-3">
                  A Sanity Blog
                </h2>
                <h4 style="color:#38ef7d">
                    GraphQL | React.js | Gatsby | JAMStack | Vanilla JS |
                </h4>
                <p>
                  A boilerplate Sanity Blog using GraphQL, React, Gatsby, JAMStack,
                  Vanilla JS
                </p>
                <p>
                  Boilerplate Blog for building quick, scalable & SEO friendly blogs for
                  bloggers & writers alike.
                </p>
              </div>
            </v-card-text>
            <v-card-actions>
                <v-btn
                color="orange"
                text
          
              >
                Go to Website
              </v-btn>   
            </v-card-actions>
          </v-card>
        </a> -->
      </v-layout>
      <!-- Fifth Row -->
      <v-layout>
        <!-- When Crypto News  -->
        <a
          href="https://www.whencryptonews.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="ml-2 mr-2 mt-5 box"
            max-width="400"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="/WhenCN.png"
            >
            </v-img>
            <v-card-text class="text--primary">
              <div>
                <h2 class="mb-3">
                  When Crypto News
                </h2>
                <h4 style="color:#38ef7d">
                    Vue.js | Vuex | Vanilla JS | Vuetify | Firebase | Axios |
                </h4>
                <p>
                Crypto Currency News Website
                </p> 
                <p>
                  This is a Crypto Currency News website that I built in the summer of 2019
                  shortly after graduating my coding Bootcamp in Barcelona.
                </p>
                <p>
                  The entirety of this websites creation was streamed live on Twitch.
                </p>
              </div>
            </v-card-text>
            <v-card-actions>
                <v-btn
                color="orange"
                text
          
              >
                Go to Website
              </v-btn>  
            </v-card-actions>
          </v-card>
        </a> 
        <!-- Crypto Sphere -->
         <a
          href="https://zen-brahmagupta-b4be79.netlify.com/"
          target=_blank
          class="noDeco"
        >
          <v-card
            class="mt-5 box"
            max-width="350"
          >
            <v-img
              class="white--text align-end"
              height="200px"
              src="/cryptoSphere2.png"
            >
            </v-img>
            <v-card-text class="text--primary">
              <div>
                <h2 class="mb-3">
                  CryptoSphere
                </h2>
                <h4 style="color:#38ef7d">
                    React.js | React-Router-DOM | Semantic UI |
                </h4>
                <p>
                  This was a fun little project I built from the ground up to teach myself
                  better how to use React.js while I was self-studying.
                </p>
                <p>
                  This was done in early 2018, and the idea later expanded to become When Crypto news which is 
                  built in Nuxt.js(Vue.js) instead of React.
                </p>
              </div>
            </v-card-text>
            <v-card-actions>
                <v-btn
                color="orange"
                text
              >
                Go to Website
              </v-btn>   
            </v-card-actions>
          </v-card>
        </a>
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
.box {
  transition: box-shadow .3s;
  border-radius:10px;
  float: left;
}
.box:hover {
  box-shadow: 0 0 11px #38ef7d; 
}
</style>
