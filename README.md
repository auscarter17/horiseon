# HORISEON WEB PAGE

Webpage for Horiseon, a digital marketing firm. This website is designed to attract new clients to Horiseon, who is able to help them with the online presence of their business. The objective of the challenge is to refractor the code to make it more accessible.

# CHANGES MADE FOR ACCESSIBILITY STANDARDS

The title for the website was simply 'website' and has been updated to show the business name. 

The gitignore file has been added with .DS_Store as an ignored file.

There were many repeating lines of code, particularly in the stylesheet of the challenge. Such examples as in the benefit sections 'benefit-brand' 'benefit-cost' and 'benefit-lead' as seen in the original index beginning on line 89, and the 'search-engine-optimization' 'online-reputation-management' and 'social-media-marketing' sections on line 137. These were able to share one 'benefits' tag to reduce the amount of redundant code in our stylesheet. 

There were many unnecessary div tags placed where other tags would suffice. The header and footer sections were designated as classes inside of a div as opposed to using their own header and footer tags. This was changed, and the corresponding parts of the stylesheet were changed as to keep the styles that were in place. 

None of the images featured in the file had alt tags for screen-reader function. These have been added to the page.

The navigation for the search engine optimization section at the top of the page did not take the user to that section. Further down in the content section seen on line 30 of the original document shows that we are missing an id that would take the user to this portion of the page, and has been added into the new site. 

The body section of the stylesheet had no font-family, and has been added in to make sure known supported fonts can appear on the page.

The code has been reorganized to be easier to read, in ways such as additional lines between divs, proper tab spacing to bring new pieces forward, and comments added between both the html and the css. 