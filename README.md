<h1 align="center">
<br>
  <img src="https://img.icons8.com/external-justicon-lineal-color-justicon/256/external-google-social-media-justicon-lineal-color-justicon.png" alt="WIKI" width="120">
<br>
<br>
WIKI
</h1>

<p align="center">This is the Lecture 0 of CS50 web programming with python and javascript</p>
<h2> These are the Specifications of the project: </h2>
<p>

Using only HTML & CSS, design a front-end for Google Search, Google Image Search, and Google Advanced Search.

  <pre>
*Entry Page: Visiting /wiki/TITLE, where TITLE is the title of an encyclopedia entry, should render a page that displays the contents of that encyclopedia entry.
  *The view should get the content of the encyclopedia entry by calling the appropriate util function.
  *If an entry is requested that does not exist, the user should be presented with an error page indicating that their requested page was not found.
  *If the entry does exist, the user should be presented with a page that displays the content of the entry. The title of the page should include the name of the         entry.
*Index Page: Update index.html such that, instead of merely listing the names of all pages in the encyclopedia, user can click on any entry name to be taken directly to that entry page.
*Search: Allow the user to type a query into the search box in the sidebar to search for an encyclopedia entry.
  *If the query matches the name of an encyclopedia entry, the user should be redirected to that entry’s page.
  *If the query does not match the name of an encyclopedia entry, the user should instead be taken to a search results page that displays a list of all encyclopedia      entries that have the query as a substring. For example, if the search query were ytho, then Python should appear in the search results.
  *Clicking on any of the entry names on the search results page should take the user to that entry’s page.
*New Page: Clicking “Create New Page” in the sidebar should take the user to a page where they can create a new encyclopedia entry.
  *Users should be able to enter a title for the page and, in a textarea, should be able to enter the Markdown content for the page.
  *Users should be able to click a button to save their new page.
  *When the page is saved, if an encyclopedia entry already exists with the provided title, the user should be presented with an error message.
  *Otherwise, the encyclopedia entry should be saved to disk, and the user should be taken to the new entry’s page.
*Edit Page: On each entry page, the user should be able to click a link to be taken to a page where the user can edit that entry’s Markdown content in a textarea.
  *The textarea should be pre-populated with the existing Markdown content of the page. (i.e., the existing content should be the initial value of the textarea).
  *The user should be able to click a button to save the changes made to the entry.
  *Once the entry is saved, the user should be redirected back to that entry’s page.
*Random Page: Clicking “Random Page” in the sidebar should take user to a random encyclopedia entry.
*Markdown to HTML Conversion: On each entry’s page, any Markdown content in the entry file should be converted to HTML before being displayed to the user. You may use the python-markdown2 package to perform this conversion, installable via pip3 install markdown2.
</pre>

</p>
<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## [Project's video presentation](https://youtu.be/WN5BUtA0zIY)

## Features

This project only features the tools and practices that were requested.

- 📗 *Django* — Written using Python that allows for the design of web applications that generate HTML dynamically.
- 🔶 *HTML* — Markup language that can be used to define the structure of a web page.
- 🔷 *CSS* — CSS is a language that can be used to add style to an HTML page.

## Getting started



1. Clone this repo using <code> git clone git@github.com:Wjunior-l/mycs50projects.git</code>
2. Move yourself to the folder.
3. Run <code>pip install django</code>
4. Run <code>pip install markdown</code>



## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
