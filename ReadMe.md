# Restaurant Reviws App:
 Final Project to Front-End Web Developer Course in **Udacity**
by Norah Aaljlan

## Idea of the Project
For the Restaurant Reviews projects, you will incrementally convert a static webpage that get code from [**Udacity**](https://github.com/udacity/mws-restaurant-stage-1/tree/google-maps) to a mobile-ready web application 

1- convert static design to reponsive on different size display.
2- Accessible to screen reader.
3- Progressive Web Application by caching some assets for offline use.

## Installation:
1-we need terminal so i used Git Bash
2- Editor for Html, CSS, ES6 JavaScript language, i used [**Brackets**](http://brackets.io/#).
3- we need to install [**Vagrant**](https://www.vagrantup.com/downloads.html) to run App on linux server before that i installed Virtual Machine (VM) Virtual Box

## SetUp:

1- I get starter code from    [**Udacity**](https://github.com/udacity/mws-restaurant-stage-1/tree/google-maps)) 
2- Then,Replace "Key=YOUR_GOOGLE_MAPS_API_KEY" in index.html and restaurant.html to Key="AIzaSyBL4B7__0PrfpavjYquz0stZXlLdY7QxC4" that copy it from my project in google api.
3- Enter terminal and excute the following:
* To bring Virtual Machine we need to go to directory /Vagrant then execute this command 
```
vagrant up
```
> Some times need to active code 
```
chcp.com 1252
```
Then Log 
```
vagrant ssh
```
After LogIN go to /vagrant directory
```
cd /vagrant
```
Then go to folder that i named RestaurantReviewApp

```
cd RestaurantReviewApp
```
Then, run server by using port 8000 
```
python -m SimpleHTTPServer 8000
```
>**note: i use Python2**

Finally visit site 
```
http://localhost:8000
```
## License
**Free Coding , Hell Yeah*

