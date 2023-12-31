# ADVANCED HTML

## This folder contains answers to tasks on the following topics

- Guidelines to follow for HTML
- Creating a skeleton of an HTML5 page
- Using semantic HTML tags to structure a web page
- Use cases to use __div__ vs __span__
- Semantic values of __header, main, footer, article, nav, section, aside__
- Using headings and the importance of heirarchical order
- HTML lists
- Difference between medias (SVG. GIF, PNG, JPG)
- Structuring data in a table
- Integrating  video in a webpage
- Integrating audio file in a webpage
- Embedding external content
- Correctly structuring a HTML page

## Here are the questions.
0. Create your first HTML file 0-index.html with:

	- Add the doctype on the first line (without any comment)
	- After the doctype, open and close a _html_ tag
	- Add the language tag, specify English for __ISO language code__ and add the direction tag (ltr or rtl) on the _html_ tag.
	- Open your file in your browser (the page should be blank)
__W3C won’t pass - you can ignore it__

1. Copy the content of 0-index.html into 1-index.html

__Create the head and body sections__

	- inside the _html_ tag, create the _head_ and _body_ tags (empty) in this order
__W3C won’t pass - you can ignore it__

2. Copy the content of 1-index.html into 2-index.html

__Meta charset:__

	- add a _meta_ tag inside the _head_:
		- add the _charset_ attribute with the value _utf-8_
__Viewport:__

	- add a _meta_ tag inside the _head_:
		- add an attribute _name_ on the tag and specify that it is the meta _viewport_
		- add the key _width_ with the value _device-width_
		- add the key _initial-scale_ with the value _1.0_
		- add the key _viewport-fit_ with the value _cover_
__Title:__

	- add the _title_ tag just after the meta viewport with value: _Homepage - Techium_

__Description:__

	- add a _meta_ tag inside the head section
		- add an attribute _name_ on the tag and specify that is the meta _description_
		- add another attribute called _content_
		- add the following description: _Techium is a digital agency_
__Favicons:__

	- download the image above to use as a favicon
	- Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
	- take the _favicon.ico_ and _favicon.png_ and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
	- inside the _head_, create 2 _link_ tags with these 3 attributes: __rel, type,__ and __href__.
		- the first _link_ tag:
			- rel: _icon_
			- type: _image/x-icon_
			- href: _./favicon.ico_
		- the second _link_ tag:
			- rel: _icon_
			- type: _image/png_
			- href: _./favicon.png_

3. Copy the content of 2-index.html into 3-index.html

__Header:__

	- create the _header_ of your page between the open and close _body_ tag
	- put the text _Header_ inside the header
Main:

	- create the _main_ tag after the _header_ tag
		- put the text _Main content_ inside your _main_ tags
Footer:

	- create the _footer_ tag after the _main_ tag
		-put the text _Footer_ inside the _footer_ tags

4. Copy the contents of 3-index.html into article.html

	- change the _\<title\>_ to put: _Article - Techium_
	- inside the _main_ tags
		- after the text, create the _aside_ tags with text _Aside_

5. Copy the content of 3-index.html into 5-index.html

	- inside your _\<main\>_ section
		- remove the text in _main_, create these sections:
			1. create first section and put the text _Hero section_ inside
			2. create second section and put the text _Services section_ inside
			3. create third section and put the text _Works section_ inside
			4. create fourth section and put the text _About section_ inside
			5. create fifth section and put the text _Latest news section_ inside
			6. create sixth section and put the text _Testimonials section_ inside
			7. create seventh section and put the text _Contact section_ inside
__Does not need to pass W3C__

6. Copy the content of 5-index.html into 6-index.html

__Work articles:__

	- inside the section _Works section_
		- add 3 _article_ tags
			- inside each _article_ write _Work \#_ where the hashtag will be the ordered number (1, 2, or 3)
__News articles:__

	- inside the section _Latest news section_
		- add 3 _article_ tags
			- inside each _article_ write _Article \#_ where the hashtag will be the ordered number (1, 2, or 3)
__Testimonial articles:__

	- inside the section _Testimonials section_
		- add 3 _article_ tags
			- inside each _article_ write _Testimonial \#_ where the hashtag will be the ordered number (1, 2, or 3)
