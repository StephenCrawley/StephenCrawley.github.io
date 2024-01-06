<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Stephen Crawley</h2>

<div class="row">
  <div class="column" style="background-color:#F9F6EE;">
    <h2>Links</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#fff;">
    <h2>CV</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>
