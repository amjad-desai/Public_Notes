This parses your HTML and CSS files, removing unused CSS. 

If your projects include a CSS framework such as Bootstrap or use a reset stylesheet, consider adding UnCSS to your workflow. It will shave unnecessary CSS—and bytes—from your code.
UnCSS Installation

Install UnCSS using the following command:

`npm install -g uncss`

## Using UnCSS from the Command Line


UnCSS requires the file path or URL of an HTML page that contains a linked CSS file. For example:

`uncss https://yourwebsite.com/`

UnCSS will parse the HTML and its linked stylesheets, and print the optimized CSS to standard output. To redirect to a file, use the redirect operator ( > ):

`uncss https://yourwebsite.com/ > optimized.css`

You can also pass multiple file paths or URLs to the command line. UnCSS will analyze each file and dump optimized CSS that contains rules affecting one or more pages:

`uncss index.html article-1.html article-2.html > optimized.css`

For a full list of commands—and an example of how to use UnCSS with a Node.js script—consult the UnCSS docs.
