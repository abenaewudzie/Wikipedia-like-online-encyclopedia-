A Wikipedia-like-online-encyclopedia
Entry page
- The view should get the content of the encyclopedia entry by calling the appropriate util function.
- If an entry is requested that does not exist, the user should be presented with an error page indicating that their requested page was not found.
- If the entry does exist, the user should be presented with a page that displays the content of the entry. The title of the page should include the name of the entry.

 Index Page: Update index.html such that, instead of merely listing the names of all pages in the encyclopedia, user can click on any entry name to be taken directly to that entry page.

 SEARCH
- If the query matches the name of an encyclopedia entry, the user should be redirected to that entry’s page.
- If the query does not match the name of an encyclopedia entry, the user should instead be taken to a search results page that displays a list of all encyclopedia entries that have the query as a substring.
 For example, if the search query were Py, then Python should appear in the search results.
Clicking on any of the entry names on the search results page should take the user to that entry’s page.

Edit
- The textarea should be pre-populated with the existing Markdown content of the page. (i.e., the existing content should be the initial value of the textarea).
- The user should be able to click a button to save the changes made to the entry.
- Once the entry is saved, the user should be redirected back to that entry’s page.

- Random Page
- clicking "Random Page" in the sidebar should take user to a random encyclopedia entry.

- Markdown To HTML conversion
- On each entry page, any Markdwon content in the entry file should be converted to HTML before been displayed to the user. 
