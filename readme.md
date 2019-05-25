## Usage
Make sure index.html is being served by a http webserver, twitch embed breaks if you try opening it from your local fs. (no idea why)

If you have nowhere to deploy, localhost with python will do:
switch to a directory where you have your `index.html` , then
`python3 -m http.server`

(by default) Site will be available at:
`http://0.0.0.0:8000/index.html`

Add a list of comma separated channels:
`http://0.0.0.0:8000/index.html?channels=dasmehdi,bobross,hungry`

Hovering over a stream will unmute it and bring the quality to the best available. Same with fullscreen.