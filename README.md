# Kennel Live Renderer
 An in-browser, split-screen live editor for native depictions, powered by [Kennel](https://github.com/ZenithDevs/Kennel/).

## Try it Out!

Kennel Live Editor is available for use at https://edit.parcility.co/.

## Building
Requires [Browserify](http://browserify.org/).
```
# Install Browserify globally
npm install -g browserify
# Install Kennel
npm install
# Compile `bundle.js` for browser use
browserify wrapper.js -o bundle.js
# (and then push this directory to your web host, such as GitHub Pages!)
```