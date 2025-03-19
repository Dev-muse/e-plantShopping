# Paradise Nursery Shopping Application

## Introduction
Paradise Nursery is a fully functional shopping cart application designed for an online plant shop that offers a variety of house plants. This project was built using **React** with **Vite** for fast development and optimized performance.

## Features
- **Landing Page**
  - Includes a welcoming page with a button linking to the product listing page.
- **Navigation Bar**
  - Links to the Landing, Product Listing, and Shopping Cart pages.
- **Product Listing Page**
  - Showcases various plants with:
    - Images
    - Names
    - Descriptions
    - Prices
    - "Add to Cart" buttons
- **Product Sections**
  - Organized into categories like "Aromatic Plants" and "Medicinal Plants."
- **Cart Page**
  - Displays products added to the cart with:
    - Thumbnail images
    - Unit cost
    - Total cost for each item type
    - Quantity control buttons (Increase, Decrease, Delete)
- **Cart Summary**
  - Displays the total number of items and the total cost
- **Checkout Flow**
  - Includes "Continue Shopping" and "Checkout" buttons for seamless navigation.

## Technologies Used
- **React** (with Vite)
- **Redux** for state management
- **React Hooks** (e.g., `useState`, `useEffect`) for dynamic UI updates

## Installation
Follow these steps to run the project locally:

1. **Clone the Repository**
```bash
git clone <repository-url>
cd paradise-nursery
```

2. **Install Dependencies**
```bash
npm install
```

3. **Run the Development Server**
```bash
npm run dev
```

4. **Visit the Application**
- Open [http://localhost:5137](http://localhost:5137) in your browser.

## Deployment
To deploy the application using GitHub Pages:

1. Build the production files:
```bash
npm run build
```

2. Deploy using Vite's deployment guide or preferred hosting platform.

## Project Highlights
- Created functional **React components** using component composition and nesting.
- Implemented **React Hooks** to manage state and side effects.
- Integrated **Redux** for efficient state management across components.
- Dynamically rendered data by mapping over objects and updating UI elements accordingly.
- Handled events such as button clicks and conditionally render elements to enhance user experience.

## Contributing
If you'd like to contribute to improving this project, please fork the repository and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For further inquiries or suggestions, feel free to reach out! 😊

