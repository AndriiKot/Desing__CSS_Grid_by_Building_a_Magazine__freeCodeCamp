
<a id=top></a>

# Building a Magazine

<details>
      <summary>
        <h4>Follow Links Steps</h4>
      </summary>
       
<table>
  <thead>
    <tr><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__000__title_" target="_self">Step 0</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__001__step__" target="_self">Step 1</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__002__step__" target="_self">Step 2</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__003__step__" target="_self">Step 3</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__004__step__" target="_self">Step 4</a></th><tr><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__005__step__" target="_self">Step 5</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__006__step__" target="_self">Step 6</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__007__step__" target="_self">Step 7</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__008__step__" target="_self">Step 8</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__009__step__" target="_self">Step 9</a></th><tr><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__010__step__" target="_self">Step 10</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__011__step__" target="_self">Step 11</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__012__step__" target="_self">Step 12</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__013__step__" target="_self">Step 13</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__014__step__" target="_self">Step 14</a></th><tr><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__015__step__" target="_self">Step 15</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__016__step__" target="_self">Step 16</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__017__step__" target="_self">Step 17</a></th><th><a href="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp//tree/main/steps/__018__step__" target="_self">Step 18</a></th></tr>
  </thead>
  <tbody>
  </tbody>
</table>
</details>

<h4>preview</h4>
    <img src="https://github.com/AndriiKot/Desing__CSS_Grid_by_Building_a_Magazine__freeCodeCamp/blob/main/images/previews/preview_step017.png" alt="preview_step017">
  

[back to top](#top)


<table>
  <thead>
      <tr><th height=33 width=100>CSS</th><th height=33 width=100>HTML5</th></tr>
  </thead>
  <tbody>
      <tr><td height=100 width=100><a href=https://www.w3.org/Style/CSS/ target="_self"><img src=https://github.com/AndriiKot/iconsSVG_and_linksDocs/blob/main/svg/css.svg alt=CSS></a></td><td height=100 width=100><a href=https://html.spec.whatwg.org/multipage/ target="_self"><img src=https://github.com/AndriiKot/iconsSVG_and_linksDocs/blob/main/svg/html.svg alt=HTML5></a></td></tr>
  </tbody>
</table>

[back to top](#top)



<details open>
  <summary>
    <h4>index.html</h4>
  </summary>



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap" />
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" />
    <link rel="stylesheet" href="./styles.css" />
    <title>Magazine</title>
  </head>
  <body>
    <main>
      <section class="heading">
        <header class="hero">
          <img class="hero-img" width="400" loading="lazy"src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" alt="freecodecamp logo">
          <h1 class="hero-title">OUR NEW CURRICULUM</h1>
          <p class="hero-subtitle">Our efforts to restructure our curriculum with a more project-based focus</p>
        </header>
        <div class="author">
          <p class="author-name">By <a rel="noreferrer" href="https://freecodecamp.org" target="_blank">freeCodeCamp</a></p>
          <p class="publish-date">March 7, 2019</p>
        </div>
        <div class="social-icons">
          <a href="https://www.facebook.com/freecodecamp"><i class="fab fa-facebook-f"></i></a>
          <a href="https://twitter.com/freecodecamp"><i class="fab fa-twitter"></i></a>
          <a href="https://instagram.com/freecodecamp"><i class="fab fa-instagram"></i></a>
          <a href="https://www.linkedin.com/school/free-code-camp"><i class="fab fa-linkedin-in"></i></a>
          <a href="https://www.youtube.com/freecodecamp"><i class="fab fa-youtube"></i></a>
        </div>
      </section>
      <section class="text">
       <p class="first-paragraph">
          Soon the freeCodeCamp curriculum will be 100% project-driven learning. 
          Instead of a series of coding challenges, 
          you'll learn through building projects - step by step. 
          Before we get into the details, let me emphasize: 
          we are not changing the certifications. All 6 certifications 
          will still have the same 5 required projects. 
          We are only changing the optional coding challenges.
       </p>
       <p>
          After years - years - of pondering these two problems and how to solve them, 
          I slipped, hit my head on the sink, and when I came to I had a revelation! A vision! 
          A picture in my head! A picture of this! 
          This is what makes time travel possible: the flux capacitor!
       </p>
       <p>
         It wasn't as dramatic as Doc's revelation in Back to the Future. 
         It just occurred to me while I was going for a run. 
         The revelation: the entire curriculum should be a series of projects. 
         Instead of individual coding challenges, we'll just have projects, 
         each with their own seamless series of tests. 
         Each test gives you just enough information to figure out how to get it to pass. 
         (And you can view hints if that isn't enough.)
       </p>
       <blockquote>
         <hr>
           <p class="quote">
            The entire curriculum should be a series of projects
          </p>
         <hr>
       </blockquote>
       <p>
         No more walls of explanatory text. No more walls of tests. Just one test at a time, as you build up a working project. Over the course of passing thousands of tests, you build up projects and your own understanding of coding fundamentals. There is no transition between lessons and projects, because the lessons themselves are baked into projects. And there's plenty of repetition 
         to help you retain everything because - hey - building projects in real life has plenty of repetition.
       </p>
       <p>
         The main design challenge is taking what is currently 
         paragraphs of explanation and instructions and packing 
         them into a single test description text. Each project 
         will involve dozens of tests like this. People will be coding the entire time, 
         rather than switching back and forth from "reading mode" to "coding mode".
       </p>
       <p>
         Instead of a series of coding challenges, people will be in 
         their code editor passing one test after another, 
         quickly building up a project. People will get into a real flow state, 
         similar to what they experience when they build the required projects 
         at the end of each certification. They'll get that sense of 
         forward progress right from the beginning. And freeCodeCamp will be a much smoother experience.
       </p>
      </section>
      <section class="text text-with-images">
        <article class="brief-history"></article>
        <aside class="image-wrapper"></aside>
      </section>
    </main>
  </body>
</html>



```



[back to top](#top)


</details>