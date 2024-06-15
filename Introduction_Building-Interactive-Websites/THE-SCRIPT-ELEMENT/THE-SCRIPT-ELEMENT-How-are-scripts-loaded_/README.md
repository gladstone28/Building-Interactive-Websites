lesson Link

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-building-interactive-websites/tracks/fscj-22-building-interactive-websites/modules/wdcp-22-javascript-and-the-dom-56951714-b66d-4898-88b7-8f4696ed549f/lessons/script-element/exercises/script-element-load


# THE SCRIPT ELEMENT

### How are scripts loaded?

A quick recap: the <script> element allows HTML files to load and execute JavaScript. The JavaScript can either go embedded inside of the <script> tag or the script tag can reference an external file. Before we dive deeper, let’s take a moment to talk about how browsers parse HTML files into web pages. This informs where to include a <script> element inside your HTML file.

Browsers come equipped with HTML parsers that help browsers render the elements accordingly. Elements, including the <script> element, are by default, parsed in the order they appear in the HTML file. When the HTML parser encounters a <script> element, it loads the script then executes its contents before parsing the rest of the HTML. The two main points to note here are that:

The HTML parser does NOT process the next element in the HTML file until it loads and executes the <script> element, thus leading to a delay in load time and resulting in a poor user experience.
Additionally, scripts are loaded sequentially, so if one script depends on another script, they should be placed in that very order inside the HTML file.
The GIF below displays two scripts being loaded. The first script makes a Watering Can appear, the second script makes a Flower appear. This shows how scripts are loaded sequentially, and how they pause the HTML parser, which is why “Blooming” appears at the end.


### Instructions
Checkpoint 1 Enabled
1. Oops! In the code editor script2.js depends on a variable in script1.js causing an error (we actually want our text to be blue instead of pink). Switch the order of the scripts so that they load appropriately.

Rearrange the order of <script>s so that the one with src="script1.js" is above src="script2.js".

To see the error, right click on the page and select inspect. You’ll see a panel show up with multiple tabs at its top. Click on the console tab to see the error. For more information check out this article on dev tools, specifically the section “Debug your JavaScript Using the Console Tool”.

