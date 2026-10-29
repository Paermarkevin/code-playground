<!DOCTYPE html>
<html>
  <head>
    <title>DOM practice</title>
  </head>
  <body>
    <h1 id="myHeading">Hello, world!</h1>
    <button onclick="changeContent()">click Me</button>
    <script>
      function changeContent() {
        const heading= documnet.getElementById("myHeading");
        heading.innerText = "You clicked the button!";
        heading.style.color ="blue";
        heading.style.backgroundColor = "Ligthtyellow";
    </script>
  </body>
</html>
