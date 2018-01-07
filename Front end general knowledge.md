# Front end security

## Several ways of malicious attacks from front end (FE):

1. Cross-site scripting (XSS): malicious code to twitter
2. CORs allows cross-domain access. FE devs need to write `Acess-Control-Allow-Origin` header for parts of a website that need to be accessed by foreign sites and only a portion of them can do so.
   > Precaution: requesting party should validate the data received & the serving party should expose the absolute minimum possible features
3. HTML5 elements and APIs

# Web fundamental

## App shell

App shell is the architecture to build a progressive web app that requires minumal HTML, CSS and JS to power a user interface without network and cached for offline support. When a user visits a website often, app shell will stay the same and only request for dynamic data is sent and loaded.
