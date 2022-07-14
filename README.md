# Vue Exercise
### Overview 
* Create a simple Vue3 site app (SPA?).
* Site sould have a login page to get the user name (no password).
  * Call API to predict the gender based on their name. 
  * Show `Hello {Mr.|Ms.} {Username}` in the header after the login.
* Present two menu options - `Country Profile` and `University List`
  * By default a user lands onto the last page he visited before or Country Profile if it is the first visit.
* Present country drop down.
* Country Profile should show facts for a selected country, present two panels beside with few facts in each.
* University List should show a table with a universities for a selected country, 10 records at a time

### APIs to use
* http://api.genderize.io/?name={Name} - Predict the gender of a person based on their name.
* http://restcountries.com/v3.1/all - Country list and facts.
* http://universities.hipolabs.com/search?country={CountryName} - University list for a selected country.

### Configuration part 
1. Create a simple site app using Vite  (https://vitejs.dev)
2. Configure Pinia store for state management (https://pinia.vuejs.org)
3. Configure API client using Axios
4. Use Tailwind CSS for styling

>**_Internal_**

>_Here we will look for candidate’s skills for setting up application structure, organising files and directories with proper titles for files._

### Application part 
* Get name from the user on application loading through Headless UI’s Combobox (https://headlessui.com/vue/combobox). 
* Store username in session. 
* Show `Hello {Username}` in the NavBar. 
* Make GET calls to the backend, set the username in the HTTP request headers. 
* Call GET API, let’s say `/posts` . 
* Store the data in Pinia store. 
* Show data on UI from the store using a table with pagination (10 records at a time) 
* Call a different GET API (for example `/comments`) and do the same steps for the response data as for the first API call. 

>**_Internal_**

>_Here we should look was candidate able to implement the essential requirement for the application. We will also look if candidate has implement bonus features. 
Along with features, we should also look for clean & readable code._

You can use this tool for API testing and prototyping - https://jsonplaceholder.typicode.com 


### Bonus Points 
* Configuration of an application from a file or environment variables like URLʼs of APIʼs to use, keys if any.
* API pagination
* Nice look & feel
* Responsive mobile friendly Design
* Cypress E2E Tests (https://cypress.io)
	

Apart from a working application, you should show: 
- A good structure of code 
- Readability of code 
- Reusability of Vue.js components 


