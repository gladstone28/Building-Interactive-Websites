Lesson link:

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-building-interactive-websites/tracks/fscj-22-building-interactive-websites/modules/wdcp-22-javascript-and-the-dom-56951714-b66d-4898-88b7-8f4696ed549f/lessons/script-element/exercises/script-element-async



# THE SCRIPT ELEMENT

## Async attribute

The async attribute loads and executes the script asynchronously with the rest of the webpage. This means that, similar to the defer attribute, the HTML parser will continue parsing the rest of the HTML as the script is downloaded in the background. However, with the async attribute, the script will not wait until the entire page is parsed: it will execute immediately after it has been downloaded. Here is an example of the async tag:
```
<script src="example.js" async></script>
```
When is it useful?

async is useful for scripts that are independent of other scripts in order to function accordingly. Thus, if it does not matter exactly at which point the script file is executed, asynchronous loading is the most suitable option as it optimizes web page load time.


### Instructions

Checkpoint 1 Passed

1. Currently our text is pink because in our style.css file, we have a ruleset for that.

Add async attribute to the turnBlue.js script to optimize load speed. Notice that once the turnBlue.js script is loaded, the text turns blue!

Similar to defer, we can add the async attribute to a <script> inside the <head> and have it load after elements below load first.

Depending on the speed of your internet, the loading of the page should be pretty fast so you probably won’t even see the text change from pink to blue!