__W3C won’t pass - you can ignore it__

7. Copy the content of 6-index.html into 7-index.html

	- remove the _Header_ text inside the _\<header\>_
	- create the _nav_ tag inside the _header_ tag
		- it should remain empty for now
__Does not need to pass W3C__

8. Copy the content of 7-index.html into 8-index.html

	- create the level 1 heading inside your _main_ before your sections
		- put text _Homepage_ in your heading tag
__Does not need to pass W3C__

9. Copy the content of 8-index.html into 9-index.html

	- in the _section_ tag with the the text _Hero section_, remove the text and create a level 2 heading with text _We help you build your brand!_
	- in the _section_ tag with the the text _Services section_, remove the text and create a level 2 heading with text _Services_
	- in the _section_ tag with the the text _Works section_, remove the text and create a level 2 heading with text _Works_
	- in the _section_ tag with the the text _About section_, remove the text and create a level 2 heading with text _About Us_
	- in the _section_ tag with the the text _Latest news section_, remove the text and create a level 2 heading with text _Latest news_
	- in the _section_ tag with the the text _Testimonials section_, remove the text and create a level 2 heading with text _Testimonials_
	- in the _section_ tag with the the text _Contact section_, remove the text and create a level 2 heading with text _Contact_
__W3C won’t pass - you can ignore it__

10. Copy the content of 9-index.html into 10-index.html

__Services headings:__

	- Inside the section containing the _h2_ heading _Services_, add these elements right after the h2:
		- create a level 3 heading with text _Design & Concept_
		- create a level 3 heading with text _Digital Strategy_
		- create a level 3 heading with text _Content Strategy_
		- create a level 3 heading with text _UX Design_
		- create a level 3 heading with text _Web Development_
		- create a level 3 heading with text _Social Media_
__Works headings:__

	- Inside the section containing the _h2_ heading _Works_:
		- in the first _article_, replace the text with a level 3 heading with text _Interior Design_
		- in the second _article_, replace the text with a level 3 heading with text _Web Development_
		- in the third _article_, replace the text with a level 3 heading with text _Personal Brand_
__About Us headings:__

	- Inside the section containing the _h2_ heading _About Us_, after the _h2_ heading, create these elements in this order:
		- a level 3 heading with text _Who are we_
		- a level 3 heading with text _Our culture_
		- a level 3 heading with text _How we work_
__Latest news headings:__

	- Inside the section containing the _h2_ heading _Latest news_:
		- in the first _article_ replace the text with a level 3 heading with text _Hoc loco tenere se Triarius non potuit_.
		- in the second _article_ replace the text with a level 3 heading with text _Ut alios omittam, hunc appello, quem ille unum secutus est_.
		- in the third _article_ replace the text with a level 3 heading with text _Bestiarum vero nullum iudicium puto_.
__W3C does not need to pass here__

11. Copy the content of 3-index.html into 11-styleguide.html

	- change the title to Styleguide - Techium
	- remove the text from header, main, and footer
	- create a new <section> inside your main tag
		- create a header in this section
			- in the header add a level 2 heading with text Headings
		- after the header:
			- add a level 1 heading with text Heading level 1
			- add a level 2 heading with text Heading level 2
			- add a level 3 heading with text Heading level 3
			- add a level 4 heading with text Heading level 4
			- add a level 5 heading with text Heading level 5
			- add a level 6 heading with text Heading level 6

12. Copy the content of 10-index.html into 12-index.html

About Us paragraphs:

	- in the About Us section
		- after the first h3 (who are we) create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
		- after the second h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
		- after the third h3 create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!
Latest news paragraphs:

	- in the Latest news section
		- in the first article
			- create a paragraph with text Career before the heading
			- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane? after the heading
		- in the second article
			- create a paragraph with text Digital Life before the heading
			- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama? after the heading
		- in the third article
			- create a paragraph with text Social before the heading
			- create a paragraph with text Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones. after the heading
Contact paragraph:

	- in the Contact section after the heading
		- create a paragraph with the text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?
