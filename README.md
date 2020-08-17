# w1-Code-Refactor

## Contents
* HTML - changes made to the HTML
* CSS - changes made to the CSS

## User Story
The client wants to refactor their website to make it meet accessibility standards and for search engine optimisation.

## HTML
* Changed the title to match the marketing agency name.
* Added meta tags for better SEO.
* Removed div with class header and replaced with header element.
* Replaced the div with a nav element to contain the unordered list of the nav bar.
* Replaced the span of class "seo" with an em element to give semantic meaning. Added CSS font-style of normal since the acceptance criteria does not specify to change the font-style and em will usually render italics.
* Replaced the div of class "hero" with an img and added alt text. Removed the CSS background properties for it. Changed in CSS the height to avoid skewing of the image.
* Replaced div of class "content" with a section element.
* All divs in the section of class "content" are changed to articles.
* Added alt text to all imgs.
* Removed the id of "online-reputation-management".
* Removed the id of "social-media-marketing".
* Changed the div of class "benefits" to a section. Changed all divs within this section to articles.
* Replaced the div of class footer with footer element.
* Removed the h2 from the footer and replaced with a p element to keep headings in order.

## CSS
* changed "header h1" to just "h1"
* changed "header h1 em" to just "em"
* changed "header nav" to just "nav"
* changed "header nav ul" to just "ul"
* changed "header nav ul li" to just "li"
* Added text-align: center to .benefits selector.
* Removed .benefit-lead, .benefit-brand and .benefit-cost selectors and replaced with just the .benefits article selector.
* Removed .benefit-lead h3, .benefit-brand h3 and .benefit-cost h3 and replaced with just one h3 selector. Removed text-align since it's in the parent.
* Removed .benefit-lead img, .benefit-brand img and .benefit-cost img and replaced with just one selector named .benefits img
* Replaced .search-engine-optimization, .online-reputation-management and .social-media-marketing selectors and replaced with just one selector named .content article.
* Removed .search-engine-optimization img, .online-reputation-management img and .social-media-marketing img  selectors and replaced with just one named .content article img.
* Replaced .search-engine-optimization h2, .online-reputation-management h2 and .social-media-marketing h2 with just one .content article h2.
* Added .benefits article p selector to align the text to the left.
* Added font-weight to the .bigger-text class to have similarity in look to a heading.
- - -
Beverley Hatzl 2020