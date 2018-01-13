  ## Website Performance Optimization portfolio project


  ## Getting started

  #### To run the project

  1. Check out the repository
  2. run a local server

    ```bash
    $> cd /path/to/your-project-folder
    $> python -m SimpleHTTPServer 8080
    ```

  3. Open a browser and visit localhost:8080

  #### To get a public URL
  1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

    ``` bash
    $> cd /path/to/your-project-folder
    $> ./ngrok http 8080
    ```

  2. Copy the public URL ngrok you can use this URL to use PageRank.
  
  #### DEMO
[See here](http://www.claudiofelis.com.br/udacity/).

  ## Work done

  ### index.htm, project-2058.html, project-mobile.html and project-webpeft.html

  * style.css minimized and changed to inline css.
  * Added "print" media query to print.css.
  * Added p async attribute to GA Script tag.
  * Alt attribute added to all images.
  * Added optimization of all images using grunt.

  ### pizza.html

  * Added missing meta tags
  * style.css and boostrap-grid.css were minimized and changed to inline css.
  * Added alt attribute to all images.
  * Added optimization of all images using grunt.
  * Changed main.js to main.min.js

  ### main.js

  * Correction of code indentation
  * changePizzaSizes function rewritten to avoid FSL
  * Determinedx function excluded due to its uselessness.
  * Refactored update function to avoid FSL

## Optmization Results

### PageSpeed

|      Files           |PageSpeed before optmization |PageSpeed after optmization  |
| -------------------: |:---------------------------:|:---------------------------:|
| index.html           |            82 / 30          |         99 / 95             |
| project-2048.html    |            86 / 93          |         99 / 97             |
| project-webperf.html |            89 / 79          |         99 / 97             |    
| project-mobile.html  |            76 / 81          |         99 / 97             |  
| pizza.html           |            90 / 31          |         99 / 97             |  

### Console.log

|     Time parameters              |       Before optmization    |      After optmization   |
| --------------------------------:| :-------------------------: | :----------------------: |
| Time to generate pizzas on load  |          7.5 ms             |         6.12ms           |
| Time to generate last 10 frames  |          24.56ms            |         0.37ms           |
| Time to resize pizzas            |          122.324            |         0.21ms           |    



For Audition: [Optmized Link (https://github.com/claudiofelis/frontend-nanodegree-mobile-portfolio)](http://www.claudiofelis.com.br/udacity/) - [Unoptmized Link (https://github.com/udacity/frontend-nanodegree-mobile-portfolio)](http://www.claudiofelis.com.br/udacity/)