# A World Made of Drawings

![](./images/harold.jpg)

## Introduction
In the 1955 children's book, [Harold and the Purple Crayon](https://en.wikipedia.org/wiki/Harold_and_the_Purple_Crayon) by Crockett Johnson, Harold is a little boy who creates his own virtual worlds just by drawing them with his magical purple crayon. Harold not only inspired generations of children, but his story also inspired some early computer graphics research in non-photrealistic rendering. This project brings Harold's magic to your computer screen by implementing portions of the paper, [Harold: A World Made of Drawings](https://dl.acm.org/citation.cfm?id=340927), presented by Cohen et al. at ACM NPAR 2000, the 1st International Symposium on Non-Photorealistic Animation and Rendering. A video of the original system can be viewed [here](https://mediaspace.umn.edu/media/t/1_gtj35asj). 

This project uses ray casting to implement the magic of Harold's purple crayon. The conversion of 2D screen coordinates to the 3D virtual world is done using pick rays and intersection tests. Drawing in the sky can be done by clicking and dragging the mouse through the sky and billboards can be created by clicking and dragging the mouse from the ground to the sky. The ground mesh can even be edited to create hills and valleys by clicking and dragging your mouse along the ground. Change the view of the camera by right-clicking and dragging the mouse.

## Prerequisites

To work with this code, you will first need to install [Node.js 16.17.0 LTS](https://nodejs.org/en/) (or newer) and [Visual Studio Code](https://code.visualstudio.com/). 

## Running

You will need to set up the initial project by pulling the dependencies from the node package manager with:

```
npm install
```

After that, you can compile and run a server with:

```
npm run start
```

Webpack should launch your program in a web browser automatically.  If not, you can run it by pointing your browser at `http://localhost:8080`.

## Acknowledgments

This assignment was based on content from CSCI 4611 Fall 2021 by [Daniel Keefe](https://www.danielkeefe.net/).

## License

Material for [CSCI 4611 Fall 2022](https://csci-4611-fall-2022.github.io/) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
