# #VanLife 🚐

#VanLife is a React-based web application designed for van enthusiasts to rent vans and manage their listings. The project utilizes **React Router** to create a seamless, single-page application (SPA) experience with complex routing requirements.

## Live Link

https://vanlife-three-beryl.vercel.app/

## Demo

<img width="2340" height="2340" alt="Image" src="https://github.com/user-attachments/assets/8d2c0672-231b-4209-9363-a68ffdd50273" />

<img width="2340" height="2340" alt="Image" src="https://github.com/user-attachments/assets/a0fabf8c-2871-4422-9189-5d8f3073609d" />

## 🚀 Features

- **Van Exploration**: A dedicated Vans page listing all available vans with filtering capabilities.
- **User Dashboard**: A central hub for van owners to see an overview of their account.
- **Income Tracking**: Detailed breakdown of net income generated from van rentals.
- **Reviews Management**: A section to view and manage feedback from renters.
- **Dynamic Routing**: Individual detail pages for each van using URL parameters.
- **Nested Layouts**: Utilizing shared layouts for the Host dashboard and main application navigation.
- **Dummy Backend**: Used Mirage.js to mimmic backend.

## 🛠️ Tech Stack

* **Frontend**: React.js
* **Routing**: React Router v6 (Data APIs)
* **Styling**: CSS3 / Built with a mobile-first approach
* **Deployment**: Vercel
* **Backend**: Mirage.js

## 📁 Project Structure & Routing

The application implements several advanced routing patterns:

- `/` - Home page
- `/about` - About the #VanLife mission
- `/vans` - List of all listed vans
- `/vans/:id` - Individual van details
- `/host` - **Host Dashboard (Protected/Nested Routes)**
    - `/host/income` - Net income stats
    - `/host/vans` - Listed vans by the current host
    - `/host/reviews` - Renter reviews

## 💻 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/VanLife.git](https://github.com/YourUsername/VanLife.git)
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```

4.  **Build for production:**
    ```bash
    npm run build
    ```

## 📝 Lessons Learned

This project was built to master **React Router v6**, focusing on:
- `Link` and `NavLink` for navigation.
- `useSearchParams` for filtering vans (Price, Type).
- `useParams` for fetching specific van data.
- `Outlet` for nested layout rendering.
- `Loader` and `Action` functions for data fetching and form handling.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
