# AJAX-Slideshow

* Using XMLHttpRequest instance, facilitated an AJAX GET request from a server and parsed the JSON from the response text to dynamically populate a select element with various dog breed names as choice/option values.

* Upon selecting a choice of dog breed name, populated the header field with the chosen dog name and facilitated another AJAX GET request from the server by passing the chosen id as a parameter and populated the corresponding dog breed information. 

* Used setTimeout and clearTimeout to construct an image slideshow of 5 dogs running in a cyclic manner at 5 seconds interval each, using vanilla/pure JavaScript without the aid of jQuery, by simply setting the display style of the current image in the iteration to be 'block' and the rest to be none. 
