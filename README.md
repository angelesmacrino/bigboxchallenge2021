My submission to the Bigbox frontend challenge 2021.
  
https://angelesmacrino.github.io/bigboxchallenge2021/  
  
Made with Vue.js, scss, and Vue Select (https://vue-select.org/)  
  
## Bigbox's Frontend Challenge 2021

---

### Challenge

You will need to develop a frontend application for the Books API provided by the NYTimes. 

The app should consume the following API: 
https://developer.nytimes.com/docs/books-product/1/overview

To complete the assignment, you must provide the following functions:

1. Save the first 10 results given by the /lists/names.json endpoint.
    * As soon as the app is rendered, it should consume the endpoint to obtain the first 
      10 categories given by the endpoint. We are going to use this list to later search 
      or filter book titles.
2. Provide a selection of categories.
    * Before the user can search for a specific book, the user should select from the list
    of categories obtained in 1.
3. Provide a search bar.
    * Once the category is selected, a search bar should be enabled for the user to look 
      up for a book by its title. Once the user presses `Enter`, it should query the search
      using the API.
4. Show the search results.
    * After the search query to the API, show the `title`, `description` and `author` of 
      every results, if any.
5. Link to a Google Search for every result.
    * When the users clicks on a result, it should redirect them to a Google Search using 
      the title and author obtained in 4. __ie: <i>https://www.google.com/search?q=range+david+epstein__ </i>

