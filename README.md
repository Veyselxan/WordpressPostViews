# WordpressPostViews
Wordpress Post Views
Add the snippet to functions.php and follow these instruction:

Add this to single.php, and make sure you paste in inside the loop.


<?php setPostViews(get_the_ID()); ?>
Lastly, to display the number of views a post has, just add this where you want it to be displayed:


<?php echo getPostViews(get_the_ID()); ?>
