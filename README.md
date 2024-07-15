
# Approach:

## 
Create a component (React Component) folder in src folder and inside that folder make three JS file i.e.



### BillDetails.js
In BillDetails.js file it is responsible for capturing user input for individual items in a bill or invoice. It includes fields for item names, quantities, and prices, along with functionality for adding items to the list and deleting the last entered item.


### ItemsList.js
In ItemsList.js file is dynamically renders and displays the list of items in a bill or invoice.


### TotalAmount.js 
The TotalAmount.js file is for calculating and displaying the total amount of the bill or invoice. It receives the list of items as props (Props), performs the necessary calculations, and presents the total amount in a clear and formatted manner.


### App.js
App.js file is the main React component for the the project. It manages the overall state, handles user interactions such as adding and deleting items, calculates the total amount, and integrates PDF generation functionality, providing the core logic for the entire web application.


### Index.js
Index.js file is the entry point for a React application. It uses the ReactDOM library to render the root component (in this case, the App component) into the HTML document. And similarly index.css is the main css of web application for giving designing and animation to projects.

Once all the code is done and compiled successfully , you will see a page where you have to input item name then its quantity and each price.

Then click on Add item button to add on the list. and you also delete the items according to your wish.
Also you can download the bill in pdf form by clicking on download button.
## Steps to Create the React App:

Step 1: Set up React Project using the Command:

npx create-react-app invoice-bill

Step 2: Navigate to the Project folder using:

cd invoice-bill

Step 3: Installing the dependencies.

npm i jspdf

npm start

Step 3: Create a folder “components” and add three new files in it namely BillDetails.js, ItemList.js and TotalAmount.js.

Project Structure:

The updated dependencies in package.json file will look like:

"dependencies": {
    "jspdf": "^2.5.1",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4",
}

Steps to Run the Application:

Step 1: Type the following Command in terminal:

npm run start
