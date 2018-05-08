# April 8
- watched Traversy Do We Still Need jQuery? 

# April 9
- Javascript30 6. Type Ahead (Fetch + Regex)
- started WpCrafter 4hr build ecommerce website
  - researched hosting

# April 11
- Advanced CSS and Sass
  - convert Natours (so-far) to Sass
  - converting to 7-1 architecture (splitting into partials)
- watched sped up WpCrafter Ecommerce video

# April 12 (Thursday)
- Advanced Sass Create Custom Float Grid
- watched Ecommerce video

# April 15
- Features Section of Natours Project (Advanced CSS and Sass)
- watched video 1 of FunFunFunction "Object Creation in Javascript" series

# April 20
- Python Bootcamp Lists
- FFFunction video 6

# April 21
- Python Bootcamp Lists(slices) and List Comprehensions
- finished series FunFunFunction "Object Creation in Javascript" series
  - has been a routine to go out for coffee/watch video
- watch Vue video on scalable css techniques
  - really just mentioned BEM and <style scoped>  (also kind of mentioned CSS modules?)
- Javascript30 8. Canvas Paint
- downloaded Elementor Pro 2 release with Themer! + played with creating Header + dynamic "single" blog post

# April 22
- Python Bootcamp Dictionaries
- Advanced CSS + SASS finish Natours Tours Section (flip cards)
- watched FunFunFunction Iterators video
- Javscript30 10. Checkbox Holding Shift

# April 25
- Python Bootcamp Tuples and Sets
- watch wordpress Astra Hooks and Custom Headers video

# April 26
- Python Bootcamp Functions
- Advanced WebDev Bootcamp create Express/Mongo/JSON Api
  - getting ready to follow that Vue music app code-along
- playing with Elementor 2 Dynamic Content

# April 28
- Python Bootcamp Function Exercises
- watch Coding Tech Zen of Python talk
- AdvWebDev jQuery SPA
  - interesting jQuery solution of storing the data id (from mongo backend) on each <li> element as it's created

# April 29
- Python Bootcamp Function Exercises
- converted AdvWebDev jQuery TodoList SPA to use a Vue front-end (using Fetch API)
  - frustrated by not being able to get initial fetch requests working
    - lack of understanding of what VSCode Live-Server extension is doing
    - partial solution was adding header option to fetch post and put request
    - final solution was to just move the Vue code into the same project folder as Express API
  - deployed to Heroku + mLab
    - couldn't get local environment variables to work (?)
- put 3 projects onto quentinmckay.com
  - Canvas Paint (js30) + notes
  - Checkbox Select (js30) + notes
  - Vue SPA TodoList converted from jQuery
  - added CSS to posts Section to fix image widths
    - width: 100% !important;  // !important to override the inline-styles elementor puts on the images
    - height: auto;            // auto to keep the correct aspect-ratio (not sure where/how i remembered this)(go me!)

# April 30 (Monday - last day of school holidays)
- Python Bootcamp Function exercises
- Part 1 of freeCodeCamp youtube series Full Stack Web App using Vue + Express
  - setup the project
    - client: vue init webpack (said yes to all options but I disabled eslint(too strict)) (then npm install axios))
    - server: express morgan cors (eslint but that's pissing me off)
  - got simple connection happening between Register component and app.post('/register',...) endpoint
    - good explanation of 2-way data binding with v-model

# May 3
- Python Bootcamp Functions Part2
  - ```*args``` and ```**kwargs```
- 2nd half of 2nd video TabTracker
  - Joi backend registration info validation and error handling
  - Vuetify intro and registration component markup
- coffee + beginners guide to webpack
- reviewed traversy webpack crash course
- got webpack raw-loader working (for reading .py and .js files)
  - first step toward Python Bootcamp py/js rosetta site !

# May 6
- Python Bootcamp `**kwargs` imperfect translation to js + started Lambdas
- coffee + FunFunFunction async/await
- 25 mins of Video 3 of TabTracker
  - continuing use/exploration of Vuetify for inputs and buttons (still not sold on Material Design)
  - added Header, Login components
  - revisited use of <router-link> (well actually <v-btn to="register">)
  - + "manual" navigation with this.$router.push({name: 'register'})

# May 7
- Python Bootcamp Built-In Functions
- creating backend Login functionality using JWT (json web tokens) and started with bcrypt-nodejs