Additional paragraphs:

	- below the level 2 Services heading add a paragraph with text We work with you
	- below the level 2 Works heading add a paragraph with text Take a look in our portfolio
	- below the level 2 About Us heading add a paragraph with text Everything about us
	- below the level 2 Testimonials heading add a paragraph with text We are more than a digital company
	- below the level 2 Contact heading add a paragraph with text We like to know new people
__Does not need to pass W3C__

13. Copy the contents of 11-styleguide.html into 13-styleguide.html

	- After the existing section containing Headings, create a new section in main
		- in this section create a header
			- Inside the header, create a level 2 heading with text Paragraph
		- after the header add a level 2 heading with text Heading with a subtitle
		- after the level 2 heading, add a paragraph with text This is my subtitle
		- after the last paragraph, add another paragraph with text: Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.

14. Copy the contents of 12-index.html into 14-index.html

In the very first <header>,

	- before the nav, create a span with the text Techium
__Does not need to pass W3C__

15. Copy the contents of 14-index.html into 15-index.html

	- Wrap the contents of the header element with a div
	- Wrap the contents of all section elements with a div
	- Finally, wrap the contents of the <footer> tag with a div
__W3C does not need to pass__

16. Copy the contents of 15-index.html into 16-index.html

	- in the div in the Services section
		- create a header tag that wraps the h2 and the p
		- create a div sibling to the header that wraps the rest of the content
	- in the div in the Works section
		- create a header tag that wraps the h2 and the p
		- create a div sibling to the header that wraps the rest of the content
	- in the div in the About Us section
		- create a header tag that wraps the h2 and the p
		- create a div sibling to the header that wraps the rest of the content
	- in the div in the Latest news section
		- create a header tag that wraps the h2
		- create a div sibling to the header that wraps the rest of the content
	- in the div in the Testimonials section
		- create a header tag that wraps the h2 and the p
		- create a div sibling to the header that wraps the rest of the content
	- in the div in the Contact section
		- create a header tag that wraps the h2 and the first p
		- create a div sibling to the header that wraps the rest of the content
__W3C does not need to pass__

17. Copy the content of 16-index.html into 17-index.html

	- before the header add a line break and a comment saying Header to help with scanning your code
	- before the main add a line break and a comment saying Main to help with scanning your code
	- before the footer add a line break and a comment saying Footer to help with scanning your code
	- before the Hero section add a line break and a comment saying Hero section
	- before the Services section add a line break and a comment saying Services section
	- before the Works section add a line break and a comment saying Works section
	- before the About Us section add a line break and a comment saying About Us section
	- before the Latest news section add a line break and a comment saying Latest news section
	- before the Testimonials section add a line break and a comment saying Testimonials section
	- before the Contact section add a line break and a comment saying Contact section
__Does not need to pass W3C__

18. Copy the content of 17-index.html into 18-index.html

	- in the header, wrap the span with a link that redirects to the page at the root of your folder (/)
	- wrap the link with a div
__W3C does not need to pass__

19. Copy the content of 18-index.html into about.html, latest_news.html and contact.html

	- change the title of about.html to replace Homepage with About
	- change the title of latest_news.html to replace Homepage with Latest news
	- change the title of contact.html to replace Homepage with Contact
__Does not need to pass W3C_

20. Copy the content of 18-index.html into 20-index.html

	- in your nav tags
		- create a link to / with the text Home
		- create an anchor to services with the text Services
		- create an anchor to works with the text Works
		- create an anchor to about with the text About
		- create an anchor to latest_news with the text Latest news
		- create an anchor to testimonials with the text Testimonials
		- create an anchor to contact with the text Contact
For now, the anchor links will not work. We will make them work in the CSS project.

__Does not need to pass W3C__

21. Copy the content of 20-index.html into 21-index.html

	- in the div in the footer
		- remove any text you have
		- create a link to https://www.facebook.com/HolbertonSchool/ with the text Facebook
		- create a link to https://twitter.com/holbertonschool with the text Twitter
		- create a link to https://www.instagram.com/holbertonschool/ with the text Instagram
__W3C won’t pass - you can ignore it__

22. Copy the content of 21-index.html into 22-index.html

	- in the Hero section, after the heading
		- create a link to # with the text Get started
	- in the About Us section, after the div containing the level 3 headings and paragraphs
		- create a link to about.html with the text Learn more about us
	- in the Contact section, after the div containing the paragraph
		- create a link to contact.html with text Get in touch
