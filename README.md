Assignment 4 - Creative Coding: Interactive Multimedia Experiences
===

Due: September 27th, by 11:59 PM.

For this assignment we will focus on client-side development using popular audio/graphics/visualization technologies; the server requirements are minimal. The goal of this assignment is to refine our JavaScript knowledge while exploring the multimedia capabilities of the browser.

Baseline Requirements
---

Your application is required to implement the following functionalities:

- A server created using Express (you can also use an alternative server framework such as Koa) for basic file delivery and middleware. Your middleware stack should include the `compression` and `helmet` [middlewares]((https://expressjs.com/en/resources/middleware.html)) by default. You are not required to use Glitch for this assignment (but using Glitch is fine!); [Heroku](https://www.heroku.com) is another excellent option to explore. The course staff can't be resposible for helping with all other hosting options outside of Glitch, but some of us do have experience with other systems. It also never hurts to ask on Slack, as there's 99 other classmates who might have the experience you're looking for!
- A client-side interactive experience using at least one of the web technologies frameworks we discussed in class over the past week.
  - [Three.js](https://threejs.org/): A library for 3D graphics / VR experiences
  - [D3.js](https://d3js.org): A library that is primarily used for interactive data visualizations
  - [Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API): A 2D raster drawing API included in all modern browsers
  - [SVG](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API): A 2D vector drawing framework that enables shapes to be defined via XML.
  - [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API): An API for audio synthesis, analysis, processing, and file playback.
- A user interface for interaction with your project, which must expose at least six parameters for user control. [dat.gui](https://workshop.chromeexperiments.com/examples/gui/#1--Basic-Usage) is highly recommended for this. You might also explore interaction by tracking mouse movement via the `window.onmousemove` event handler in tandem with the `event.clientX` and `event.clientY` properties. Consider using the [Pointer Events API](https://developer.mozilla.org/en-US/docs/Web/API/Pointer_events) to ensure that that mouse and touch events will both be supported in your app.
- Your application should display basic documentation for the user interface when the application first loads. This documentation should be dismissable, however, users should be able to redisplay it via either a help buton (this could, for example, be inside a dat.gui interface) or via a keyboard shortcut (commonly the question mark).
- Your application should feature at least two different ES6 modules that you write ([read about ES6 modules](https://www.sitepoint.com/understanding-es6-modules/)) and include into a main JavaScript file. This means that you will need to author *at least three JavaScript files* (a `app.js` or `main.js` file and two modules). We'll discuss modules in class on Monday 9/23; for this assignment modules should contain at least two functions.
- You are required to use a linter for your JavaScript. There are plugins for most IDEs, however it will be difficult to run the linter directly in Glitch. If you haven't moved to developing on your personal laptop and then uploading to Glitch when your project is completed, this is the assignment to do so!
- Your HTML and CSS should validate. There are options/plugins for most IDEs to check validation.

The interactive experience should possess a reasonable level of complexity. Some examples:
### Three.js
- A generative algorithm creates simple agents that move through a virtual world. Your interface controls the behavior / appearance of these agents.
- A simple 3D game
- An 3D audio visualization of a song of your choosing. User interaction should control aspects of the visualization. 
### Canvas
- Implement a generative algorithm such as [Conway's Game of Life](https://bitstorm.org/gameoflife/) (or 1D cellular automata) and provide interactive controls. Note that the Game of Life has been created by 100s of people using <canvas>; we'll be checking to ensure that your implementation is not a copy of these.
- Design a 2D audio visualizer of a song of your choosing. User interaction should control visual aspects of the experience. 
### Web Audio API
- Create a screen-based musical instrument using the Web Audio API. You can use projects such as [Interface.js](http://charlie-roberts.com/interface/) or [Nexus UI](https://nexus-js.github.io/ui/api/#Piano) to provide common musical interface elements, or use dat.GUI in combination with mouse/touch events (use the Pointer Events API). Your GUI should enable users to control aspects of sound synthesis.
### D3.js
- Create visualizations using the datasets found at [Awesome JSON Datasets](https://github.com/jdorfman/Awesome-JSON-Datasets). Experiment with providing different visualizations of the same data set, and providing users interactive control over visualization parameters and/or data filtering. Alternatively, create a single visualization with using one of the more complicated techniques shown at [d3js.org](d3js.org) and provide meaningful points of interaction for users.

Deliverables
---

Do the following to complete this assignment:

1. Implement your project with the above requirements.
3. Test your project to make sure that when someone goes to your main page on Glitch/Heroku/etc., it displays correctly.
4. Ensure that your project has the proper naming scheme `a4-yourname` so we can find it.
5. Fork this repository and modify the README to the specifications below. *NOTE: If you don't use Glitch for hosting (where we can see the files) then you must include all project files that you author in your repo for this assignment*.
6. Create and submit a Pull Request to the original repo. Name the pull request using the following template: `a4-gitname-firstname-lastname`.

Sample Readme (delete the above when you're ready to submit, and modify the below so with your links and descriptions)
---

## TODO

https://a4-anaghalate.glitch.me

- the goal of the application WAS to create some sort of interactive game which would replicate tetris
- I faced several challanges and had all of my assignments due on this friday and thus was unable to complete the project but did finish the server side aspect
