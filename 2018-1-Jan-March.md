# Jan 1

- completed Part 4 of [Traversy Vue + FireStore](https://www.youtube.com/watch?v=cjEzK4me1k8)
- read up on using wordpress tinyMCE editor
- signed up to freeCodeCamp

# Jan 2

- completed Part 5 (new + edit) and 6 (deploy using GitHub Pages {useless}) of Traversy Vue + Firestore
  - couldn't get GitHub project hosting to work (apparently needs a workaround - not sure why)
- spent time learning Wordpress TinyMCE editor
  - why fonts kept reverting back to Georgia (b/c it was hard-coding font style every line)
  - how to use keyboard shortcuts / markdown-ish syntax (good stuff)

# Jan 3

- started Net Ninja Vue Tutorial Playlist (1-5)
- played with embedding CodePen pens in wordpress posts

# Jan 4

- Net Ninja Vue tutorials 6 - 9

# Jan 5

- Net Ninja Vue tutorials 10 - 15 (Punching Bag Game + Intro to Componenents!)

# Jan 6

- Net Ninja Vue tutorials 16 - 19 (vue-cli + files + nesting components)

# Jan 7

# Jan 8

- Net Ninja Vue tutorials 25 - 28 (Event Bus, Lifecycle Hooks, Slots, Dynamic Components)
- played with making logo for EA2 using free online logo apps (Canva, Logomakr) and online vector art

# Jan 9

- looked at Net Ninja Git Branching tutorial (he uses branches to save Lesson-1, Lesson-2, etc)
- learned about branching 

# Jan 10-13

- finished Net Ninja Vue playlist (stunning series)
- copied freeCodeCamp tribute page the other day

# Jan 14

- skimmed through freeCodeCamp 'Basic Javascript' and 'Object Oriented and Functional Programming'

# Jan 17

- got Net Ninja Vue tutorial Blog App to work on GitHub pages as project
  - using webpack-simple template (it's what Net Ninja used)
  - `$ npm run build`
  - change /dist to /docs
  - copy over index.html into /docs
  - remove '/' from front of src="/bundle.js"
  - also changed router mode from 'history' back to default hash (didn't work at first then i checked later and it was working. wtf?)
    

# Jan 18

- watch Traversy Webpack crash course
- updated Node from 6.10.2 to 8.9.4 (just downloaded the .msi and installed)
- freeCodeCamp Basic Algorithm testPalindrome (Regex)

# Jan 19

- Traversy CSS Grid Responsive Website Mobile-First tutorial
  - a strange one b/c uses Grid in a way I haven't seen anywhere before (adding `display: grid` to each section via class `.grid`)
  - also uses Flex with some fixed widths (seemingly effective but not recommended in the CodeTech talk by Grid pioneer Rachel Andrews)
- getting comfortable with the workflow for project (code -> GitHub Desktop Client -> create branches + merge -> push to GitHub -> create GitHub Project Page)

# Jan 20 - 22

- solidifying my workflow of putting past project onto quentinmckay.com

# Jan 23

- re-wrote Color Game from Colt Steele Web Developer Bootcamp
  - might be interesting to redo it using Vue
  
# Jan 24

- put Color Game on quentinmckay.com
- went through, took notes, and put Bootcamp To-Do List up as well

# Jan 25 - 29

- rewatched / took notes on Simple Express app and Heroku deployment
- put Yelpcamp on my site

# Jan 30 - Feb 5

- started Colt Steele Advanced Web Developer Bootcamp
  - so far finished first section on CSS Animation (Transforms, Transitions, Keyframes)
    - projects: push button, rising/setting sun
- watched video on Functional Programming (What the fuck is a monad?)
- watched video on mysql injections

# Feb 6 - Feb 14
- followed Advanced WebDevBootcamp Flexbox, Async Foundations, and Fetch sections
  - Fetch Random User example
- started Vue JS 2 - The Complete Guide (Maximillian Schwarzmuller)

# Feb 17
- wrote Monster Slayer in Vue

# Feb 24
- switched to VS Code over the weekend
  - main benefits
    1. integrated terminal (the terminal plugin in Atom was always a little bit janky)
    2. integrated linting (still not entirely sure what Intellisense is)
    3. integrated debugger
    4. reason I switched to Atom in the first place is because I liked the "look" 
        but I just downloaded a really popular theme to make Code look like Atom
- continuing Vue: The Complete Guide
  - coded Wonderful Quotes (second project of the course)

# Feb 25 - March 3
- put Monster Slayer and Wonderful Quotes on website
- Vue course
  - Section 11: Forms and Inputs
  - Section 12: Custom Directives
  - Section 13: Filters and Mixins
  - Section 14: Animations and Transitions
  - built the Super Quiz (with the flip animation)

# March 4
- wanted to add flash-red-when-wrong animation to Super Quiz (rather than ugly alert() like Max does)
  - researched how to re-trigger a css animation
    - 1st solution is to remove the triggering class via `setTimeout()` then re-add to `element.classList` (problem is duration is coded in both CSS and javascript)
    - 2nd solution is Web Animation API. Very cool! (pretty new and not implemented in all browsers yet)
  - going to go implement it tonight

# March 12
- "finished" the Super Quiz (haven't made a quentinmckay.com entry yet)

- finished vue-router and vuex sections
  - vuex is confusing (not entirely sure what benefits it provides other than allowing access to all the data from any component. All the getters/mutations/actions seem like an unnecessary amount of boilerplate). hopefully this gets cleared up during the Final Project in the next section.

# March 14
- wrote Stock Trader (final project of Vue course) project setup + basic css/layout + vue-router
- watched NetNinja Vuex tutorial playlist
  
# March 15
- added Vuex + Portfolio to Stock Trader

# March 16
- Wes Bos Javascript 30 - 1. Drum Kit

# March 18
- implemented 'Save & Load' button on Stock Trader
  - researched CSS + JS click to open dropdown (+ close when clicked away)
  - hooked up to Firebase (no authentication)

# March 19 - 25
- finished Stock Trader
- Javascript 30 2. Clock, 3. CSS Variables (Image Blur), 4. Array Cardio, 5. Flexbox Image Gallery

# March 26
- Javascript 30 6. Array Cardio

# March 28
- bought + started Colt Steele Python 3 Bootcamp
- started properly Advanced CSS and Sass
- started EAA logo (still need to play with colors)

# March 29
- Python Bootcamp (basics)
  - python 3 installation on Mac/Windows
  - VSCode python setup
