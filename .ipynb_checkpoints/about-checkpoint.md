---
layout: page
title: About Me
permalink: /about/
tags: about
---


<html>
<head>
<style>
* {
    box-sizing: border-box;
}

.column {
    float: left;
    width: 50%;
    padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
    content: "";
    clear: both;
    display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div class="column"><img src="/images/me.jpg" alt="me" style="width:100%"></div>
  <div class="column">Something about me</div>
</div>

</body>
</html>




