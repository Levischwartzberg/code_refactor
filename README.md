# code_refactor

# 01 HTML, CSS, and Git: Code Refactor

## Process

The html was altered without changing the content that the user views. The previous html had mostly div tags organizing the various segments of the document. 

The following steps were taken to improve the html.

1: The div with class "header" was changed to a header tag, and the css style sheet was updated to reflect this.]
2: The two large content areas (classes "content" and "benefits") below the image were changed from divs to section tags.
3: The individual items within the "content" section were changed to the article tag instead of div.
4: The images and corresponding descriptions in the "benefits" section were changed from divs to figure tags.
5: Two of the three article tags had redundant id tags that weren't used for styling, and were therefore removed.
6: A footer tag was used to replace the div tag for the footer.
7: A title (alt replacement for divs) was added to the div with the background image to allow for increased accesibility. 
8: alt descriptions were added to the remaining images.