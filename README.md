# Code Refactor Starter Code
# horizeon

Expalaination:

We were required to make an html file acsessable for people with vision disabilities and make the code simple for any programer who wants to look at the code.

I did this by changing primary non semantic commands to semantic commands like, "Footer, Article, aside and heading" .

The next step was changing the non semantic elemenmts inside of the primary divs. For this I used "section and nav." 

This makes things easier for sombody looking at the code to piece it together and not just have a bunch of divs.

The next step was to check and see if anything was buggy with the css file. To check this i opened up the HTML file in a preview and saw that the navigation links were pushed to the left side of the header. I then realized this was becuase the "header" had a div instead of a nav. This was a quick fix, I put nav next to the header and everything started functioning fine.

The last thing I did was add descriptions in the code next to the image. This is so when someone who needs the text read to them they will be able to get a description of the image.