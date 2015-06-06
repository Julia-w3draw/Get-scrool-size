# Get-scrool-size


I created an element with scroll and appended invisible to the body. This way I can get the real size.

This snippet is used in a production environment as part of an object that collects relevant data before any JS code is executed. Each programmer find relevant a different set of information, this one can be used in two ways: getting the scroll size for pixel precision design or (!) as a very simple mechanism for detecting the presence of scroll when element's width/height are known.

