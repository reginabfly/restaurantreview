## Restaurant Reviews Project

For the **Restaurant Reviews** projects, I converted a static webpage to a mobile-ready web application. I took a static design that lacks accessibility and converted the design to be responsive on different sized displays and accessible for screen reader use. I also created a service worker to begin the process of creating a seamless offline experience for the users.

### Specification

I was provided the code for a restaurant reviews website which included a lot of issues. It was barely usable on a desktop browser, much less a mobile device. It didn't include any standard accessibility features, and it didn't work offline at all. I had to update the code to resolve these issues while still maintaining the included functionality. 

### The Steps It Took

1. In the folder where all the files are located, I started up a simple HTTP server to served up the site files on my local computer. Python has some simple tools to do this. In a terminal, you can check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
2. While my server was running, I visited the site: `http://localhost:8000`, and looked around for a bit to see what the current experience looked like.
3. I explored the provided code, and started making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. I wrote code to implement the updates to get this site on its way to being a mobile-ready website.

## Google Maps:

This repository uses [Google Maps](https://developers.google.com/maps/documentation/javascript/get-api-key). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Google Maps](https://developers.google.com/maps/documentation/javascript/get-api-key). Replace the text YOUR_GOOGLE_MAPS_API_KEY in index.html and restaurant.html with your own key. The first year is free when signing up for an API at Google.

## Credits

This project was the fifth project in the Front-End Web Developer Nanodegree at [Udacity.com](https://www.udacity.com/). 


