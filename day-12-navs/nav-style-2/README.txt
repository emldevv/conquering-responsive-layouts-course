Style 1 - ".nav__item--push-right". Useful for wordpress developers
    The first method of styling the nav requires a distinct class on one of the elements to separate them. It takes advantage of margin: auto; properties. In margin: auto; both margin-left and margin-right are centring the contents. If you just use margin-left, then only the margin to the left of the content pushes it all the way to the right. Vice-versa for margin-right.

    This element has a distinct tag (.nav__item--push-right) and is assigned the property of margin-left: auto;, thus pushing it right.

Style 2 - creating a new ul. Useful for custom developers.
    This works if you are able to edit the html. A new ul is created and positioned seperately.
    If you are going to use multiple nav elements in your html, you may want to consider the area role of each nav, and make one a "primary nav" and the other "secondary nav". This isn't an ideal way to do it, but it is a way.
