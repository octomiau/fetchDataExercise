# fetchDataExercise
A React application that fetches and displays data from the Hacker News Algolia API. It supports pagination and allows users to search for specific content.

## 🌟Features:

- **Search Bar:** Allows users to fetch articles based on specific queries from Hacker News Algolia API.
- **Pagination:** Dynamically displays pages based on the total number of items and a given page size.
- **Responsive:** Displays loading and error messages based on the status of the API call.

## 🔧 Installation:
1. Clone this repository:
```bash
git clone [repository-url]
```
3. Navigate to the project directory:

  ```bash
cd fetchDataExercise
  ```
3. Install the required dependencies (ensure you have node and npm installed):
   
  ```bash
npm install
  ```
**Notes:** Make sure to replace `[repository-url]` with the actual URL of your repository. This README provides a brief overview of the code and its features. Adjustments might be needed based on the actual functionality and additional context about the project.

## 🚀 Usage:

1. Start the application:
   
```bash
npm start
```
2. Open a web browser and navigate to http://localhost:3000.
3. Use the search bar to query for articles and navigate through the results using the pagination buttons.

## 🔎 Code Details:

- **useDataApi Hook:** A custom hook to fetch data from an API. It manages the loading, success, and error states using the useReducer hook.</li>
- **Pagination Component:** A stateless component that displays the pagination buttons based on the total number of items and a given page size.
- **dataFetchReducer:** A reducer function to manage the different states (loading, success, error) of our data fetching process.
- **App Component:** The main component which integrates the search bar, the fetched data display, and the pagination component.

## ⚠️ Known Issues:

-If the API endpoint changes or has downtime, the application may not display content properly.
-The application does not handle deep pagination, i.e., it might not work correctly if there are a large number of pages.


## 🤝 Contributions:

Feel free to raise issues or submit pull requests if you find any problems or have suggestions to improve the component.

## 📜 License:

This component is open-sourced under the [MIT License](https://opensource.org/licenses/MIT).


