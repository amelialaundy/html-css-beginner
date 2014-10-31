Step Four: using CSS
=================

Ok so we've got some colours and styles happening on our about_me page, but it's a bit messy with these styles all over the place.

In this step we will create a CSS file to store all of our styles in so that we don't have to litter them through our HMTL file.

#Release One
- Look at the [example CSS file](https://github.com/amelialaundy/html-css-beginner/blob/step_4/example_css.css), the styles are now all stored in here
- Now look at the [example_html file](https://github.com/amelialaundy/html-css-beginner/blob/step_4/html_example.html) and see how all the style attributes have been removed
- In the head tag we now have a link tag, the href attribute tells the HTML where to find the CSS document, the rel attribute tells the HTML the relationship between itself and the document being linked and the type tells it the media type of the link

#Release Two
- Create a file called styles.css
- Add a link tag to your header in your about_me file, in the href attribute you will want to put 'styles.css'
- Using the styles you added into your about_me with the style attribute, add them into your styles.css file
- Once you think you have added them all, remove all the style attributes from you about_me file- a quick way to do this in sublime in to use cmd + f and type in the word style, this will let you delete all the style attributes
- Open you about_me in Chrome to see if it has worked!
- Now you should notice that for example instead of having to write style='some style name: style value' on every h2 tag, you can write it once in your css and it will apply it to all the h2 tags