0x01. AirBnB clone - Web static

Background Context Web static, what? Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:

Create simple HTML static pages Style guide Fake contents No Javascript No data loaded from anything During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Before starting, please fork or clone the repository AirBnB_clone from your partner if you were not the owner of the previous project.

Resources Read or watch:

Learn to Code HTML & CSS (until “Creating Lists” included) Inline Styles in HTML Specifics on CSS Specificity CSS SpeciFishity Introduction to HTML CSS MDN center boxes Learning Objectives At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General What is HTML How to create an HTML page What is a markup language What is the DOM What is an element / tag What is an attribute How does the browser load a webpage What is CSS How to add style to an element What is a class What is a selector How to compute CSS Specificity Value What are Box properties in CSS Copyright - Plagiarism You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives. You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work. You are not allowed to publish any content of this project. Any form of plagiarism is strictly forbidden and will result in removal from the program. Requirements General Allowed editors: vi, vim, emacs All your files should end with a new line A README.md file, at the root of the folder of the project, is mandatory Your code should be W3C compliant and validate with W3C-Validator All your CSS files should be in styles folder All your images should be in images folder You are not allowed to use !important and id (#... in the CSS file) You are not allowed to use tags img, embed and iframe You are not allowed to use Javascript Current screenshots have been done on Chrome 56 or more. No cross browsers You have to follow all requirements but some margin/padding are missing - you should try to fit as much as you can to screenshots

Tasks 0. Inline styling mandatory Write an HTML page that displays a header and a footer.

Layout:

Body: no margin no padding Header: color #FF0000 (red) height: 70px width: 100% Footer: color #00FF00 (green) height: 60px width: 100% text Best School center vertically and horizontally always at the bottom at the page Requirements:

You must use the header and footer tags You are not allowed to import any files You are not allowed to use the style tag in the head tag Use inline styling for all your tags

Head styling mandatory Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)
Requirements:

You must use the header and footer tags You are not allowed to import any files No inline styling You must use the style tag in the head tag The layout must be exactly the same as 0-index.html

CSS files mandatory Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)
Requirements:

You must use the header and footer tags No inline styling You must have 3 CSS files: styles/2-common.css: for global style (i.e. the body style) styles/2-header.css: for header style styles/2-footer.css: for footer style The layout must be exactly the same as 1-index.html

Zoning done! mandatory Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)
Layout:

Common: no margin no padding font color: #484848 font size: 14px font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif; icon in the browser tab Header: color: white height: 70px width: 100% border bottom 1px #CCCCCC logo align on left and center vertically (20px space at the left) Footer: color white height: 60px width: 100% border top 1px #CCCCCC text Best School center vertically and horizontally always at the bottom at the page Requirements:

No inline style You are not allowed to use the img tag You are not allowed to use the style tag in the head tag All images must be stored in the images folder You must have 3 CSS files: styles/3-common.css: for the global style (i.e body style) styles/3-header.css: for the header style styles/3-footer.css: for the footer style

Search! mandatory Write an HTML page that displays a header, footer and a filters box with a search button.
Layout: (based on 3-index.html)

Container: between header and footer tags, add a div: classname: container max width 1000px margin top and bottom 30px - it should be 30px under the bottom of the header (screenshot) center horizontally Filter section: tag section classname filters inside the .container color white height: 70px width: 100% of the container border 1px #DDDDDD with radius 4px Button search: tag button text Search font size: 18px inside the section filters background color #FF5A5F text color #FFFFFF height: 48px width: 20% of the section filters no borders border radius: 4px center vertically and at 30px of the right border change opacity to 90% when the mouse is on the button Requirements:

You must use: header, footer, section, button tags No inline style You are not allowed to use the img tag You are not allowed to use the style tag in the head tag All images must be stored in the images folder You must have 4 CSS files: styles/4-common.css: for the global style (body and .container styles) styles/3-header.css: for the header style styles/3-footer.css: for the footer style styles/4-filters.css: for the filters style 4-index.html won’t be W3C valid, don’t worry, it’s temporary

More filters mandatory Write an HTML page that displays a header, footer and a filters box.
Layout: (based on 4-index.html)

Locations and Amenities filters: tag: div classname: locations for location tag and amenities for the other inside the section filters (same level as the button Search) height: 100% of the section filters width: 25% of the section filters border right #DDDDDD 1px only for the first left filter contains a title: tag: h3 font weight: 600 text States or Amenities contains a subtitle: tag: h4 font weight: 400 font size: 14px text with fake contents Requirements:

You must use: header, footer, section, button, h3, h4 tags No inline style You are not allowed to use the img tag You are not allowed to use the style tag in the head tag All images must be stored in the images folder You must have 4 CSS files: styles/4-common.css: for the global style (body and .container styles) styles/3-header.css: for the header style styles/3-footer.css: for the footer style styles/5-filters.css: for the filters style