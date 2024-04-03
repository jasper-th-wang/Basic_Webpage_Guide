# Adding your information as HTML

This section will show you how to add content to your webpage using HTML. You will add new elements, nest elements inside each other, and even add clickable links! When you’re done, your website will look like this: [image of unstyled website]

## Reverting your changes

In the last section, you added red hello world text to ensure that your CSS file is properly linked to your HTML file. We will remove this as it isn’t needed anymore.

1. Delete the "Hello, world!" texts inside the `body` tag in `index.html`

2. Delete the contents inside the `style.css` file

## Building your website

You now have a blank slate to start adding your content! At any point during these steps, feel free to refresh your web page and see your changes.

1. Open index.html if you’re not there already

2. Copy the following `<h1>` code snippet and paste it in between the `body` tags

    ??? abstract "Code Snippet"
         ```html
         <h1>###</h1>
         ```
    !!! note "The `<h1>` Tag in HTML"
        The `<h1>` tag defines the most important _heading_ in an HTML document. Headings are hierarchical, and the `<h1>` represents the highest level of headings, typically used for the main title or headline of a page. It renders text in a bold and larger font size by default, helping to structure content and improve accessibility and SEO.
   
3. Replace the `###` inside the `<h1>` tag with a interesting title for your website:

    ```html title="Example"
    <h1>Jasper's and Daylen's Webpage</h1>
    ```

4. Copy the following `<p>` code snippet and paste it below the `<h1>` tag

    ??? abstract "Code Snippet"
         ```html
         <p>###</p>
         ```
    !!! note "The `<p>` Tag in HTML"
        The `<p>` tag defines a _paragraph_ of text in an HTML document. It creates a new line before and after the content, making it suitable for long-form text, such as articles, blog posts, and descriptions. By default, it renders text in a normal font size and weight, providing a clear visual separation from other content.
   
5. Replace the `###` inside the `<p>` tag with a short introduction of yourself or your website:

    ```html title="Example"
    <p>We are CST students who love making websites using HTML and CSS.</p>
    ```

6. Copy the following `<ul>` code snippet and paste it below the `<p>` tag

    ??? abstract "Code Snippet"
         ```html
         <ul>
           <li>###</li>
           <li>###</li>
           <li>###</li>
         </ul>
         ```
    !!! note "The `<ul>` and `<li>` Tag in HTML"
        The `<ul>` tag defines an _unordered list_ in an HTML document. It creates a bulleted list of items, typically used for navigation menus, feature lists, and other collections of related content. Each _list item_ is defined by the `<li>` tag, which renders content as a bullet point by default.
   
7. Replace the `###` inside the _first two_ `<li></li>` tags with three interesting facts about yourself or your website:

    ```html title="Example"
    <ul>
        <li>Our favorite snacks: potato chips</li>
        <li>Our favorite music genre: country</li>
        <li>###</li>
    </ul>
    ```

8. Copy the following `<a>` code snippet, replace the `###` and paste inside the _last_ `<li></li>` tag

    ??? abstract "Code Snippet"
         ```html
         <a href="###">###</a>
         ```
    !!! note "The `<a>` Tag in HTML"
        The `<a>` tag, also known as the _anchor_ tag, defines a hyperlink in an HTML document. It creates a clickable link to another webpage, document, or resource. The `href` attribute specifies the URL of the destination, while the text content between the opening and closing tags serves as the visible link text.
   
9. Replace the first `###` inside the `href` attribute with a URL you want to link to (e.g., your social media profile, a favorite website, etc.)

10. Replace the second `###` inside the `<a>` tag with a descriptive text for the link (e.g., "Visit my LinkedIn profile", "Check out my favorite website", etc.):

    ```html title="Example"
    <a href="https://catoftheday.com/">Good website</a>
    ```


11. Wrap the `<h1>` and `<p>` elements you created in _step 1_ to _step 5_ inside a `<div>` tag:
    ```html title="Example"
    <div>
        <h1>Jasper's and Daylen's Webpage</h1>
        <p>We are CST students who love making websites using HTML and CSS.</p>
    </div>
    ```
         
    !!! note "The `<div>` Tag in HTML"
        The `<div>` tag defines a _division_ or section in an HTML document. It groups content together, allowing you to apply styles, structure layouts, and create reusable components. It is often used as a container for other elements, such as text, images, forms, and more.

12. Wrap the entire `<ul>` element you created in _step 6_ to _step 7_ inside a `<div>` tag:

    ```html title="Example"
    <div>
        <ul>
            <li>Our favorite snacks: potato chips</li>
            <li>Our favorite music genre: country</li>
            <li><a href="https://catoftheday.com/">Good website</a></li>
        </ul>
    </div>
    ```

!!! success

    You’ve successfully added some basic structure to your website set yourself up for easier styling in the future! Your html document should now look like this:
    
    ```html
    <div>
        <h1>Jasper's and Daylen's Webpage</h1>
        <p>We are CST students who love making websites using HTML and CSS.</p>
    </div>
    <div>
        <ul>
            <li>Our favorite snacks: potato chips</li>
            <li>Our favorite music genre: country</li>
            <li><a href="https://catoftheday.com/">Good website</a></li>
        </ul>
    </div>
    ```