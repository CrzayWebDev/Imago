# Case study - Frontend development 


## Topic
IMAGO Images sells licenses for media to our customers. For this we offer a website on which our customers can find and purchase these licenses.
Your task is to build a page with a search bar, where customers can enter specific search terms and view the media results.
When a user clicks on one of the media returned from their search, they get more information on the selected media and get the option to add it to their shopping cart.

## Goal
Create a website using JavaScript and React.
This website connects to a RESTful API to send requests and receive responses.
The website is able to show media previews and help the customer select the media they want to purchase.

By creating this website you show that you are able to use version control and give your commit messages meaningful names.
You name functions, variables and classes in a way that other developers quickly understand their behavior and follow a consistent code style.
By following the design we have provided you show that you have a feeling for aesthetics and can improvise if things are not defined down to the last pixel.
Make sure to document your code enough so no questions come up during the reading of the code.

## Features
### 1. Search Bar
Create a page where the user can enter a search term into the search bar at the top of the page.
When the user presses enter, send an API request to the backend that contains the search term the user entered.
### 2.  Search Results
Receive the API response and display the media previews. The media needs to be displayed in the same order as in the API response.
Each media preview is clickable and redirects the user to a new page.
### 3. Single Media View
Create a page where all information on a media is being displayed.
To get this information send a request to the backend.
This page should display the following information:
- caption
- creation date
- creator
- height & width of the media
- preview (mediasrc)
- price of both licences in Euro (usagelicences/price)


## Resources
### API

- DataURL: https://1780bf9a-10a6-4235-8605-39539ff6a76b.mock.pstmn.io
- TestData: https://drive.google.com/drive/folders/1LUDwf6lUefFSsSHqmfOx4791-Nc7Xh6z?usp=sharing 
- Figma: https://www.figma.com/file/CUs4YuYfwgaJMEaGYrbx1A/IMAGO-Search-Frontend-Developer-Test?node-id=283%3A173&t=QYf38BecCcFfQ92h-1
