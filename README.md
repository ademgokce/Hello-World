<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<!--[if lt IE 9]>
    <script src="bower_components/html5shiv/dist/html5shiv.js"></script>
<![endif]-->

<link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
<body>

<div class="container">
  <header><h3>Welcomey to My Gallery</h3></header>
  <section id="content">
    <div class="gallery">
      <ul>
        <li><a class="fancybox" rel="group" href="images/img/image1.jpg" title="image"><img src="images/image1.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image2.jpg" title="image"><img src="images/image2.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image3.jpg" title="image"><img src="images/image3.jpg" height="250" width="150"alt="pictures"></a></li>
      </ul>
      <ul>
        <li><a class="fancybox" rel="group"href="images/img/image4.jpg" title="image"><img src="images/image4.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image5.jpg" title="image"><img src="images/image5.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image6.jpg" title="image"><img src="images/image6.jpg" height="250" width="150"alt="pictures"></a></li>
      </ul>
      <ul>
        <li><a class="fancybox" rel="group"href="images/img/image7.jpg" title="image"><img src="images/image7.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image8.jpg" title="image"><img src="images/image8.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image9.jpg" title="image"><img src="images/image9.jpg" height="250" width="150"alt="pictures"></a></li>
      </ul>
      <ul>
        <li><a class="fancybox" rel="group"href="images/img/image1.jpg" title="image"><img src="images/image1.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image2.jpg" title="image"><img src="images/image2.jpg" height="250" width="150"alt="pictures"></a></li>
        <li><a class="fancybox" rel="group"href="images/img/image3.jpg" title="image"><img src="images/image3.jpg" height="250" width="150"alt="pictures"></a></li>
      </ul>

    </div>
  </section>
<footer><p>All rights reserved</p></footer>
</div>
<!-- Add jQuery library -->
<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
<!-- Add fancyBox -->
<link rel="stylesheet" href="source/jquery.fancybox.css" type="text/css" media="screen" />
<script type="text/javascript" src="source/jquery.fancybox.pack.js"></script>

<script type="text/javascript">
	$(document).ready(function() {
		$(".fancybox").fancybox();
	});
</script>

</body>
</html>
