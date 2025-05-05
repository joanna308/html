<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Block vs Inline Elements</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .section {
      padding: 20px;
      color: white;
    }

    .block-section {
      background-color: black;
    }

    .inline-section {
      background-color: rgb(142, 17, 17);
    }

    .inner-box {
      background-color: powderblue;
      color: black;
      padding: 20px;
      max-width: 500px;
      margin: 20px auto;
    }

    .highlight-box {
      background-color: bisque;
      color: black;
      padding: 20px;
      max-width: 600px;
      margin: 20px auto;
    }

    a {
      color: rgb(153, 12, 110);
    }

    ul {
      margin: 10px 0;
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <div class="section block-section">
    <h2>Block elements</h2>
    <p>Block elements start on a new line and always add some space before and after the element.</p>
    <p>Block elements are a little different from inline elements.</p>
    <p>Block elements take up all the available width before moving to the next line. They adjust to the width of the page.</p>
    <p>To center align the block element, use <code>width</code> and <code>margin: auto</code> like done here:</p>

    <div class="inner-box">
      <p>Some examples of block elements are:</p>
      <ul>
        <li>div</li>
        <li>address</li>
        <li>dd</li>
        <li>dt</li>
        <li>header</li>
        <li>pre</li>
      </ul>
      <p>For more examples of block elements, look at:
        <a href="https://www.w3schools.com/html/html_blocks.asp" target="_blank" title="block & inline elements">Block elements</a>
      </p>
    </div>

    <p>The <code>div</code> element defines a division or a section in an HTML document.</p>
    <p>The <code>div</code> element is often used as a container for other HTML elements.</p>
    <p>When used together with CSS, the <code>div</code> element can be used to style blocks of content like used here.</p>
    <p>If <code>width</code> and <code>margin: auto</code> are not used, it may look like the inline example below.</p>
  </div>

  <div class="section inline-section">
    <h2>Inline elements</h2>
    <p>Inline elements do not start on a new line.</p>
    <p>They continue on the same line that they are used on.</p>
    <p>Inline elements are almost the same as block elements except for the fact that they do not start on a new line.</p>
    <p>Inline elements take up as much width as necessary, unlike block elements that take up the entire width available.</p>

    <div class="inner-box">
      <p>Some examples of inline elements are:</p>
      <ul>
        <li>span</li>
        <li>a</li>
        <li>time</li>
        <li>input</li>
        <li>map</li>
        <li>abbr</li>
      </ul>
      <p>For more examples of inline elements, look at:
        <a href="https://www.w3schools.com/html/html_blocks.asp" target="_blank" title="block & inline elements">inline elements</a>
      </p>
    </div>

    <p>The <code>span</code> element defines a section in an HTML document.</p>
    <p>When used with CSS, <code>span</code> can be styled inline like this:</p>

    <div class="highlight-box">
      This sentence is using <span style="background-color:rgb(45, 212, 123); color:black"><i>span</i></span> to add styles like font and color, and highlight content inside the span tag.
    </div>
  </div>

</body>
</html>

