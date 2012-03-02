# Prototype WebRTC

This prototype is only available for Chrome/Chromium with support WebRTC.
This web application allow you to video chat with someone else by sharing a single link.


## Requirements

You have to install 

- node.js (socket.IO is directly provided with the sources)
- a HTTP server
- Chrome or Chromium > 18.0.1025 available in Chrome Dev or Chrome Canary repositories

## Installation

1. Get the sources
2. Move them in your www directory
3. Change the server address in index.php and webrtc.js if needed
4. Launch index.js in nodejs_server with node /path/to/your/www/nodejs_server/index.js
5. Open the page http://yourserver/
6. Then use the link given to your partner
7. Enjoy

# Credits

This project use the differents following projects :

- jQuery
- Bootstrap Twitter

And it's been inspired directly from this application : https://apprtc.appspot.com/