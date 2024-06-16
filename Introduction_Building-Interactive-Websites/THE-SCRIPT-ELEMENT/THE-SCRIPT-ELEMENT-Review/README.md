Lesson link:

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-building-interactive-websites/tracks/fscj-22-building-interactive-websites/modules/wdcp-22-javascript-and-the-dom-56951714-b66d-4898-88b7-8f4696ed549f/lessons/script-element/exercises/script-element-review



THE SCRIPT ELEMENT
Review

Let’s review.

- HTML creates the skeleton of a webpage, but JavaScript introduces interactivity

- The <script> element has an opening and closing tag. You can embed JavaScript code inbetween the opening and closing <script> tags.

- You link to external JavaScript files with the src attribute in the opening <script> tag.

- By default, scripts are loaded and executed as soon as the HTML parser encounters them in the HTML file, the HTML parser waits to load the entire script before from proceeding to parse the rest of the page elements.

- The defer attribute ensures that the entire HTML file has been parsed before the script is executed.

- The async attribute will allow the HTML parser to continue parsing as the script is being downloaded, but will execute immediately after it has been downloaded.

- The old convention was to put scripts right before the **</body>** tag to prevent the script from blocking the rest of the HTML content. Now, the convention is to put the script tag in the **<head>** element and to use the defer and async attributes.
