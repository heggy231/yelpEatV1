# yelpEatV1
YelpEat is a restaurant review web app that incorporates accessibility ("a11y") for diverse users for diverse screen sizes with various network speed.\

Some statistics on disability for the US:\
-----------------------------------------

----
> * Around 2% of the population has some kind of vision disability (i.e. are blind or have significant difficulty seeing even with glasses)
> * Around 50% of the population has some kind of clinically significant refractive error (a visual impairment which may be corrected with glasses if mild enough)
> * Around 8% of males and 0.5% of females have some form of color vision deficiency
> * Around 2% of adults have a hearing disability
> * Over 4% have a cognitive disability (difficulty remembering, concentrating, or making decisions)
----

## Project Overview: Stage 1
- Introduction video watch here >>> https://www.youtube.com/watch?time_continue=1&v=N-Tf905Oerk

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality. 

### Requirements
  1. Make the provided site fully responsive. All of the page elements should be usable and visible in any viewport, including desktop, tablet, and mobile displays. Images shouldn't overlap, and page elements should wrap when the viewport is too small to display them side by side.

  2. Make the site accessible. Using what you've learned about web accessibility, ensure that alt attributes are present and descriptive for images. Add screen-reader-only attributes when appropriate to add useful supplementary text. Use semantic markup where possible, and aria attributes when semantic markup is not feasible.

  3. Cache the static site for offline use. Using Cache API and a ServiceWorker, cache the data for the website so that any page (including images) that has been visited is accessible offline.

### What do I do from here?
- Option 1
1. Run with Web Server for Chrome
2. CHOOSE FOLDER to your site file local repo.
3. Check mark on Options: Accessible on local network
   Check mark on Auto show index.html
   Enter Port: 8887
   Set CORS headers
4. Set your URL to http://127.0.0.1:8887

- Option 2
1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 
  In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8777` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
2. With your server running, visit the site: `http://localhost:8777`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code.