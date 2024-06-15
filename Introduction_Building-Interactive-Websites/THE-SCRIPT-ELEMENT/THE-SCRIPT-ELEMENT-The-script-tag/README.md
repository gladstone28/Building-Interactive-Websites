


THE SCRIPT ELEMENT
The <script> tag
3 min
The <script> element allows you to add JavaScript code inside an HTML file. Below, the <script> element embeds valid JavaScript code:
```
<h1>This is an embedded JS example</h1>
<script>
  function Hello() {
    alert ('Hello World');
  }
</script>
```
Frankly, without the <script> tag, websites would be unclickable and a bit boring.

The <script> element, like most elements in HTML, has an opening and closing angle bracket. The closing tag marks the end of the content inside of the <script> element. Just like the <style> tag used to embed CSS code, you use the <script> tag to embed valid JavaScript code.


### Instructions
Checkpoint 1 Passed

Copy this JavaScript code and paste it between the opening and closing <script> tags.
```
function blooming() {
  var image = document.getElementById('myImage');
  if (image.src.match("normal")) {
    image.src = "flower.png";
  } else {
    image.src = "normal.png";
  } 
}   
```
Then, click Run when you are finished and click on the Codecademy logo.