__Does not need to pass W3C__

23. Copy the content of 22-index.html into 23-index.html

	- in the Services section
		- in each level 3 heading, create a link to # around the text already in the heading
	- in the Works section
		- in each level 3 heading, create a link to # around the text already in the heading
	- in the Latest news section
		- in each level 3 heading, create a link to # around the text already in the heading
__Does not need to pass W3C__

24. Copy the content of 23-index.html into 24-index.html

	- in the nav
		- create an unordered list, put each anchor tag (Home, Services, Works, …) as an individual list item
	- in the div in the footer
		- create an unordered list and put each anchor tag (Facebook, Twitter, …) as an individual list item
__W3C does not need to pass__

25. Copy the content of 24-index.html into 25-index.html

	- inside the footer, after the div
		- create a new div
		- in the new div create an unordered list with the following links:
			1. link to # with text Terms of Use
			2. link to # with text Privacy Policy
			3. link to # with text Cookie Policy

26. Copy the content of 13-styleguide.html into 26-styleguide.html

Example of unordered list:

	- inside main after Paragraph section, add :
		- a new line and a comment with text Lists
		- after, create a new section with inside:
			- create a header with inside a level 2 heading with the text Lists
			- after the new header, create a div with inside:
				- a level 3 heading with text Unordered
					- under it, add an unordered list with these items: Dolor pulvinar etiam magna etiam., Sagittis adipiscing lorem eleifend., Felis enim feugiat dolore viverra.
Example of ordered list:

	- after previous unordered list, in the same div
		- add a level 3 heading with text Ordered
			- add an ordered list with these items:
				1. Dolor pulvinar etiam magna etiam.
				2. Sagittis adipiscing lorem eleifend.
				3. Felis enim feugiat dolore viverra.
Example of definition list:

	- after previous ordered list, in the same div
		- add a heading level 3 with text Definition
		- add a definition list with these items:
			1. Term: Definition List title, Definition: Definition text.
			2. Term: Startup, Definition: A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.
			3. Term: Water, Definition: A colorless, transparent, odorless liquid that forms the seas, lakes, rivers, and rain and is the basis of the fluids of living organisms.

27. Copy the content of 25-index.html into 27-index.html

	- in the footer between the two divs:
		- add a horizontal rule
		- after the horizontal rule add a paragraph with text © 2020 Techium, made with ♥ by students at Holberton School.
__W3C does not need to pass.__

28. Copy the content of 26-styleguide.html into 28-styleguide.html

	- in main after Lists section
		- add a new line and a comment with the text Horizontal rule
		- create a new section
			- create a header and inside it add a level 2 heading with the text Horizontal rule
			- after the header create a div and put a horizontal rule in it

29. Copy the content of 27-index.html into 29-index.html

	- in the Testimonials section
		- in the first article
			- replace the text with a blockquote with text I am completely blown away. Thanks to Techium, we've just launched our 5th website! and cite author Yuri Y.
		- in the second article
			- replace the text with a blockquote with text Thank you so much for your help. Techium company is awesome! and cite author Dorrie S.
		- in the third article
			- replace the text with a blockquote with text I love your system. Definitely worth the investment. I'd be lost without Techium company. and cite author Sven H.
__W3C does not need to pass__

30. Copy the content of 28-styleguide.html into 30-styleguide.html

Example of inline quote:

	- inside main after Horizontal rule section
		- add a new line and a comment with text Blockquotes
		- create a new section
			- in the section create a header, in the header create a level 2 heading with text Blockquotes
			- after the header, create a div
				- in the div add a level 3 heading with the text Inline quote
				- add an inline quote with the text Stay hungry. Stay foolish.
Example of blockquote:

	- after the inline quote div, create another div
		- in the new div add a level 3 heading with the text Blockquote
		- add a multiline quote with the text I will be the leader of a company that ends up being worth billions of dollars, because I got the answers. I understand culture. I am the nucleus. I think that’s a responsibility that I have, to push possibilities, to show people, this is the level that things could be at. and cite Kanye West, Musician

