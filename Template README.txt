heiarchy of nesting
  container
    content
      item

containers:
body
  main
    header
      content
        item
    mid
      content
        item
    footer
     content
       item

within header: 
  logo
  nav
  log in
  sign up

within main
  side-bar = display content on the side left/right
  side-nav = display vertical nav left/right
  content = blurbs and links to other pages

within footer:
  footer-nav
  social media
  copyright

CSS structure.

* - margin, padding, box-size(as needed), font-family(for majority of text)
body - background-color/image, text color, 
cluster at the top element tages - button, p, h1-h6 and if multi-class selectors have the same style (example = .test, .fun {color: red;})
main-container - styles of the container and width adjustment to create border along the side.
header - styles for the container
any id or classes within header
mid-container - styles
any classes or id within mid-container
side-bar (if one) after mid-container content classes and ids.
footer-container - style
any class or id within footer-container