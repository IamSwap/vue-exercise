# Vue Exercise
### Overview 
**Figma Prototype:** https://www.figma.com/proto/GEaogWZluk5P3twInDx5Lb/Exercise-Mockup

* Create a simple Vue3 site app (SPA).
* Site sould have a login page to get the user name.
  * Call API to predict the gender based on their name. 
  * Show `Hello {Mr.|Ms.} {Username}` in the header after the login in the header.
* Present country drop down with proceed button.
* Present a page with header which has two menu options - `Country Profile` and `University List`
* Country Profile page should show facts for a selected country, present two panels beside with few facts in each.
* University List page should show a table with a universities for a selected country, 10 records at a time

### APIs to use
* http://api.genderize.io/?name={Name} - Predict the gender of a person based on their name.
* http://restcountries.com/v3.1/all - Country list and facts.
* http://universities.hipolabs.com/search?country={CountryName} - University list for a selected country.

### Configuration part 
1. Create a simple site app using Vite  (https://vitejs.dev)
2. Configure routes using Vue Router (https://router.vuejs.org/)
2. Configure Pinia store for state management (https://pinia.vuejs.org)
3. Configure API client using Axios (https://github.com/axios/axios)
4. Use Tailwind CSS for styling (https://tailwindcss.com/)

### Application part 
* On the login page, get name from the user using input box; Store username in session. 
* After the login page, show country selector with proceed button. (Country selector should use Combbox Element from https://headlessui.com/vue/combobox)
* Call countries API `http://restcountries.com/v3.1/all` ; Store the data in Pinia store. 
* Show page with header which has two menu options - `Country Profile` and `University List`
* Along with menus, show `Hello {Mr.|Ms.} {Username}` in the Header/NavBar with logout button. 
* On the Country Profile page, show facts for a selected country, present two panels beside with few facts in each.
* On the University List page, show a table with a universities for a selected country, 10 records at a time.
* To fetch university list for a country use `http://universities.hipolabs.com/search?country={CountryName}` API.
* Both pages should have a Country switcher, so on switching country, data on both pages should change.

### Evaluation
* Satisfaction of functional requirements.
* Architecture of project - folder/file structure and code structure. 
* Separation of Code, Data and Configuration.
* Readability of code - coding consistency, self-documented code.
* Reusability of code - Vue.js components, etc.

### Bonus Points 
* Nice look & feel
* Responsive mobile friendly Design
