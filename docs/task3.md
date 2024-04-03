# Styling your website

This section will show you how to style the content you added in the previous section. You’ll use  CSS selectors to specify which elements you’ll add which styles to.

## Styling the `li` elements

1. Open your `style.css` file and type your first CSS _selector_ `li`, following with a set of curly braces `{}`:

    ```css title="style.css"
    li {
    
    }
    ```
   
    !!! note "CSS selectors"
        CSS selectors are patterns used to select the elements you want to style. They target elements based on their type, class, or ID. In this case, the `li` selector targets all list items in your unordered list.   

2. Inside the curly braces, add the following properties and values:

    ??? abstract "Code Snippet"
         ```css
         color: red;
         text-decoration: underline;
         ```
    !!! note "CSS declarations"
        CSS declarations are made up of a property and a value. The property specifies the style you want to change, and the value specifies the new style. In this case, the `color` property changes the text color to red, and the `text-decoration` property underlines the text.

