The div tag is an HTML element used to group and organize other elements together.

    <div> This is some content </div>
    <div>
        This is create a new line
        This content doesn't create a new line
    </div>
    <div>
        <div>Some</div><div>more</div><div>lines</div>
    </div>

The Div tag stands for "division" and is used to divide or group content into logical sections.

it's a block-level element, meaning it takes up the full width of its container and create a line break after it.

It's doesn't have any inherent styling or semantics meaning, and its purpose is mainly to help with layout and organization of content.

It's can be styled using css of control its appearance, such as its size, background color, border and positioning

---

Create a wireframe

    problem Statement:
        Create a web page that show cases job listings for jovian including the following

        A Navbar at the top showing logo
        A Header Section displaying the picture and some relevant information
        A list of job opening that includes the job designation, location and salary details
        A footer at the bottom of the web page with important links

    Make the page visually appealing and informative

Headings:

    Headings are defined using the HTML <h1> to <h6> tags
    h1 is highest level of heading and h6 is lowest level
    Heading should be used in a logical order and accurately describe the content of the page.
    h1 tag should be used for most important heading so on

The p and span tags are both used to define text in HTML:

    The P tag defines a paragraph of text and typically used for longer sections of text that form a distinct block.

    The span tag defines a small section of text and is typically used for inline styling, such as changing the color of single word or phase

Modifier tags, such as b, i, u, strong, em, etc..are used to modify the appearance or meaning of text within HTML:

    The b tag is used to make text bold
    the i tag is used to italicize text.
    The u tag is used to underline text.
    The strong tag is used to indicate that the text is important and should be emphasized.
    The em tag is used to indicate that the text, typically displayed in italics.

Note: Use of modifiers tags like b and i is considered outdated. it is recommended to use CSS styles instead.

    Exercise:
        Use some modifier tags to highlight important keywords in the description below "About Jovian"

Lists:

    An Unordered HTML list:                An ordered  HTML list:
        item                                   1. First item
        Item                                   2. Second item
        Item                                   3. Third item

    special HTML tags are used to create lists, which allow for the presentation of information in an organization and structured manner.

        There are two types of lists in HTML:

            1. Unordered lists:
                create using ul tag
                List items are added using li tag
                Bullet points are used to denote list items
                Appearance of bullet points can be customized with CSS

            2. Ordered lists are created using the <ol> tag.
                Items are numbered or lettered automatically.
                The <li> tag is used for each list item in an ordered list.
                The numbering or lettering style can be customized using the type attribute or CSS.

            Lists can be nested, meaning you can place one list inside another. This works for both unordered and ordered lists, and you can even mix them together. Here’s how nested lists work:

Let's some footer items to our page using ul tag:

    <div>
        <ul>
            <li> Courses </li>
            <li> Programs </li>
            <li> Youtube </li>
        </ul>

        <span>&copy; 2024, Jovain</span>
    </div>

Links:
In HTML, links are created using the <a> (anchor) tag. Links can point to other web pages, sections within the same page, email addresses, or even initiate downloads. Here's a breakdown:

    The a tag must have an href attribute that specifies the URL of the destination page.

    The link that is displayed as the link is placed between the Open and closing a tags.

    You can use target attribute to specify where the lined page should be opened, such as in a new tab or window.

    You can also create links to specific sections of a page by using the id attribute to identify the section and adding it to the URL in the href attribute.

Images:

    The image tag is used to add images to an HTML Page.

    The src attribute of the img tag is used to specify the URL or file path of the image

    The alt Provides a text description of the image. This is displayed if the image fails to load and is also important for accessibility.

    width: Specifies the width of the image in pixels or percentage.

    height: Specifies the height of the image in pixels or percentage.

    Specifies whether the image should load immediately or lazily (when it comes into view).

    lazy: Defers loading until the image is visible.
    eager: Loads immediately.

    The title Provides additional information about the image. This text appears as a tooltip when the user hovers over the image.

Use this url
https://www.htmldog.com

Adding Styles With CSS
