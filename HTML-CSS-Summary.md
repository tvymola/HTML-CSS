# Summary of HTML and CSS Podcasts

## HTML and CSS

For web development, it is extremely important for developers to understand the fundamentals of HTML and CSS. Many seasoned developers will use the __Angular framework__ to build web pages which is perfectly fine. However, when something breaks or goes wrong, having the base HTML and CSS fundamental knowledge will give you the ability to debug the application and fix the code. The entire web is written using HTML and CSS. Knowing what each of the elements are and what they are used for will give you a better perspective for troubleshooting code.

### Accessibility

Good developers will also have knowledge that takes into consideration all of the best practices for making web sites and content accessible for everyone. Accessibility elements are used to enable those with disabilities to have additional context to assist with using web sites.

### Best Practices

The podcast went into detail on some best practices when writing HTML, an example is the 'id' element. The 'id' element should be a unique thing and only be applied to a single item on the page. For example, an 'id' can be used to link the reader to a specific location on the page.

__HTML Forms__ is another fundamental skill that developers should be well versed in. They need to design a form that is well structured and that takes into account Accessibility for all users of the content.

__CSS Specificity__ is a term that describes an algorithm that performs calculations to determine the order in which CSS components are applied to your elements. Different selectors have different levels of specificity, based on a weighted system.

__Important tag__ is a selector that is used to override the default CSS. It shouldn't be used for anything global because they can cause issues down the line.

__Selectors__ are patterns used for targeting specific elements to apply styling. Several examples of a selector would be class, id, element, descendant, direct descendant, attribute, and disabled.

__Layouts__ are used for positioning content on a page. Historically, web designers and developers had to utilize floats and tables to manage the layout of their content. Now we have useful options such as Flexbox and Grid for better managing the layout of a web site.

__Box model__ refers to one of the most important parts of CSS. Everything follows the pattern of a box in regards to spacing, padding, margins, borders and how they affect the shape of the box. It all relates to positioning.

__Border-box__ is used to include padding and border in the element's total width and height.

The __Position__ property specifies the type of positioning method used for an element. Understanding positioning and its parent is important. There are 5 different position values that can be used:

* static
* relative
* fixed
* absolute
* sticky

__Forms and Inputs__ the podcast mentioned that we should be aware that they have default CSS styling that need to be respected, but can also be overridden. The challenges can be when performing alignment inside of forms. Developers need to verify that their inputs look the same in different browsers. The Fieldset tag is often underused, but can be used for grouping groups of Inputs. Fieldset can be also be used for disabling items.

An __inline element__ uses the display tag and refers to an element that has floating content on its left or right side.

A __block element__ actually fills the entire line or space. Content cannot be displayed on its left or right side.

A __inline-block element__ allows us to set width and height on an element. The top and bottom margins and paddings are respected. Compared to the _block_ element, inline-block does not add a line break after the element. This allows for the element to be placed next to other elements.

__Pixel vs. rem vs. em__ is a positioned based upon something else. Knowing how these work is important for foundational learning and developers should know why each is used. Pixel (px) is fixed and absolute, it does not change with the parent or root element. Em is relative to the parent element, changing with the font-size of the nearest parent. Rem is relative to the root element, changing with the font-size of the html element or the browser's default font-size.

__Typography__ basics are knowing about collapsing margins where adjacent siblings if they collide they will collapse into a largest possible margin. We should understand how margins and line height work, and how they work together. This means sizing your headings and your font stack appropriately.

__Media queries__ are a popular technique used for delivering a tailored style sheet to different devices and screen sizes. The maximum width in pixels is set, then styling is applied to the screen based on the width of the device being used in pixels.

## Summary of the 5 Newest CSS Features

__Microsyntax__ refers to the brief text values that we use to indicate a specific meaning. Examples of microsyntax are the @ symbol to refer to a name or the # sign to specify a hashtag. This is something that I've been using for many years and I never had known the name of before.

The __nth child__ is a pseudo class selector that selects child elements based on their position amongst the sibling elements. Microsyntax is used to gain control over the elements that you wish to select. This feature is brand new to me and although I understand how it works, I haven't put it to use just yet.



