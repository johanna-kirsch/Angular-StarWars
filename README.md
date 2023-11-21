# Angular Project (2022)
This is a two-week project for a Mobile Web Development lecture from 2021/2022.

The goal was to create a responsive web page for a topic of our choice using Angular. 
Note that this is a programming exercise, not a web design one. 
The focus is on the correct utilization of Angular and Typescript as well as the implementation of forms, navigation and responsive elements. 

We implemented a Star Wars themed website that contains a quiz as well as some textual information. Note that the text in this project is in French because I studied in France at this point.

## How to run this application
1. Install dependencies: `npm install`
2. Build project: `npm run build`
3. Create a docker image: `docker build -t ng-star-wars . ` or load the provided image: `docker load < star_wars_image.tar`
4. Run it: `docker run -d -p 1234:80 ng-star-wars`
5. Open http://localhost:1234/

## Credits
- I worked on this project with [Jérémy H.](https://github.com/TheValemagne) (I forked our repository from his account to add some information)
- The droid loader that gets displayed before the quiz results was taken from [this CodePen project by Frank's Laboratories](https://codepen.io/franksLaboratory/pen/mdyewbW), licensed under the MIT license and therefore free of use.
