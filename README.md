<<<<<<< HEAD
<<<<<<< HEAD
# Practice Portfolio Project
=======
# Kevin Yang's Dev Portfolio
>>>>>>> be088a9119b749b2a92e710934b16f3d594ed7bf

Welcome to my repo where I keep up to date my portfolio. If you have any questions or would like to reach out, please message me at:
kyang812@yahoo.com.

<<<<<<< HEAD
### Featureset 1 (Do this when asked to, not before - week 3)
- Dev story copy
	- Replace the title "GRAYSCALE" in the main page with your name
	- add your short blurb about yourself below the title
	- in the section titled "ABOUT GRAYSCALE" change the title to "ABOUT <your first name>"
	- Add your developer story to the text below "ABOUT GRAYSCALE"

### Featureset 2 (Do this when asked to, not before - week 5)
- Hackathon 1 project add

### Featureset 3 (Do this when asked to, not before - week 7)
- Google maps api fix
	- go to <a href="https://cloud.google.com/maps-platform/?apis=maps" target="_blank">google maps api</a> and click "get started"
	- Enable the google maps platform and click "continue"
	- select a project and click "Create a new project"
	- name it 'practice-portfolio'
	- you likely have no billing set up for google, you'll need to do so next
		- google maps is free, but they need a CC on hand to make sure you are real and in case you do something dumb like get 1 trillion hits
		- create billing account
		- set your country
		- read/check the terms of service
		- pick your receipt of email preference (yes/no)
		- agree and continue
		- make sure your payment profile is filled out / correct
		- supply a credit card and associated information
		- you will get 1 year of credits, after that point you will be employed and probably not care
	- enable and google maps platform
		- click next
		- get your supplied api key
		- go to the bottom of the index.html file
		- find the google maps api and add your key in the part labeled YOUR_KEY_HERE
	- secure
		- click on api console
		- under api restrictions, 
			- click HTTP referrers (web sites)
			- in the input below, add your domain name with an https protocol (https://yourdomain.ext) (this will allow it to work on your server)
			- click save
			- add localhost as into the input (this will allow it to work on your local computer)
			- click save
			- allow up to 5 minutes for it to work properly then contact a staff member if it does not
		- test the page by starting it up (in a server locally) and seeing if the map below pops up.
	- switch maps to show your city
		- use the non-minified version of the JS file
			- in the index.html file, at the bottom, change the script src from grayscale.min.js to grayscale.js
			- save the index file
		- change the lat/lon of the google map
			- find your city or map location of preference by doing a google search for lat and lon.  For example "irvine lat/long"
				- note that North / East latitudes / longitudes will be written as positive numbers, South/West latitudes / longitudes will be written as negative numbers
				- eg "117.8265° W" will be "-117.8265"
			- go to js/grayscale.js
			- in grayscale.js at about line 40, there is a line that starts with "map.setCenter(new google.maps.LatLng("
			- change the lat/long given there to your desired lat/long


### Featureset 4 (Do this when asked to, not before - week 7)
- Hackathon 2 project add

### Featureset 5 (Do this when asked to, not before - week 7)
- Contact form data and validation

### Featureset 6 (Do this when asked to, not before - Week 8)
- Deploy to server as Dev
- Deploy to server as Production

### Featureset 7 (Do this when asked to, not before - week 9)
- Contact form email sending (sendgrid)
=======
# Kevin Yang's Dev Portfolio

Welcome to my repo where I keep up to date my portfolio. If you have any questions or would like to reach out, please message me at:
kyang812@yahoo.com.

=======
>>>>>>> be088a9119b749b2a92e710934b16f3d594ed7bf
```javascript
function hello() {
  console.log("Thanks for stopping by, hope you're having a great one!");
}# portfolio
<<<<<<< HEAD
>>>>>>> 61b22750cfc42f03bb1e364dbc1a71b5617b9b97
=======
>>>>>>> be088a9119b749b2a92e710934b16f3d594ed7bf
