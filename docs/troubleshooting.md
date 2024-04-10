# Troubleshooting
We've compiled a table of issues that may arise when completing your tasks. If you have an issue when carrying out a task, check the corresponding table for the symptoms you're experiencing and try the provided solution.

## Task 1: Setting up your webpage project

| Issue                                             | Related Step                             | What likely happened                            | How to fix it                                     |
|---------------------------------------------------|------------------------------------------|------------------------------------------------|---------------------------------------------------|
| Either index.html or style.css is missing from your project folder | Setting up your project directory, step 8 | You made the files outside of your project folder | Manually navigate to the project folder you created. Manually add the missing files with their extensions. |
| Hello World text appears but is not red when opened on browser    | Linking your CSS file to your HTML file, step 4 | The link you added in step 5 does match your style.css file name | Ensure that your stylesheet link in the header of your HTML file matches the filename of your CSS file exactly. |

## Task 2: Adding your information as HTML

| Issue                                 | Related Step               | What likely happened                   | How to fix it                                                                      |
|---------------------------------------|----------------------------|---------------------------------------|------------------------------------------------------------------------------------|
| The link you added does not work      | Building your website, Step 4 or 6 | The url you added is incomplete       | Ensure that the 'https://' is included in your url and that it is enclosed in double quotes |
| List content doesn’t have a bullet point | Building your website, step 7 | The content you added wasn’t wrapped correctly in list index tags | Recopy the code snippet from step 6 and replace all of the text from the opening `<ul>` tag to the closing `</ul>` tag with it. Replace the ### signs making sure to not replace any |

## Task 3: Styling your website

| Issue                                 | Related Step               | What likely happened                               | How to fix it                                                                 |
|---------------------------------------|----------------------------|----------------------------------------------------|-------------------------------------------------------------------------------|
| The class style you applied does not show up | Building your website, Step 4 | The class you added to the HTML does not match the declaration in style.css. | Ensure that the class="" has the case sensitive, full class declaration without the leading '.' inside the double quotes. |
| The id style you applied does not show up    | Building your website, Step 6 | The id you added to the HTML does not match the declaration in style.css.    | Ensure that the id="" has the case sensitive, full class declaration without the leading '#' inside the double quotes.    |