31. Copy the content of 29-index.html into 31-index.html

	- in the footer
		- right after open footer tag, put the following address: 234 Washington Street (line-break) Urbana, Illinois
	- in the Latest news section
		- in the first article, after the last paragraph, add the author name in small print: By Kelly D.
		- in the second article, after the last paragraph, add the author name in small print: By William A.
		- in the third article, after the last paragraph, add the author name in small print: By Frances J.
__W3C does not need to pass__

32. Copy the content of 30-styleguide.html into 32-styleguide.html

	- inside main after the Blockquotes section

		- add a new line and a comment with text Typography
		- create a new section

			- in the section create a header and inside it add a level 2 heading with the text Typography
			- after the header create a div, inside the div add this text with the correct HTML tag: 320 Stewart Avenue, Unit 12 (line break) New York City NY 10001, the city, state, and postal code should be on a separate line
			- create another div, in the new div nest this code block using the pre HTML tag:
```html 
<code>
     <h2>My title</h2>
     <p>Proin lacus turpis, feugiat sit amet sollicitudin non, volutpat in libero. Aenean hendrerit ultrices nulla ac lobortis. Vestibulum consectetur nibh vel ante rhoncus faucibus.</p>
 </code>
```
			- create another div, in the new div add this paragraph of text with the correct HTML tag: Curabitur sit amet turpis cursus massa mollis highlighted. Duis finibus leo massa, eget dapibus erat finibus sed. Aenean condimentum sapien magna, eleifend highlighted mi consequat ut. Cras nec quam sed sapien ultricies highlighted ut sed metus. Each occurrence of the word highlighted should be highlighted.
__W3C does not need to pass__

33. Copy the content of 32-styleguide.html into 33-styleguide.html

	- inside main after Typography section
		- add a new line and a comment with text Table
		- create a new section
			- in the section create a header, in the header add a level 2 heading with the text Table
			- after the header, create a table, reproduce in HTML

The <th> tags containing Title, Director, Release Date should have a scope attribute set to col The <th> tags containing the names of the movies should have a scope attribute set to row

__Due to previous task, does not have to pass W3C__

34. Copy the content of 33-styleguide.html into 34-styleguide.html

	- in main tag after Table section
		- add a new line and a comment with text Details
		- create a new section
			- create a header, in the header add a level 2 heading with the text Details
			- after the header create a div
				- in the div add a level 3 heading with text Default
				- add a details element and specify Show/Hide me in the summary
				- add this text after the summary: Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
			- create another div
				- add a level 3 heading with text Open
				- add a details element that is open by default and specify Always open in the summary
				- add this text after the summary: Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
__Due to earlier task, does not have to pass W3C__

35. Copy the content of 31-index.html into 35-index.html

	- in header
		- find the span with the name of the website
		- replace it with the image above
		- make sure the image is in the same directory as all of your other files and that the file name is logo-black.png
		- alt: Techium logo
		- don’t forget to specify width of 160 and height of 40
	- in footer, after the opening tag and before the address
		- insert the logo image
		- alt: Techium logo
		- don’t forget to specify the width and height (same as in header)
__W3C does not need to pass__

36. Copy the content of 35-index.html into 36-index.html

You can use image generators to get images for this task. For avatar images you can download them on UI Faces. Just make sure you rename your images to match the task requirements.

__Add three images in the Works section:__

	- in the Works section
		- before the first level 3 heading create a div
			- add images/pic-work-01.jpg inside the div
			- alt: empty
		- before the second level 3 heading create a div
			- add images/pic-work-02.jpg inside the div
			- alt: empty
		- before the third level 3 heading create a div
			- add images/pic-work-03.jpg inside the div
			- alt: empty
__Add one image in the About Us section:__

	- in the About Us section before the first level 3 heading inside the div
		- add the image images/pic-about-us.jpg
			- alt: empty
			- width: 460
			- height: 447
__Add three images in the Latest news section:__

	- in the Latest news section
		- in the first article, before the first paragraph, create a div
			- in the div add the image images/pic-blog-01.jpg
			- alt: empty
			- width: 305
			- height: 205
		- in the second article, before the first paragraph, create a div
			- in the div add the image images/pic-blog-02.jpg
			- alt: empty
			- width: 305
			- height: 205
		- in the third article, before the first paragraph, create a div
			- in the div add the image images/pic-blog-03.jpg
			- alt: empty
			- width: 305
			- height: 205
