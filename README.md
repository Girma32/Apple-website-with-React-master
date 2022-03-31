## Project Title ##

Apple Website Recreated Using React


## Introduction ##

This project shows how the current Apple's website can be recreated using React. It also demonstrates how we can use Bootstrap along with React to build a responsive website. 

## Description ##

To rebuild Apple's current website, I created components for various pages using React. The app implements routing by passing each path/page and rendering the components for each page based on the page's URL. If the user navigates to a wrong path or a path that not defined by the route, a separate component is included to display a 404 page. I imported switch component that react router provides to render the defined paths, but to show the 404 page when the path user entered does not match the defined pages. The COVID Alert path is defined outside the switch component because it shares the same path with Main page, and we want to display it only when user navigates to the Main page. The recreated website is also modified to display Apple’s channel by making YouTube API request. 

## Technology ##

React.js, Bootstrap

## Install dependencies ##
npm install

## Author ##

Tewodros Negusse
  

## Acknowledgments ##

Many thanks to EvangadiTech and Adugna Bekele.




