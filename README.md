# Vue Exercise
### Overview 
* Create a simple Vue3 site app (SPA).
* Site sould have a login page to get the user name (no password).
  * Call API to predict the gender based on their name. 
  * Show `Hello {Mr.|Ms.} {Username}` in the header after the login in the header.
* Present country drop down with proceed button.
* Present a page with header which has two menu options - `Country Profile` and `University List`
  * By default a user lands onto the last page he visited before or Country Profile if it is the first visit.
* Country Profile page should show facts for a selected country, present two panels beside with few facts in each.
* University List page should show a table with a universities for a selected country, 10 records at a time

### APIs to use
* http://api.genderize.io/?name={Name} - Predict the gender of a person based on their name.
* http://restcountries.com/v3.1/all - Country list and facts.
* http://universities.hipolabs.com/search?country={CountryName} - University list for a selected country.

**Figma Prototype:** https://www.figma.com/proto/GEaogWZluk5P3twInDx5Lb/Exercise-Mockup

### Configuration part 
1. Create a simple site app using Vite  (https://vitejs.dev)
2. Configure routes using Vue Router (https://router.vuejs.org/)
2. Configure Pinia store for state management (https://pinia.vuejs.org)
3. Configure API client using Axios (https://github.com/axios/axios)
4. Use Tailwind CSS for styling (https://tailwindcss.com/)

### Application part 
* On the first page, get name from the user using input box. 
* Store username in session. 
* On the next page, show country selector with proceed button. (Country selector should use Combbox Element from https://headlessui.com/vue/combobox)
* Call countries API. For ex. `http://restcountries.com/v3.1/all` . 
* Store the data in Pinia store. 
* Show page with header which has two menu options - `Country Profile` and `University List`
* Along with menues, show `Hello {Mr.|Ms.} {Username}` in the Header/NavBar with logout button. 
* On the Country Profile page, show facts for a selected country, present two panels beside with few facts in each.
* And on the University List page, show a table with a universities for a selected country, 10 records at a time.
* To fetch university list for a country use `http://universities.hipolabs.com/search?country={CountryName}` API.
* Bonus: Both pages should have a Country switcher, so on switching country, data on both pages should change.

### Bonus Points 
* Configuration of an application from a file or environment variables like URLʼs of APIʼs to use, keys if any.
* API pagination
* Nice look & feel
* Responsive mobile friendly Design
	

Apart from a working application, you should show: 
- A good structure of code 
- Readability of code 
- Reusability of Vue.js components 