__Add three images in the Testimonials section:__

	- in the Testimonials section
		- in the first article before the quote, add the image images/pic-person-01.jpg
			- alt: Yuri Y. avatar
			- width: 100px
			- height: 100px
		- in the second article before the quote, add the image images/pic-person-02.jpg
			- alt: Dorrie S. avatar
			- width: 100px
			- height: 100px
		- in the third article before the quote, add the image images/pic-person-03.jpg
			- alt: Sven H. avatar
			- width: 100px
			- height: 100px
__Does not need to pass W3C__

37. Copy the content of 36-index.html into index.html (the final file!)

	- inside the footer

		- replace the text Facebook with the SVG icon code and add width of 25px and height of 25px to the SVG tag:
```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<title>
Facebook icon
</title>
<path d="M23.998 12c0-6.628-5.372-12-11.999-12C5.372 0 0 5.372 0 12c0 5.988 4.388 10.952 10.124 11.852v-8.384H7.078v-3.469h3.046V9.356c0-3.008 1.792-4.669 4.532-4.669 1.313 0 2.686.234 2.686.234v2.953H15.83c-1.49 0-1.955.925-1.955 1.874V12h3.328l-.532 3.469h-2.796v8.384c5.736-.9 10.124-5.864 10.124-11.853z"/>
</svg>
```
		- replace the text Twitter with the SVG icon code and add width of 25px and height of 25px to the SVG tag:
```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<title>
Twitter icon
</title>
<path d="M23.954 4.569a10 10 0 0 1-2.825.775 4.958 4.958 0 0 0 2.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 0 0-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 0 0-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 0 1-2.228-.616v.061a4.923 4.923 0 0 0 3.946 4.827 4.996 4.996 0 0 1-2.212.085 4.937 4.937 0 0 0 4.604 3.417 9.868 9.868 0 0 1-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 0 0 7.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 0 0 2.46-2.548l-.047-.02z"/>
</svg>
```

		- replace the text Instagram with the SVG icon code and add width of 25px and height of 25px to the SVG tag:
```html
<svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<title>
Instagram icon
</title>
<path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384 5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382 3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899 3.644 3.644 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324 6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0 1.44 1.44 0 0 1 2.88 0z"/>
</svg>
```
__W3C does not need to pass__

38. Copy the content of 34-styleguide.html into 38-styleguide.html

	- in main after the Details section
		- add a new line and a comment with text Video
		- create a section
			- in the section create a header, in the header add a level 2 heading with the text Video
			- after the header add the following video: https://intranet-projects-files.s3.amazonaws.com/webstack/BigBuckBunny.mp4
			- add controls to the video
			- ensure that the video does a loop
			- display https://intranet-projects-files.s3.amazonaws.com/webstack/thumbnail.jpg when the video is downloading
			- provide an alternative text: Sorry, your browser doesn't support HTML5 video
__Due to an earlier task, does not need to pass W3C__

39. Copy the content of 38-styleguide.html into 39-styleguide.html

	- in main after Video section
		- add a new line and a comment with text Audio
		- create a section
			- in the section create a header, in the header add a level 2 heading with the text Audio
			- after the header add the following audio file: https://intranet-projects-files.s3.amazonaws.com/webstack/TroubleChapter8_64kb.mp3
			- add controls to the audio player
			- provide an alternative text: Sorry, your browser doesn't support audio element
__Due to an earlier task, does not need to pass W3C__

40. Copy the content of 39-styleguide.html into styleguide.html

	- in main after the Audio section
		- add a new line and a comment with text Iframe
		- create a section
			- in the section create a header, in the header add a level 2 heading with the text Iframe
			- after the header add a div
				- inside the div, create an iframe
					- title: Holberton School
					- width: 350px
					- height: 200px
					- source: https://www.youtube.com/embed/41N6bKO-NVI
					- fallback text: Holberton Sally
__W3C does not need to pass__

###And you I am done!

The code is W3C compliant as it is validated using W3C-Validator.
