Create Your First Website

These days there is a website for everything. Learning to create to build your own website is invaluable, particularly if you need a site for your business or personal portfolio.

Many people prefer to use services like Wordpress or Squarespace. These are perfectly valid tool to create your website, but if you prefer building something from the ground up instead of using a template, you’ll need to learn the basics.

This project will go over the basics of HTML, CSS, and Javascript. It will teach you what each of these languages are used for, and how they all tie together. While this girtorial won’t build a website from start to finish, by the time you’ve completed it you should know enough to finish your website.

To get started you’ll want a text editor like [Atom](https://atom.io/) or [Notepad++](https://notepad-plus-plus.org/).


Commit 1

First will start with a fresh HTML doc. The first line of your document should always be <!DOCTYPE html>. This tells your web browser what kind of file to expect. Next you’ll want some html tags. The first <html> tag is the start of your document, and </html> will end it. The entirety of your website will live inside these two tags.

Commit 2

The <title> tag is is exactly that, the tittle of your page. Any text in-between these two tags will be displayed at top of your browser. The <head> tag is used for things that will not be shown on your page, but we’ll go over that later. The <body> tag will be the meat of your page. Everything between these two tags will be displayed on your page. If you open the document with your browser, you should see “Hello world!” on the page, and “My first website” in in the tab.

Commit 3

The <h1> tag signifies your heading. Multiple headings can be used to display by importance. You could for example, use <h2> as another heading, and it would be displayed with slightly smaller text. The <p> tag is for paragraphs. Any text inside the <p></p> tags will be signify a paragraph. To start another paragraph, simply type text into new <p> tags.

Commit 4

To add links to your site, you’ll use <a> tags. The href is the site you’d like to reference. You’ll put the link inside of the quotes. Any text inside of the <a> tags is how the link will be displayed. In this case, you should see a blue link that says “A Helpful Website.”

Commit 5

You can also easily make lists. <ul> tags stands for unorganized list. By default it’ll add bullets to your list items. Each item will needs it’s own <li> tags. As you’ve probably guessed <ol> is and organized list, which will add numbers to each item starting at 1.

Commit 6

Next we’ll want to start giving our site some style. To do this we’ll add a CSS file called “style.css”. While you can style you’re site directly in your HTML document, it’s a better idea to do it in another document (sometimes several different CSS documents) to help keep things organized. You’ll notice the link we added to the <head> tag. This will tell your html to find the css file. Right now this file is blank, so there won’t be any changes.

Commit 7

We’ll start with something simple. If we want something to be displayed the same way on the entire page, we can simply call the body of the html document here and change it’s background color. If you open the file again, you’ll see that it’s changed color.

Commit 8

We can also do this for specific parts of the document. If we want to make all of our unorganized lists to display italicized, we just call the ul tag in the css file and add the font-style. We can do this indecently of our organized list, which we want to be bold by adding font weight.
