# Final Project: Paradise Nursery Shopping Application

This project is the final assignment for the Developing Front-End Apps with React course, which is one of the 12 courses included in the IBM JavaScript Full-Stack Developer professional certificate offered by Coursera. The Paradise Nursery Shopping Application is a React-based web application where users can browse various plant categories, add them to a shopping cart, and proceed to checkout.

## Features

- React Components:

* Created functional components in React that are composed and nested to build the application interface.

- React Hooks:

* Implemented the useState and useEffect hooks to manage component-level states and lifecycle events.

- Redux Integration:

* Integrated Redux into the application for global state management. Used Redux concepts like actions, reducers, and the store to manage cart items, product data, and quantities.

- Dynamic Data Rendering:

* Dynamically rendered data from an array of plant objects, mapping over arrays to generate lists of components such as plant cards and shopping cart items.

- User Interactions:

* Handled user interactions like button clicks to add or remove items from the cart, and implemented the corresponding actions to update the Redux store.

- Cart Management:

* Displayed the total quantity of items in the cart and allowed users to adjust item quantities or remove items from the cart.

## Technologies Used

- React: For building the UI components and handling state management with hooks.
- Redux: For global state management across the application, specifically to handle cart state.
- JavaScript (ES6): Used throughout the application for functional logic, array manipulation, and rendering UI components.
- CSS: For styling the UI components and ensuring responsiveness across devices.

## Installation

1. Clone the repository:
   git clone https://github.com/yourusername/paradise-nursery.git

2. Navigate into the project directory:
   cd paradise-nursery

3. Install the required dependencies:
   npm install

4. Start the development server:
   npm run dev

Your application will be live at http://localhost:5173/shoppingreact

## How to Use

1. Browse through the available plant categories.
2. Click on the "Add to Cart" button to add a product to your cart.
3. Access the cart by clicking the shopping cart icon in the navbar.
4. View the items added to the cart, adjust quantities, and remove items.
5. Continue shopping or proceed to checkout.

## Challenges

- Implementing state management with Redux was a bit challenging, but once the concept of actions, reducers, and store was understood, it became easier to handle cart operations.

- Dynamically rendering the plant list from the objects and ensuring that the cart updates in real-time required some careful thought on data flow and state updates.

## Future Improvements

- Implement user authentication and a persistent cart that saves even after the browser is closed.
- Add a real-time product search and filter functionality to help users find plants easily.
- Style improvements to make the user interface more appealing, including animations and transitions.
